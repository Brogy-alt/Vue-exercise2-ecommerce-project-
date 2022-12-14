<template>
  <body>
    
 
  <div class="hello">
    <h1>{{ msg }}</h1>
    
    <div class="home">
    <img alt="Vue logo" src="https://i.postimg.cc/xCs5pvBd/Rent-a-Girlfriend-English-Logo.webp">
    <h1>South Africa</h1> 
  </div>
    
  </div>
</body>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

body{
  height: 100vh;
  width: 100vw;
}

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


</style>
