<template>
  <div id="app">
    <Header />
    <main>
      <Produto />
    </main>
    <Footer />
  </div>
</template>

<script>
import Header from "@/components/Header.vue"
import Produto from "@/components/Produto.vue"
import Footer from "@/components/Footer.vue"


export default {
  name: "App",
  components: {
    Header,
    Produto,
    Footer
  },
};
</script>

<style>

@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&display=swap');

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Roboto',sans-serif;
}

#app{
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  overflow: hidden;
}

main{
  flex: 1;
}

body{
  display: flex;
  flex-direction: column;
}

ul{
  list-style: none;
}

a{
  text-decoration: none;
}
</style>
