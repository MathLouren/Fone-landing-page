<template>
  <header>
      <div class="logo">
          <img src="../assets/logo.svg" alt="">
      </div>
      <div class="itens">
          <ul>
              <li><a href="#">Home</a></li>
              <li><a href="#">About</a></li>
              <li><a href="#">Products</a></li>
              <li><a href="#">Support</a></li>
          </ul>
      </div>
      <div class="btns">
          <img src="../assets/search.svg" alt="">
          <img src="../assets/shopping-cart.svg" alt="">
      </div>
  </header>
</template>

<script>
export default {

}
</script>

<style>

header{
    height: 7vh;
   display: flex;
   justify-content: space-around;
   align-items: center;
   font-family: 'Roboto',sans-serif;
}

.logo img{
    height: 50px;
}

ul{
    display: flex;
    align-items: center;
}

a{
    color: #000;
    padding: 10px;
    font-size: 1.1rem;
}

a:hover{
    color: rgb(87, 87, 87);
}

.btns img{
    padding: 10px 15px;
    cursor: pointer;
}

</style>