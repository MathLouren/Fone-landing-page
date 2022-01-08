<template>
  <main>
      <div class="img_left">
          <img src="../assets/fone.png" alt="">
      </div>
      <div class="container_right">

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
    width: 1400px;
}

.img_left{
    width: 50%;
    height: 87vh;
    display: flex;
    align-items: center;
    justify-content: center;
}

img{
    height: 600px;
}

.container_right{
    width: 50%;
    display: flex;
    justify-content: right;
}

</style>