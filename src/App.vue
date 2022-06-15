<template>
  <PortfolioNavbar/>
  <router-view/>
</template>

<script>
import PortfolioNavbar from '@/components/PortfolioNavbar.vue'
export default {
  components:{
    PortfolioNavbar
  }
}
</script>

<style>
router-view{
  width: 100%;
  display: flex;
  align-items: center;
}

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

ul{
  list-style: none;
}

a{
  text-decoration: none;
}

/* img{
  width: 100%;
  height: 100%;
} */

body{
  display: flex;
  justify-content: center;
  /* align-items: center; */
  min-height: 100vh;
  width: 100%;
  background-color: #1A1E23;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  width: 100%;
}

nav {
  height: 75px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
