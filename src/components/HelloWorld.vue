<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Arii,inc でフロントエンジニアしています。Vue,Nuxt,に加えて最近ReactNativeとか触ってます。
    </p>
    <h3>質問がある場合はTwitterまでどうぞ</h3>
    <a href="https://twitter.com/iba_ragi">@iba_ragi</a>
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
