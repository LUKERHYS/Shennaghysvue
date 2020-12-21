<template>
  <div class="container">
    <header>
        <div id="nav">
          <router-link to="/">Home</router-link>
          <router-link to="/about">About</router-link>
          <router-link to="/artists">Artists</router-link>
        </div>
        <div class="logo-flag">
          <img class="logo-image" src="./assets/head-logo.png" alt="">
        </div>
    </header>
    <div class="content">
      <main>
        <router-view/>
      </main>
    </div>
  </div>
</template>

<script>
export default {
};
</script>

<style>
div{
  border: blue solid 1px;
}
.container {
  width: 100vw;
  display: block;
  justify-content: space-between;
  margin: 0;
   font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 0;
}
header {
  display: flexbox;
}
#nav {
  top: 0;
  left: 0;
  display: flex;
  justify-content: flex-end;
  width: 100vw;
  background-color: #E20A15;
  z-index: -1;
  -webkit-box-shadow: 0px 7px 19px -9px rgba(0,0,0,0.5);
  -moz-box-shadow: 0px 7px 19px -9px rgba(0,0,0,0.5);
  box-shadow: 0px 7px 19px -9px rgba(0,0,0,0.5);
}
#nav a {
  font-weight: bold;
  font-size: 25px;
  color: rgb(37, 37, 37);
  padding: .6em .6em .6em 0;
}
#nav a.router-link-exact-active {
  color: #FED000;
}
.logo-flag {
  position: absolute;
  z-index: 2;
  top: 0;
  display: flex;
  justify-content: center;
  max-width: 12%;
  background-color: #F2F1E8;
  margin-left: 5%;
}
.logo-image{
  max-width:75%;
  max-height: 75%;
  padding: 1em;
}
</style>
