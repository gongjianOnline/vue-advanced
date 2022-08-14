<!--  -->
<template>
  <div>
    <button v-test:click="handleClick">click</button>
  </div>
</template>

<script>
export default {
  name:"fuckEslintComponent",
  data () {
    return {
    };
  },
  directives:{
    test:{
      inserted(el,info){
        el.addEventListener(info.arg,info.value)
      },
      unbind(el,info){
        el.removeEventListener(info.arg)
      }
    }
  },

  computed:{},

  mounted(){},

  methods:{
    handleClick(){
      console.log("this is click")
    }
  }
}

</script>
<style scoped>
</style>