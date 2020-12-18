<template>
    <div>
        <div class="columns">
            <div class="column is-three-fifths">
                <img :src="require(`~/assets/images/News/1.jpg`)" />
                <article>
                    <h2>Title</h2>
                    <p>Some lede goes here</p>
                </article>
            </div>
        
            <div class="column">
                <img :src="require(`~/assets/images/News/2.jpg`)" />
                <article>
                    <h2>Title</h2>
                    <p>Some lede goes here</p>
                </article>
                <img :src="require(`~/assets/images/News/2.jpg`)" />
                <article>
                    <h2>Title</h2>
                    <p>Some lede goes here</p>
                </article>
            </div>
        </div>
        <hr />
        <h1>Latest Articles</h1>
        <no-ssr placeholder="A beautiful slider will be here after client-side hydration">
            <carousel>
                <slide v-for="item in slider" v-bind:key="item.image" class="slider-gap">
                    <img :src="require(`~/assets/images/slider${item.image}`)" class="slider-image" />
                    <article>
                    <h2>{{ item.title }}</h2>
                    <p>{{ item.lede }}</p>
                    </article>
                </slide>
            </carousel>
        </no-ssr>
    </div>
</template>

<script>

    export default {
        data() {
            return {
                slider: [
                    {
                        image:"/1.jpg", 
                        title:"Here is a title", 
                        lede:"Awesome lede"
                    },
                    {
                        image:"/2.jpg", 
                        title:"Here is a title", 
                        lede:"Awesome lede"
                    },
                    {
                        image:"/3.gif", 
                        title:"Here is a title", 
                        lede:"Awesome lede"
                    },
                    {
                        image:"/4.jpg", 
                        title:"Here is a title", 
                        lede:"Awesome lede"
                    }
                ]
            }
        }

    }
</script>

<style lang="scss" scoped>

h1 {
    font-family: 'Roboto';
    font-size: 35px;
    font-weight: 500;
    text-align: center;
}

img {
    width: 100%;
}

.slider-gap {
    padding: 20px;
}

.slider-image {
    overflow: hidden;
    max-height: 330px;
}

</style>
