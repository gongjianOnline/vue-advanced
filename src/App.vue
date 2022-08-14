<!--  -->
<template>
  <div id="app">
    <DirectiveComponents></DirectiveComponents>
  </div>
</template>

<script>
import DirectiveComponents from "./components/directiveComponent"
export default {
  name:"appComponents",
  data () {
    return {
    };
  },

  components:{
    DirectiveComponents
  },

  computed:{},

  mounted(){},

  methods:{}
}

</script>
<style scoped>
</style>