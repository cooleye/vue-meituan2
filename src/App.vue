<template>
  <div id="app">
      <router-view></router-view>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
    
  }
}
</script>

<style>
html,body{
  width: 100%;height: 100%;
}
body{
  margin: 0;padding: 0;
  background: #f0efed;
  overflow-x: hidden;
  overflow-y: hidden;
}
#app {
  font-family: "Helvetica Neue",Helvetica,Arial,sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
  width: 100%;height: 100%;
  overflow-y: scroll;
}
/*包含以下四种的链接*/
a {
    text-decoration: none;
    color: #666;
}
/*正常的未被访问过的链接*/
a:link {
    text-decoration: none;
}
/*已经访问过的链接*/
a:visited {
    text-decoration: none;
}
/*鼠标划过(停留)的链接*/
a:hover {
    text-decoration: none;
}
/* 正在点击的链接*/
a:active {
    text-decoration: none;
}

ul{
  list-style: none;
  margin: 0;
  padding: 0;
}
h1,h2,h3,h4,h5,h6{
  padding: 0;
  margin: 0;
}
p{
  margin: 0;
  padding:0;
}
</style>
