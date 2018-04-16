<template>
    <Dashboard></Dashboard>
</template>

<script>
    import Dashboard from './Dashboard'
    export default {
        mounted() {
            console.log('Component mounted.')
        },
        components: {
            Dashboard
        }
    }
</script>
