<template>
    <div>
       <p> Работа: {{ art }} </p>
    </div>
</template>

<script setup lang="ts">

definePageMeta({
  layout: 'art-layout'
})

    const { art } = useRoute().params
   
</script>

<style scoped>

    div{
        background-color: black;
        color: beige;
    }
    
</style>