<template>
    <div>
        index.vue
        {{ route.query }}
    </div>
</template>

<script setup lang="ts">
definePageMeta({
  layout: 'docs'
})
const route = useRoute()
</script>