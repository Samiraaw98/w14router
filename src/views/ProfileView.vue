<template>
    <div>
        <h1>Welcome {{$route.params.name}}</h1>

    </div>
</template>

<script>
    export default {
        name : "ProfileView",
        data() {
            return {
                username: "Jill"
            }
        },
        methods: {
            apiCall() {
                // Fetch information based on $route.params.id
            }
        },
    }
</script>

<style lang="scss" scoped>

</style>