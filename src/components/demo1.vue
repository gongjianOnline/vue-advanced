<!--  -->
<template>
  <div>
    <div>demo1 {{test}}</div>
    <button @click="handelTest">handelClick</button>
  </div>
</template>

<script>
export default {
  name:"fuckEslintComponent",
  data () {
    return {
      name:"demo1"
    };
  },
  inject:["test","handelTest"],

  computed:{},

  mounted(){},

  methods:{

  }
}

</script>
<style scoped>
</style>