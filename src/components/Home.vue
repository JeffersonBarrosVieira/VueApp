<template>
  <div id="home">
    <img id="logo" alt="Vue logo" src="@/assets/icone-720x720.png">
    <h1>{{ msg }} {{ teste }}</h1>
  </div>
</template>

<script>
  export default {
    name: 'HelloWorld',
    props: {
      msg: String,
      teste: String
    }
  }
</script>

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

  #home {
    width: 100%;
    height: calc(100vh - 120px);
    background-color: #f0f0f0;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }

  #logo {
    width: 250px;
  }
</style>
