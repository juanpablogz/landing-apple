<template>
  <div>
    <section class="container">
        <div class="item">
          <navigation/>
        </div>
        <div class="item">
            <hero/>
        </div>
        <div class="item">
            <amazing />
        </div>
        <div class="item">
            <ipad />
        </div>
        <div class="item">
            <macbook/>
        </div>
        <div class="item">
            <watch />
        </div>
        <div class="item">
            <watch2 />
        </div>
        <div class="item">
            <services />
        </div>
        <div class="item">
            <footer />
        </div>
    </section>
  </div>
</template>

<script>
import navigation from './navigation.vue'
import hero from './hero.vue'
import amazing from './amazing.vue'
import ipad from './ipad.vue'
import macbook from './macbook.vue'
import watch from './watch.vue'
import watch2 from './watch2.vue'
import services from './services.vue'
import footer from './footer.vue'
export default {
  name: 'HelloWorld',
    components: {
    navigation,
    hero,
    amazing,
    ipad,
    macbook,
    watch,
    watch2,
    services,
    footer
  },
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    body {
        font-family: Arial, Helvetica, sans-serif;
    }
    .container {
        display: grid;
        /* grid-template-columns: repeat(4, 1fr);
        grid-template-rows: repeat(66, 1fr); */
        gap: 10px 10px;
        height: 100%;
    }
    .item {
        /* background: lightblue; */
        /* padding: 10px; */
        /* border: 1px solid red; */
    }
    .item .item {
        /* background: turquoise; */
    }
    .item:nth-of-type(1) {
        /* background:blue; */
        grid-column-start: 1;
        grid-column-end: 5;
        position: fixed;
        width: 100%;
    }
    .item:nth-of-type(2) {
        background:rgb(245,245,247);
        grid-column-start: 1;
        grid-column-end: 5;
        grid-row-end: span 11;
    }
    .item:nth-of-type(3) {
        background:rgb(0,0,0);
        grid-column-start: 1;
        grid-column-end: 5;
        grid-row-end: span 11;
    }
    .item:nth-of-type(4) {
        background: #F6F7F9;
        grid-column-start: 1;
        grid-column-end: 5;
        grid-row-end: span 11;
    }
    .item:nth-of-type(5) {
        background:rgb(0,0,0);
        grid-column-start: 1;
        grid-column-end: 3;
        grid-row-end: span 11;
        box-sizing: border-box;
    }
    .item:nth-of-type(6) {
        background:rgb(0,0,0);
        grid-column-start: 3;
        grid-column-end: 5;
        grid-row-end: span 11;
    }

    .item:nth-of-type(7) {
        background:rgb(250,250,250);
        grid-column-start: 1;
        grid-column-end: 3;
        grid-row-end: span 11;
    }
    .item:nth-of-type(8) {
        background:rgb(250,250,250);
        grid-column-start: 3;
        grid-column-end: 5;
        grid-row-end: span 11;
    }
    .item:nth-of-type(9) {
        background:#FAFAFA;
        grid-column-start: 1;
        grid-column-end: 5;
        grid-row-end: span 11;
    }
</style>
