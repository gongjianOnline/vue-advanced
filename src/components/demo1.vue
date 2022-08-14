<!--  -->
<template>
  <div>demo1</div>
</template>

<script>
import myExtends from "../mixins/log.js"
export default {
  name:"fuckEslintComponent",
  data () {
    return {
      name:"demo1"
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