<template>
  <div id="app">
    <the-header />
     <router-view />
    <the-footer />
  </div>
</template>

<script>
    
    import TheHeader from "./components/global/TheHeader.vue";
    import TheFooter from "./components/global/TheFooter.vue";
    
    
export default {
    name: "app",
    components: {
        TheHeader,
        TheFooter
    }

}
    
</script>

<style lang="scss">
    html, body {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: sans-serif !important
    }
::-webkit-scrollbar {
  width: 8px;
}
::-webkit-scrollbar-thumb {
  background: #000
}    

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
