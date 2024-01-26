<script setup lang="ts">

</script>

<template>
<div class="sectionCard">
  <div class="imgCard">
    <h3>Хит продаж</h3>
    <img alt="Vue logo" height="290" width="290" src="../assets/vue.svg"/>
    <p>В наличии</p>
  </div>
  <h4 class="category">
    Кресла театральные
  </h4>
  <h3 class="itemName">Спортивные кресла</h3>
  <h3 class="article">Артикул: 000-000</h3>
  <h4 class="price">Цена: <strong>1000</strong>руб.</h4>
</div>
</template>

<style scoped>
.sectionCard {
  width: 290px;
  height: 430px;
  margin: 18px;
  background: #4d2525;
}

.imgCard {
  position: relative;
}

.imgCard > p, h3 {
  position: absolute;
  color: #000;
}

.imgCard > h3 {
  top: 0;
  left: 0;
  margin: 12px
}

.imgCard > p {
  bottom: 0;
  right: 0;
  margin: 1rem;
}

.category {
  text-align: left;
  color: #fff;
  margin: 0;
  margin-left: 12px;
  font-size: 14px;
}

.itemName {
  text-align: left;
  font-size: 18px;
  color: aqua;
  margin: 0;
  margin-left: 12px;
}

.article {
  text-align: left;
  margin-top: 2rem;
  margin-left: 12px;
  font-size: 14px;
  color: #fff;
}

.price {
  color: aquamarine;
  text-align: left;
  margin-left: 12px;
  margin-top: 60px;
}
  .price strong {
    font-size: 24px; /* задайте желаемый размер шрифта для самой цены */
  }

img {
  background: #000;
  width: 290px;
  height: 290px;
}
</style>