<template>
    <div>
        <router-link :to="{name: 'add'}">添加</router-link>
    </div>
</template>
<script>
export default {
    name:"User",
    methods : {
        adds () {
            this.$router.push('/add')
        }
    }
}
</script>
<style scoped>

</style>