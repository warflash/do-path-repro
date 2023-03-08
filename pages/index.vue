<template>
    <div>
        <img src="/logo.svg" />
        <div>
            <span>
                Hello World
            </span>
            <NuxtLink to="/nested">-> Nested</NuxtLink>
            <span>
                API: {{ apiData.data }}
            </span>
        </div>
    </div>
</template>

<script setup lang="ts">
const route = useRoute()

const apiData = useFetch("/api/hello", {
    server: false,
});

</script>

<style lang="scss" scoped>

</style>