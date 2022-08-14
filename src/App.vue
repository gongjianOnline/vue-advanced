<!--  -->
<template>
  <div id="app">
    <Dome1></Dome1>
  </div>
</template>

<script>
import Dome1 from "./components/demo1.vue"
export default {
  name:"appComponents",
  data () {
    return {};
  },
  provide(){
    return {
      test:"这是一个字符串",
      handelTest:this.handelClick
    }
  },

  components:{
    Dome1
  },

  computed:{},

  mounted(){},

  methods:{
    handelClick(){
      console.log("this is handelClick")
    }
  }
}

</script>
<style scoped>
</style>