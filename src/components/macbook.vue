<template>
  <div>
        <h2>MacBook Air</h2>
        <p>Un salto al siguiente nivel.</p>
        <a href="">Más información</a>
      <img src="https://res.cloudinary.com/dutj1bbos/image/upload/c_scale,w_598/v1613596775/air.0_hbvlvq.jpg" alt="">
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
img {
  width: 600px;
}
div > img {
    display: flex;
    margin: 0 auto;
}
div {
  text-align: center;
  color:white;
}
h2 {
  font-size: 35px;
  margin: 0px;
  margin-top: 40px;;
}
div > p {
  font-size: 15px;
  margin: 0px;
  margin-bottom: 10px;
}
a{
  color: #06c;
}
</style>