<template>
  <div id="app">
    <div class="style1">
      <img width="50%" src="./assets/logo-0.png">
      <pack1/>
      <pack2/>
    </div>
  </div>
</template>

<script>
import pack1 from "./components/main";
import pack2 from "./components/camera";
export default {
  name: "App",
  components: {
    pack1,
    pack2
  },
  mounted() {
    let camScript = document.createElement("script");
    camScript.setAttribute("src", "./components/camera.js");
    document.head.appendChild(camScript);
  }
};
</script>




<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.style1 {
  background-size: cover;
  background-color: #101520;
  background-image: url("./assets/6592-2.png");
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}
</style>
