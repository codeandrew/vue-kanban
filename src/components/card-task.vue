<template>
  <div>
    <v-card
     color="#385F73"
     dark >
      <v-card-title class="headline"> {{ heading }} </v-card-title>

      <v-card-subtitle> {{ description }} </v-card-subtitle>
      <v-card-actions>
        <v-btn text>Button Here</v-btn>
      </v-card-actions>
    </v-card>
  </div>
</template>

<script>
    export default {
        name: 'CardTask',
        props: {
            heading : String,
            description: String,
            priority: String,
            status: String
        }

    }
</script>

<style lang="scss" scoped>

</style>