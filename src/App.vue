<template>
  <div id="app">
    <div id='glass'>
      <img src="http://t2.hddhhn.com/uploads/tu/201805/9999/96914b42c6.jpg">
      <div id='glass_bottom'></div>
    </div>
    <Home msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import Home from './View/Home/Home.vue';
// import { device } from './common/Utils';

export default {
  name: 'app',
  components: {
    Home
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  /* background-color: aqua; */
}
#glass {
  /* background: rgba(0, 0, 0, .4); */
  /* background-color: rgb(196, 72, 72); */
  width: 100%;
  height: 200px;
  /* filter: blur(6px); */
}
img {
  height: 200px;
}

#glass_bottom {
  /* background: url('http://t2.hddhhn.com/uploads/tu/201805/9999/96914b42c6.jpg'); */
  background-color: rgb(43, 46, 226);
  position: absolute;
  filter: blur(10px);
  height: 200px;
  width: 600px;
  margin-top: -200px;
  z-index: -1;
}
</style>
