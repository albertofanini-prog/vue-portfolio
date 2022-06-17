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
  color: #42b983;
}

/* img{
  width: 100%;
  height: 100%;
} */

router-view{
  width: 100%;
  display: flex;
  align-items: center;
}

body{
  display: flex;
  justify-content: center;
  /* align-items: center; */
  min-height: 100vh;
  width: 100%;
  background-color: #1A1E23;
}

body::-webkit-scrollbar-track
{
	-webkit-box-shadow: inset 0 0 6px rgba(0,0,0,0.3);
	background-color: #F5F5F5;
}

body::-webkit-scrollbar
{
	width: 6px;
	background-color: #F5F5F5;
}

body::-webkit-scrollbar-thumb
{
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

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
