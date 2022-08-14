<!--  -->
<template>
  <div>demo1</div>
</template>

<script>
import log from "../mixins/log.js"
export default {
  name:"fuckEslintToComponent",
  data () {
    return {
      name:"demo2"
    };
  },
  mixins:[log],

  computed:{},

  mounted(){},

  methods:{

  }
}

</script>
<style scoped>
</style>