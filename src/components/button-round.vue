<template>
  <div class="text-center">
    <v-btn rounded color="primary" dark> {{ message }} </v-btn>
  </div>
</template>

<script>
    export default {
        name: 'ButtonRound',
        props: {
            message : String
        }

    }
</script>

<style lang="scss" scoped>

</style>