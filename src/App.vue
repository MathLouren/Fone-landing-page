<template>
  <div id="app">
    <Header />
    <Produto />
  </div>
</template>

<script>
import Header from "@/components/Header.vue"
import Produto from "@/components/Produto.vue"


export default {
  name: "App",
  components: {
    Header,
    Produto
  },
};
</script>

<style>

@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&display=swap');

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

ul{
  list-style: none;
}

a{
  text-decoration: none;
}
</style>
