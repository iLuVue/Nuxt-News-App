<template>
  <div>
    <hr />
    <CategorySection 
      sectionTitle="News"
      headImg="/images/News/1.jpg"
      headTitle="Article Headline"
      headLede="Excerpt from article to capture readers' attention." 
      secondImg="/images/News/2.jpg"
      secondTitle="Apple"
      secondLede="Pear" 
      thirdImg="/images/News/3.jpg"
      thirdTitle="Apple"
      thirdLede="Pear" 
      fourthImg="/images/News/4.jpg"
      fourthTitle="Apple"
      fourthLede="Pear" />
    <h2>Latest</h2>
    <carousel>
      <slide>
        <img src="~/assets/images/slider/6.gif" class="slider-image" />
        <article>
          <h2>A cool title</h2>
          <p>A really capturing lede.</p>
        </article>
      </slide>
      <slide>
        <img src="~/assets/images/slider/7.jpg" class="slider-image" />
        <article>
          <h2>A cool title</h2>
          <p>A really capturing lede.</p>
        </article>
      </slide>
      <slide>
        <img src="~/assets/images/slider/8.jpg" class="slider-image" />
        <article>
          <h2>A cool title</h2>
          <p>A really capturing lede.</p>
        </article>
      </slide>
      <slide>
        <img src="~/assets/images/slider/6.gif" class="slider-image" />
        <article>
          <h2>A cool title</h2>
          <p>A really capturing lede.</p>
        </article>
      </slide>
      <slide>
        <img src="~/assets/images/slider/7.jpg" class="slider-image" />
        <article>
          <h2>A cool title</h2>
          <p>A really capturing lede.</p>
        </article>
      </slide>
      <slide>
        <img src="~/assets/images/slider/8.jpg" class="slider-image" />
        <article>
          <h2>A cool title</h2>
          <p>A really capturing lede.</p>
        </article>
      </slide>
    </carousel>
    <hr />
    <CategorySection 
      sectionTitle="Food & Drink"
      headImg="/images/Food/1.jpg"
      headTitle="Article Headline"
      headLede="Excerpt from article to capture readers' attention." 
      secondImg="/images/Food/2.jpg"
      secondTitle="Apple"
      secondLede="Pear" 
      thirdImg="/images/Food/3.jpg"
      thirdTitle="Apple"
      thirdLede="Pear" 
      fourthImg="/images/Food/4.jpg"
      fourthTitle="Apple"
      fourthLede="Pear" />
    <hr />
    <CategorySection 
      sectionTitle="Entertainment & Events"
      headImg="/images/Events/1.jpg"
      headTitle="Article Headline"
      headLede="Excerpt from article to capture readers' attention." 
      secondImg="/images/Events/2.jpg"
      secondTitle="Apple"
      secondLede="Pear" 
      thirdImg="/images/Events/3.jpg"
      thirdTitle="Apple"
      thirdLede="Pear" 
      fourthImg="/images/Events/4.jpg"
      fourthTitle="Apple"
      fourthLede="Pear" />
    <hr />
    <CategorySection 
      sectionTitle="Guides"
      headImg="/images/Guides/1.jpg"
      headTitle="Article Headline"
      headLede="Excerpt from article to capture readers' attention." 
      secondImg="/images/Guides/2.jpg"
      secondTitle="Apple"
      secondLede="Pear" 
      thirdImg="/images/Guides/3.jpg"
      thirdTitle="Apple"
      thirdLede="Pear" 
      fourthImg="/images/Guides/4.jpg"
      fourthTitle="Apple"
      fourthLede="Pear" />
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

h2 {
  text-align: center;
}

// .slider-image {
//     overflow: hidden;
//     max-height: 200px;
// }

</style>
