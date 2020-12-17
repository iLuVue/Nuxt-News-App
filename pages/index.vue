<template>
  <div>
    <hr />
    <CategorySection 
      sectionTitle="News"
      headImg="@/assets/1.jpg"
      headTitle="Article Headline"
      headLede="Excerpt from article to capture readers' attention." />
    <hr />
      <CategorySection 
      sectionTitle="Food & Drink" />
    <hr />
      <CategorySection 
      sectionTitle="Events & Entertainment" />
    <hr />
      <CategorySection 
      sectionTitle="Guides" />
    <hr />
  </div>
</template>

<script>
  import TheNav from '@/components/TheNav'
  import CategorySection from '@/components/Home/CategorySection'

  export default {
    components: {
      CategorySection
    }
  }
</script>

<style lang="scss" scoped>

</style>