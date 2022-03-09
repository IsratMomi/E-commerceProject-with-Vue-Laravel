<template>
  <div class="home">
    <HeroArea/>
    <FeaturedCategory/>
    <TrendingProduct/>
    <BannerArea/>
    <SpecialOffer/>
    <HomeProductList/>
    <PopularBrand/>
    <LatestNews/>
    <ShippingInfo/>

  </div>
</template>

<script>
  import HeroArea from "@/components/home/HeroArea";
  import FeaturedCategory from "@/components/home/FeaturedCategory";
  import TrendingProduct from "@/components/home/TrendingProduct";
  import BannerArea from "@/components/home/BannerArea";
  import SpecialOffer from "@/components/home/SpecialOffer";
  import HomeProductList from "@/components/home/HomeProductList";
  import PopularBrand from "@/components/home/PopularBrand";
  import LatestNews from "@/components/home/LatestNews";
  import ShippingInfo from "@/components/home/ShippingInfo";
  export default {
    name: 'HomeView',
    components: {HeroArea,FeaturedCategory,TrendingProduct,BannerArea,SpecialOffer,HomeProductList,PopularBrand,LatestNews,ShippingInfo},


  }
</script>
