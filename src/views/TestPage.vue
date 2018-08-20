<template>
    <div class="test" @click="showMessage">
        test
    </div>
</template>
<script>
export default {
    data: function () {
        return {
            mes: 123
        }
    },
    methods: {
        showMessage: function (mes) {
            if (mes == null)
                mes = this.mes
            alert(mes)
        }
    }
}
</script>
<style lang="less">

</style>