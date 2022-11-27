<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div class="haneul-card" style="width: 304px; height: 296px;">
      <div class="header"><strong>Secondary Text</strong></div>
      <h5 class="title">Hello World</h5>
      <p class="body">This is just a testing text. This is just a testing text.</p>
      <div class="footer"><span>Lim Ah Kao</span><span class="divider"></span><span>10 Aug 2022</span></div>
    </div>
  </div>
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
