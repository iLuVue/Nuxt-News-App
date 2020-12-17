<template>
    <section>
    <h1>{{ sectionTitle }}</h1>
    <a>See more ></a>
        <div class="columns">
            <div class="column is-two-fifths">
                <img :src="headImg" />
                    <article>
                        <h2>{{ headTitle }}</h2>
                        <p>{{ headLede }}</p>
                    </article>
            </div>
                <div class="column">
                    <img :src="require('assets/1.jpg')">
                    <article>
                        <h2>{{ headTitle }}</h2>
                        <p>{{ headLede }}</p>
                    </article>
                </div>
                <div class="column">
                    <img :src="require('assets/1.jpg')">
                    <article>
                        <h2>{{ headTitle }}</h2>
                        <p>{{ headLede }}</p>
                    </article>
                </div>
                <div class="column">
                    <img :src="require('assets/1.jpg')">
                    <article>
                        <h2>{{ headTitle }}</h2>
                        <p>{{ headLede }}</p>
                    </article>
                </div>
        </div>
    </section>
</template>

<script>
    export default {
        props: ['sectionTitle', 'headImg', 'headTitle', 'headLede']
    }
</script>

<style lang="scss" scoped>

h1 {
    display: inline-block;
    padding-bottom: 20px
}

a {
    display: inline-block;
    float: right;
}

img {
    width: 100%;
}

</style>