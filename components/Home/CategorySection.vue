<template>
    <section>
    <h1>{{ sectionTitle }}</h1>
    <a>See more ></a>
        <div class="columns">
            <div class="column is-two-fifths">
                <img :src="headImg">
            </div>
                <div class="column">2</div>
                <div class="column">3</div>
                <div class="column">4</div>
        </div>
    </section>
</template>

<script>
    export default {
        props: ['sectionTitle', 'headImg', 'headTitle', 'headExcerpt']
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

.column {
  background-color: lightpink;
  border-radius: 5px;
}

</style>