<template>
    <div class="email-status">
        <!--<div class="email-status-details">-->
            <!--<strong>Read emails</strong>-->
        <!--</div>-->
        <progress-bar :barData="barData"></progress-bar>
    </div>
</template>

<script>

    import progressBar from '../utils/progress-bar.vue'

    export default {
        props: {
            barData: {
                required: true,
                type: Array
            }
        },
        components: {
            progressBar
        }
    }
</script>

<style scoped>
.email-status {
    background: #34495D;
    border: 2px lightgray outset;
    border-radius: 0 0 15px 15px;
    display:flex;
    justify-content: space-between;
    min-height: 20px;
}

/*.email-status-details {
flex: 0 1 20%;
}*/


</style>