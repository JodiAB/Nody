<template>
  <div class="fire">
    <nav> <Navi /></nav>
   
  
    <router-view />
    <Spinner />
    <Footer />
  </div>
</template>
<script>
import Navi from '@/components/Navi.vue'; // Adjust the import path based on your project structure
import Footer from '@/components/Footer.vue';
import Spinner from '@/components/Spinner.vue';
export default {
  components: {
    Navi,
    Footer,
    Spinner

    
  
  },
};
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: beige;
  background-color: navy;
  height: 100vh;
}

nav {
  padding: 13px;
  display: flex;
  justify-content: center;
  gap:1rem;
  color: beige;
}

nav a {
  font-weight: bold;
  color: beige;

}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
