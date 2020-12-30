<template>
    <b-navbar centered fixed-top>
        <template slot="start">
            <b-navbar-item v-for="item in navbars" :key="item.title" :href="item.target">
                {{item.title}}
            </b-navbar-item>
        </template>
    </b-navbar>
</template>

<script>
    export default {
        data(){
            return{
                navbars : [
                    {title:"News", target:"/"},
                    {title:"Food & Drink", target:"/"},
                    {title:"Events & Entertainment", target:"/"},
                    {title:"Guides", target:"/"},
                ]
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>