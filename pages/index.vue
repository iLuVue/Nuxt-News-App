<template>
  <div>
    <hr />
    <CategorySection 
      sectionTitle="News"
      headImg="1.jpg"
      headTitle="Article Headline"
      headLede="Excerpt from article to capture readers' attention." />
    <hr />
    <CategorySection 
      sectionTitle="Food & Drink"
      headImg="1.jpg"
      headTitle="Article Headline"
      headLede="Excerpt from article to capture readers' attention." />
    <hr />
    <CategorySection 
      sectionTitle="Entertainment & Events"
      headImg="1.jpg"
      headTitle="Article Headline"
      headLede="Excerpt from article to capture readers' attention." />
    <hr />
    <CategorySection 
      sectionTitle="Guides"
      headImg="1.jpg"
      headTitle="Article Headline"
      headLede="Excerpt from article to capture readers' attention." />
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