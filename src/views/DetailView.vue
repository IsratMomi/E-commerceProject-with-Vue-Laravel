<template>
  <div class="detail-view">
    <PageTitle/>

    <section class="item-details section">
      <div class="container">
          <ProductBasicInfo/>
        <div class="product-details-info">
          <ProductDetail/>
          <ProductReview/>

        </div>
      </div>
    </section>






  </div>
</template>

<script>
  import PageTitle from "@/components/includes/PageTitle";
  import ProductBasicInfo from "@/components/productdetail/ProductBasicInfo";
  import ProductDetail from "@/components/productdetail/ProductDetail";
  import ProductReview from "@/components/productdetail/ProductReview";
  export default {
    name: "DetailView",
    components: {PageTitle,ProductBasicInfo,ProductDetail,ProductReview}
  }
</script>

<style scoped>

</style>