<template>
  <div>
    <h2>iPhone 12 Pro</h2>
    <p>Un salto al siguiente nivel.</p>
      <a href="">Más información ></a>
      <img src="https://res.cloudinary.com/dutj1bbos/image/upload/v1613595372/Apple_announce-iphone12pro_10132020.jpg.landing-big_2x_cikbzy.jpg" alt="">
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
h2 {
  font-size: 45px;
  margin: 0px;
  margin-top: 40px;;
}
div > p {
  font-size: 25px;
  margin: 0px;
  margin-bottom: 10px;
}
div > img {
    width: 77%;
    padding-left: 165px
}
div {
  text-align: center;
  color: white;
}
a{
  color: #06c;
}
@media (max-width: 600px) {
  div {
    height: 1100px;
  }
  div > img {
      width: 100%;
      padding-left: 0px;
      margin-top: 28%;
  }
  h2 {
    font-size: 100px;
  }
  div > p {
    font-size: 50px;
  }
  a {
    font-size: 50px;
  }
}
</style>