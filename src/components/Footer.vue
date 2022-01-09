<template>
  <footer>
      <div class="container">
          <div class="container_itens">
              <img src="../assets/speaker.svg" alt="">
          <div class="text">
              High-Resolution Audio Compatible
          </div>
          </div>
          <div class="container_itens">
              <img src="../assets/bluetooth.svg" alt="">
          <div class="text">
              High-Resolution Audio Compatible
          </div>
          </div>
          <div class="container_itens">
              <img src="../assets/battery-charging.svg" alt="">
          <div class="text">
              A powerful battery that lasts up to 4 hours of use
          </div>
          </div>
      </div>
  </footer>
</template>

<script>
export default {

}
</script>

<style scoped>

footer{
    margin: auto;
    width: 100%;
    background-color: rgb(221, 210, 170);
}

.container{
    max-width: 1400px;
    height: 7vh;
    margin: auto;
    display: flex;
    justify-content: center;
    align-items: center;
}
.container_itens{
    display: flex;
    justify-content: center;
    align-items: center;
}

.text{
    margin-left: 20px;
    max-width: 200px;
}

@media(max-width:800px){
    footer{
        margin-top: 50px;
        background: none;
    }
    .container{
        flex-direction: column;
    }

    .container_itens{
        width: 100%;
        padding: 15px 0;
        background-color: rgb(211, 202, 165);
    }
}

</style>