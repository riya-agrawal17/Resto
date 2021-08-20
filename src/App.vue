<template>
  <router-view />
</template>

<script>
export default {
  name: 'App',
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
body {
  padding: 0;
  margin: 0;
}
.logo {
  width: 100px;
}
.register input,
.login input,
.add input {
  width: 300px;
  height: 40px;
  padding-left: 20px;
  display: block;
  margin-bottom: 30px;
  margin-right: auto;
  margin-left: auto;
  border: 1px solid lightgreen;
}
.register button,
.login button,
.add button {
  width: 320px;
  height: 40px;
  background: rgb(46, 63, 46);
  border: 1px solid rgb(47, 77, 47);
  color: white;
  cursor: pointer;
}
.delete-btn {
  width: 80px;
  height: 30px;
  background: red;
  border: 1px solid red;
  color: white;
  cursor: pointer;
}

.links,
.sign {
  color: #3a72a7;
  text-decoration: none;
  margin-right: 15px;
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande',
    'Lucida Sans', Arial, sans-serif;
}
</style>
