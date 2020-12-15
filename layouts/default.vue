<template>
  <div>
    <TheNav />
    <section class="main-content">
    <Nuxt />
    </section>
    <TheFooter />
  </div>
</template>

<script>
  import TheNav from '@/components/TheNav'
  import TheFooter from '@/components/TheFooter'
  export default {
    
  }
</script>

<style lang="scss" scoped>

.main-content {
  max-width: 1200px;
  padding: 30px;
  margin: 0px auto;
}

</style>
