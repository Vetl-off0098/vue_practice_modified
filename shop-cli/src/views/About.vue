<template>
  <div class="about">
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
    <homepage />
  </div>
</template>

<script>
// import catalog from '../components/Catalog.vue'
import basket from '../components/Basket.vue'
import filterest from '../components/Filter.vue'
import homepage from '../components/HomePage.vue'
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
  components: { basket, filterest, homepage }
}
</script>

<style>
  .owl-theme .owl-nav.disabled + .owl-dots {
    position: absolute;
    bottom: 19px;
    left: 45.8%;
  }
  .owl-theme .owl-dots .owl-dot span{
    display: inline-block;
    width: 30px;
    height: 30px;
    background-color: #c7c7c7;
    border-radius: 50%;
    margin: 5px;
  }
  .owl-dot:hover {
    background-color: #212121;
  }
  .owl-theme .owl-dots .owl-dot.active span {
    width: 40px;
    height: 40px;
    background-color: #212121;
    border-radius: 50%;
    margin-bottom: 0px;
  }
</style>