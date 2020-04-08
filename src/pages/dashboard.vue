<template>
    <section id="dashboard">
        <div class="container">
            <h1>{{ title }} </h1>
        </div>
    </section>
</template>

<script>
    export default {
        name: 'Dashboard',
        props:{
            title : String
        }
    }
</script>

<style lang="scss" scoped>

</style>