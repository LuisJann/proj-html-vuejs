<script>
import AppHeader from './components/AppHeader.vue';
import AppBanner from './components/AppBanner.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default{
  components:{
    AppHeader,
    AppBanner,
    AppMain,
    AppFooter
  },
  data(){
    return{

    }
  }
}

</script>


<template>
<AppHeader />
<AppBanner />
<AppMain />
</template>

<style lang="scss">
@use "./styles/general.scss"as*;

</style>
