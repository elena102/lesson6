<template>

 <ul class="product-list">
       <product></product>           
</ul>

</template>

<script>
import MainHeader from '@/components/MainHeader.vue';

import Product from '../components/Product.vue';
export default {
  components: {Product, MainHeader},
  name: 'HomeView',
}
</script>
