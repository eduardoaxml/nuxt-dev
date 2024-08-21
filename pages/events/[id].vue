<script setup>
    const route = useRoute();
    const id = route.params.id;
</script>
<template>
    <div>
        event uid : {{ id }}
    </div>
</template>