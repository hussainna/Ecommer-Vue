<template>
  <div>
    <Header/>
    <Hero/>
    <Baner/>
    <Type/>
    <Product/>
    <Summer/>
    <Customers/>
    <Footer/>
    <Under/>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Hero from './views/hero/Hero.vue';
import Baner from './views/banner/Baner.vue'
import Type from './views/type/Type.vue';
import Product from './views/product/Product.vue';
import Summer from './views/summer/Summer.vue';
import Customers from './views/customers/Customers.vue'
import Footer from './components/Footer.vue';
import Under from './components/Under.vue'
export default {
name:'App',

components:{
  Header,
  Hero,
  Baner,
  Type,
  Product,
  Summer,
  Customers,
  Footer,
  Under,
}

}
</script>

<style lang="scss">
  @import "./style/main.scss";
</style>