<template>
    <div id="template">
      <v-container>
        <div class="buttons">
            <h1>Buttons</h1>
            <ButtonRound message="Round Button" />
        </div>
      </v-container>
  
        <div>
            <v-container>
            <h1> Card Task</h1>
                <CardTask  
                    heading="New Task"
                    description="Short description About task"
                    priority="Priority Here To Be Assigned"
                />
            </v-container>
        </div>
    </div>
</template>

<script>
import ButtonRound from '../components/button-round.vue';
import CardTask from '../components/card-task.vue';

export default {
    name: 'Template',

    components : {
        ButtonRound,
        CardTask
    }

}
</script>

<style lang="scss" scoped>

</style>