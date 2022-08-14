<!--  -->
<template>
  <div id="app">
    <Dome1 v-if="child1Visible"></Dome1>
    <button @click="child1Visible = false">x</button>
    <Dome2 v-if="child2Visible"></Dome2>
    <button @click="child2Visible = false">x</button>
  </div>
</template>

<script>
import Dome1 from "./components/demo1.vue"
import Dome2 from "./components/demo2.vue"
export default {
  name:"appComponents",
  data () {
    return {
      child1Visible:true,
      child2Visible:true
    };
  },

  components:{
    Dome1,
    Dome2
  },

  computed:{},

  mounted(){},

  methods:{}
}

</script>
<style scoped>
</style>