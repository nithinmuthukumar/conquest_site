<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <NavigationBar v-bind:curpage="curpage"></NavigationBar>
  </div>
</template>
<script>
  import NavigationBar from "./components/NavigationBar.vue"

  export default {
    name: 'app',
    components: {
      NavigationBar

    },
    data(){
      return {
        user:"",
        curpage:"Home"

      }
    },
    props:{
      switchPage:function () {

      }

    },
    methods:{






    },
    mounted: function(){


    }
  }
</script>


<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
