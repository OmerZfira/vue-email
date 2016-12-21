<template>
    <div class="header">
        <h3>app header</h3>
        <button class="btn btn-success glyphicon glyphicon-pencil" @click="">&nbsp;<span>Compose</span></button>
    </div>
</template>

<script>
    export default {
        data() {
            return {
            }
        },

    }
</script>

<style scoped>
.header {
    border-radius: 15px 15px 0 0;
    background: #34495D;
    padding: 5px;
    display: flex;
    justify-content: space-between;
}

.btn-success {
    height: 35px;
    align-self: flex-end;
}
</style>