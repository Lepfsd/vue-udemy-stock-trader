<template>
    <div>
        <h1>trade or view your portfolio</h1>
        <h6>you may save & load your data</h6>
        <h6> click on 'end day' to begin a new day!</h6>
        <hr>
        <p>your funds: {{funds | currency }} </p>
    </div>
</template>

<script>
export default {
    computed: {
        funds(){
            return this.$store.getters.funds;
        }
    }
}
</script>

