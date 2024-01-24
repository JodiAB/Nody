<!-- NavBar.vue -->

<template>
    <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/shop">Shop</router-link> |
      <router-link to="/Cart">Cart</router-link> |
      <router-link to="/Contact">Contact</router-link> |
      <router-link to="/Admin">Admin</router-link>
    </nav>
  </template>
  
  <script>
  export default {

  };
  </script>
  
  <style scoped>
  nav {
    display: flex;
    justify-content: center;
    padding: 20px;
    background-color: transparent;
    text-align: center;
    width: 100%;
    font-size: 18px;
    gap: 6rem;
  }
  
  nav a {
    font-weight: bold;
    color: darkgoldenrod;
  }
  
  nav a.router-link-exact-active {
    color: beige;
  }
  </style>
  