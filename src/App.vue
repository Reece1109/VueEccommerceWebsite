<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about"> About </router-link> |
    <router-link to="/contact"> Contact Page </router-link>|
    <router-link to="/products"> Products </router-link>|
    <router-link to="/footer"> Footer </router-link>|
  </nav>


  <router-view/>

</template>

<script>
// // import data //Fetching the data
// import About  from "./components/About.vue";


export default {    //Accessing the Data
  components:{
  },
  data() {
    return {
      imageUrl: ''
    }
  }
}

</script>

<style scoped>

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

home {
background-image: url(https://i.postimg.cc/d09b9kqF/RS7ILR22.webp);
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}
nav a.router-link-exact-active {
  color: #42b983;
}
</style>
