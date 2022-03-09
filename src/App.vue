<template>

  <MyNavbar/>
  <router-view/>
  <MyFooter/>
  <ScroolTop/>
</template>

<script>
    import MyNavbar from "@/components/includes/MyNavbar";
    import MyFooter from "@/components/includes/MyFooter";
    import ScroolTop from "@/components/includes/ScroolTop";
    export default {
      name: 'App',
      components: {MyNavbar,MyFooter,ScroolTop}
    }
</script>

<style scoped>

</style>
