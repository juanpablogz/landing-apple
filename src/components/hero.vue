<template>
  <main>
    <div class="container">
      <h1>iPhone 12</h1>
      <p>Súper.Mega.Rápido.</p>
      <a href="">Más información ></a>
    </div>
    <div>
      <img class="desktop" src="https://res.cloudinary.com/dutj1bbos/image/upload/v1613595027/iphone-12-o-iphone-11_1_fjbasi.png" alt="">
      <img class="mobile" src="https://res.cloudinary.com/dutj1bbos/image/upload/v1614040650/85608ed4-5f31-4cc7-ad97-91f33001b695_alta-libre-aspect-ratio_default_0_xxxkhu.jpg" alt="">
    </div>
  </main>
</template>

<script>
export default {

}
</script>

<style scoped>
p, h1 {
  margin: 0;
}
p, h1 {
  margin-bottom: 10px
}
h1 {
  font-size: 45px;
}
p {
  font-size: 25px;
}
.container {
  text-align: center;
  color: black;
  font-size: 25px;
  margin-top: 130px;

}
.desktop {
  width: 700px;
}
a{
  color: #06c;
}
@media (max-width: 600px) {
  main {
    height: 1250px;
  }
  h1 {
    font-size: 100px;
  }
  p {
    font-size: 60px;
  }
  a {
    font-size: 60px;
    margin-bottom: 10px;
  }
  .mobile {
    width: 1000px;
  }
  .desktop {
    display: none;
  }
}
@media (min-width: 600px) {
  .mobile {
    display: none
  }
}
</style>
