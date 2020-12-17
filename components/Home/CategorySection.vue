<template>
    <section>
    <div class="title-container">
        <h1>{{ sectionTitle }}</h1>
        <a>See more ></a>
    </div>
        <div class="columns">
            <div class="column is-two-fifths">
                <img :src="require(`~/assets/${headImg}`)" />
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

.title-container {
    display: flex;
    justify-content: center;
}

h1 {
    flex: 1;
    padding-bottom: 20px;
    justify-content: center;
    transform: translateX(5%);
    text-align: center;
    font-family: 'Roboto', Sans-Serif;
    font-size: 35px;
    font-weight: bold;
}

h2 {
    font-family: 'Roboto', Sans-Serif;
    font-size: 20px;
}

p {
    font-family: 'Droid Serif', Serif;
    font-size: 15px;
}

a {
    font-size: 0.75rem;
    font-family: 'Droid Serif', Serif;
    font-size: 15px;
}

img {
    width: 100%;
}

</style>
