<template>
  <div class="hello">
    <div class="main">
      <div class="left">
        <!-- Левый блок -->
        <div class="block">
          <p>ФИО</p>
        </div>
        <div class="block">
          <p>Компания</p>
        </div>
        <div class="block">
          <p>Адрес</p>
        </div>
      </div>

      <div class="right">
        <!-- Правый -->
        <div class="block2"></div>

        <div class="button"></div>
      </div>
    </div>
  </div>
</template>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}

* {
  margin: 0;
}

.top {
  position: absolute;
  width: 100%;
  height: 20%;
  background: #2F4F4F;
}

.block {
  background: #D3D3D3;
  position: inherit;
  height: 10%;
  margin: 4%;
  padding: 10px;
  border-radius: 5px;
}

.block p {
  position: relative;
  font-size: 2em;
  text-align: center;
}

.main {
  position: relative;
  width: 100%;
  height: 100%;
}

.left {
  width: 40%;
  height: 100%;
  position: relative;
  margin: 2%;
  display: inline-block;
  vertical-align: top;
  background: #778899;
  padding: 10px;
  border-radius: 5px;
}

.right {
  height: 100%;
  position: inherit;
  width: 40%;
  margin: 2%;
  display: inline-block;
  background: #778899;
  padding: 10px;
  border-radius: 5px;
}

.menu {
  margin-left: 90%;
  width: 11%;
  height: 100%;
  position: inherit;
  background: #2F4F4F;
}

.block2 {
  position: relative;
  margin: 4%;
  background: #D3D3D3;
  padding: 10px;
  border-radius: 5px;
}

.button {
  position: relative;
  width: 35%;
  margin: 4%;
  background: #D3D3D3;
  padding: 10px;
  border-radius: 5px;
}

.stat {
  background: #D3D3D3;
  position: relative;
  left: 10%;
  width: 80%;
  height: 12%;
  margin-top: 8%;
}

.stat h1 {
  text-align: center;
  position: inherit;
  font-size: 2em;
  top: 22%;
}

.description {
  position: relative;
  margin-top: 8%;
  width: 80%;
  min-height: 40%;
  background: #D3D3D3;
  margin-left: 10%;
}

.description p {
  font-size: 1.2em;
}

.description2 {
  position: relative;
  margin-top: 8%;
  width: 75%;
  min-height: 40%;
  background: #D3D3D3;
  margin-left: 12%;
}
</style>
