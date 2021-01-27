<template>
  <div id="app">
    <svg-icon icon-class="test" className="test"></svg-icon>
    <svg-icon icon-class="talk" className="talk"></svg-icon>
     <svg-icon icon-class="volume"></svg-icon>
  </div>
</template>

<script>
export default {
  name: 'App',
  components: {

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
  margin-top: 60px;
}
.test {
  color: #fff;
  cursor: pointer;
  background: blueviolet;
  border-radius: 50%;
  padding: 2px;
  width: 30px;
  height: 30px;
}

.test:hover {
  color: #000;
  background: chartreuse;
}

.talk {
  color: chartreuse;
}

.talk:hover  {
  color: #000;
}
</style>
