<template>
    <div id="template">
        <div class="buttons">
            <h1>Buttons</h1>
            <ButtonRound message="Round Button" />
        </div>
    </div>
</template>

<script>
import ButtonRound from '../components/button-round.vue';

export default {
    name: 'Template',

    components : {
        ButtonRound
    }

}
</script>

<style lang="scss" scoped>

</style>