<style scoped>
    @import 'styles/common.css';
</style>
<template>
    <div>
        {{ message }}
        <router-view></router-view>
    </div>
</template>
<script>
    export default {
        data () {
            return {
                message : "hello --------------"
            }
        },
        mounted () {

        },
        beforeDestroy () {

        },
        methods: {

        }
    }
</script>
