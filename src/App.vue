<template>
 <div>
    <basic-header></basic-header>
    <main-header></main-header>
    <router-view></router-view>
    <features></features>
    <feetback></feetback>
    <pagination></pagination>
    <basic-footer></basic-footer>
    
</div>
</template>
<script>
import BasicHeader from './components/BasicHeader.vue';
import MainHeader from './components/MainHeader.vue';
import BasicFooter from './components/BasicFooter.vue';
import Features from './components/Features.vue';
import Feetback from './components/Feetback.vue';
import Pagination from './components/Pagination.vue';

export default {
  components:{BasicHeader, MainHeader, BasicFooter,Features,Feetback,Pagination},

}
</script>
<style lang="scss">

</style>
