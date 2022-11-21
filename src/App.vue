<script>
import AppHeader from './components/AppHeader.vue';
import AppBanner from './components/AppBanner.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
import AppTestimonial from './components/AppTestimonial.vue';

export default{
  components:{
    AppHeader,
    AppBanner,
    AppMain,
    AppFooter,
    AppTestimonial
  },
  
}

</script>


<template>
<AppHeader />
<AppBanner />
<AppMain />
<AppTestimonial />
<AppFooter />
</template>

<style lang="scss">
@use "./styles/general.scss"as*;

</style>
