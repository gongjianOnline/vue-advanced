<!--  -->
<template>
  <div>demo1</div>
</template>

<script>
import myExtends from "../mixins/log.js"
export default {
  name:"fuckEslintToComponent",
  data () {
    return {
      name:"demo2"
    };
  },
  extends:myExtends,

  computed:{},

  mounted(){},

  methods:{

  }
}

</script>
<style scoped>
</style>