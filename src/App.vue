<template>
  <router-view />
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif; */
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}

body {
  padding: 0;
  margin: 0;
}

.logo {
  width: 150px;
}

.register input,
.login input,
.addR input {
  width: 300px;
  height: 40px;
  padding-left: 20px;
  display: block;
  margin-bottom: 30px;
  margin-right: auto;
  margin-left: auto;
  border: 1px solid #110c24;
  border-radius: 0.5rem;
  opacity: 90%;
}

.register button,
.login button,
.addR button {
  width: 320px;
  height: 40px;
  background: black;
  color: white;
  cursor: pointer;
  border-radius: 0.5rem;
}

.heading {
  margin-bottom: 3%;
}

html {
  background-color: #120c24;
}
</style>
