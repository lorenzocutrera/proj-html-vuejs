<script>
import appHeader from './components/appHeader.vue';
import appMain from './components/appMain.vue';

export default{
  components:{
    appHeader,
    appMain
  }
}

</script>

<template>
  <appHeader></appHeader>

  <appMain></appMain>

  <appFooter></appFooter>
</template>

<style lang="scss" scoped>

</style>
