<template>
    <div>
        <img src="/logo.svg" />
        <div>
            <span>
                Hello World
            </span>
            <NuxtLink to="/nested">-> Nested</NuxtLink>
        </div>
    </div>
</template>

<script setup lang="ts">
const route = useRoute()
</script>

<style lang="scss" scoped>

</style>