<template>
  <main>
      <div class="img_left">
          <img src="../assets/fone.png" alt="">
      </div>
      <div class="container_right">
          <h1>HYPER X ON-EAR</h1>
          <p class="desc">Wireless over-ear headphones</p>
          <div class="avaliacao"></div>
          <span>Driver unit</span>
          <p>70mm, dome type (CCAW Voice Col)</p>
          <span>Driver unit</span>
          <p>4 Hz + 100.000 Hz</p>
          <div class="buy">
          <span class="price">$89.99</span>
          <button class="add_cart">ADD TO CART</button>
      </div>
      </div>
  </main>
</template>

<script>
export default {

}
</script>

<style scoped>

main{
    margin: auto;
    max-width: 1400px;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    padding: 50px 0;
}

.img_left{
    width: 700px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
}

img{
    max-height: 500px;
    margin: 0 10px;
}

.container_right{
    margin: 50px 10px 0 10px;
    margin-top: 50px;
    width: 520px;
    display: flex;
    justify-content: center;
    flex-direction: column;
    flex-wrap: wrap;
    margin: 40px 20px 10px0 20px;
}

.container_right h1{
    font-size: 3rem;
    color: rgb(204, 4, 4);
    letter-spacing: 0.1rem;
    margin-bottom: 20px;
}

.container_right .desc{
    font-weight: bold;
    font-size: 1.3rem;
    letter-spacing: 0.06rem;
    margin: 10px 0;
    color: rgb(48, 48, 48);
}

.container_right span{
    font-size: 1.2rem;
    font-weight: bold;
    letter-spacing: 0.08rem;
    margin-top: 10px;
}

.container_right p{
    letter-spacing: 0.08rem;
    color: rgb(121, 121, 121);
}

.buy{
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
    margin-top: 15px;
}

.buy .price{
    font-size: 2rem;
    font-weight: bold;
}

.buy .add_cart{
    padding: 15px 40px;
    background-color: crimson;
    color: #fff;
    border: none;
    font-size: 0.9rem;
    cursor: pointer;
    letter-spacing: 0.1rem;
    transition: 0.6s;
    margin-right: 10px;
}

.buy .add_cart:hover{
    background-color: rgb(255, 0, 51);
}

</style>