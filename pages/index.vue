<template>
  <div>
    <hr />
    <CategorySection 
      sectionTitle="News"
      headImg="" />
    <hr />
      <CategorySection 
      sectionTitle="Food & Drink" />
    <hr />
      <CategorySection 
      sectionTitle="Events" />
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