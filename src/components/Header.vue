<template>
    <header class="container">
        <h1 class="text-center py-5">{{title}}</h1>

    </header>
</template>

<script>
export default {
    name: "Header",
    props: ['title']
}  


</script>

<style lang="scss" scoped>
    h1{
        font-weight: bold;
    }
</style>