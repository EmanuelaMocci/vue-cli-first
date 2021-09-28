<template>
    <div>
        <h3>{{ message }}</h3>
        <img src="../assets/logo.png" alt="Hero img">
    </div>
</template>

<script>
export default {
    name: 'Hero',
    props: {
        message: String
    }
}
</script>

<style>
</style>