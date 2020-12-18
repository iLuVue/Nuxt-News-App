<template>
    <section>
    <div class="title-container">
        <h1>{{ sectionTitle }}</h1>
        <a>See more ></a>
    </div>
        <div class="columns">
            <div class="column is-two-fifths">
                <img :src="require(`~/assets${headImg}`)" />
                    <article>
                        <h2>{{ headTitle }}</h2>
                        <p>{{ headLede }}</p>
                    </article>
            </div>
                <div class="column">
                    <img :src="require(`~/assets${secondImg}`)" />
                    <article>
                        <h2>{{ secondTitle }}</h2>
                        <p>{{ secondLede }}</p>
                    </article>
                </div>
                <div class="column">
                    <img :src="require(`~/assets${thirdImg}`)" />
                    <article>
                        <h2>{{ thirdTitle }}</h2>
                        <p>{{ thirdLede }}</p>
                    </article>
                </div>
                <div class="column">
                    <img :src="require(`~/assets${fourthImg}`)" />
                    <article>
                        <h2>{{ fourthTitle }}</h2>
                        <p>{{ fourthLede }}</p>
                    </article>
                </div>
        </div>
    </section>
</template>

<script>
    export default {
        props: ['sectionTitle', 'headImg', 'headTitle', 'headLede', 'secondImg', 'secondTitle', 
        'secondLede', 'thirdImg', 'thirdTitle', 'thirdLede', 'fourthImg', 'fourthTitle', 'fourthLede']
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
    font-family: 'Roboto';
    font-size: 35px;
    font-weight: 500;
}

h2 {
    font-family: 'Roboto';
    font-size: 20px;
}

p {
    font-family: 'Roboto';
    font-size: 15px;
}

a {
    font-size: 0.75rem;
    font-family: 'Roboto';
    font-size: 15px;
}

img {
    width: 100%;
}

</style>
