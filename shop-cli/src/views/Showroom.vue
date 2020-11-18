<template>
    <div class="showroom">
      <header>
        <div class="logo"><a href="http://localhost:3000/src/static/index.html">E-shop</a></div>
        <div id="nav">
            <router-link to="/">Home</router-link>
            <router-link to="/about">About</router-link>
            <router-link to="/showroom">Showroom</router-link>
            <router-link to="/contact">Contact</router-link>
        </div>
        <!-- <div class="totalSum">Суммарная стоимость товаров:&nbsp;{{ }}</div> -->
        <div class="cart">
            
            <filterest />
            <button class="btn-cart" type="button" @click="isVisibleCart = !isVisibleCart">Корзина</button>
            <basket ref="basket" v-show="isVisibleCart" />
            <!-- Basket -->
        </div>
      </header>
      <goodsitem />
  </div>
</template>

<script>
// import catalog from '../components/Catalog.vue'
import basket from '../components/Basket.vue'
import filterest from '../components/Filter.vue'
import goodsitem from '../components/GoodsItem.vue'
export default {
  data() {
    return {
      isVisibleCart: false
    }
  },
  methods: {
    getData(url) {
        return fetch(url)
            .then(d => d.json())
    },
  },
  components: { basket, filterest, goodsitem }
}
</script>