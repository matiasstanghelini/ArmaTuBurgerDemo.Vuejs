
<template>
  <div>
    <div id="nav">
      <router-link id="logo-url" to="/">
        <img id="logo" :src="logo" :alt="alt">
      </router-link>
      <router-link to="/">Hacer un Pedido</router-link>
      <router-link to="/pedidos">Mis Pedidos</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: "Navbar",
  props: ["logo", "alt"]
}
</script>

<style scoped>
  #nav {
    background-color: rgb(37, 5, 68);
    border-bottom: 4px solid rgb(255, 167, 3);
    padding: 15px 50px;
    font-weight: bold;
    display: flex;
    justify-content: flex-end;
    align-items: center;
  }
  #nav #logo-url {
    margin: auto;
    margin-left: 0;
  }
  #logo {
    width: 40px;
    height: 40px;
  }
  #nav a {
    color: #ffffff;
    text-decoration: none;
    margin: 12px;
    transition: .5s;
  }
  #nav a:hover {
    color: rgb(50, 48, 66);
  }
</style>