<template>
  <div>
     <header>
         <nav>
             <ul>
                 <li class="name">
                    <img src="https://img.icons8.com/color/26/000000/mac-os.png"/>
                 </li>
                 <li class="name">Mac</li>
                 <li class="name">iPad</li>
                 <li class="name">iPhone</li>
                 <li class="name">Watch</li>
                 <li class="name">TV</li>
                 <li class="name">Music</li>
                 <li class="name">Soporte</li>
                 <li class="name">Dónde Comprar</li>
             </ul>
         </nav>
     </header>
  </div>
</template>

<script>
export default {

}
</script>

<style soped>

header > nav > ul {
    font-size: 14px;
    color: #f5f5f7;
    background: #323233;
    display: flex;
    margin: 0 auto;
    list-style: none;
    justify-content: center;
}
.name {
    width: 100px;
    height: 50px;
    display: flex;
    align-items: center;
    font-weight: 300;
}
</style>