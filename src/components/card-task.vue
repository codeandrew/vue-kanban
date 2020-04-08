<template>
  <div>
    <v-card
     color="#385F73"
     dark >
      <v-card-title class="headline">Unlimited music now</v-card-title>

      <v-card-subtitle>Listen to your favorite artists and albums whenever and wherever, online and offline.</v-card-subtitle>

      <v-card-actions>
        <v-btn text>Listen Now</v-btn>
      </v-card-actions>
    </v-card>
  </div>
</template>

<script>
    export default {
        name: 'CardTask',
        props: {
            message : String
        }

    }
</script>

<style lang="scss" scoped>

</style>