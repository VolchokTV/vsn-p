<template>
    <div>
        <header class="shadow-sm bg-white">           
        <nav  class="container mx-auto p-4">
            <NuxtLink to="/arts/1"  class="font-bold"> Мои Арты </NuxtLink>
        </nav>
        </header>
    <div  class="container mx-auto p-4" >
        <slot />
    </div>
    
    <footer> 
        <ul class="flex gap-4">
                <li>  <NuxtLink to="/"> Home </NuxtLink> </li>
                <li>  <NuxtLink to="/about"> About </NuxtLink> </li>
                <li>  <NuxtLink to="/arts" class = "btn"> Arts </NuxtLink> </li>
        </ul>
        (c) 2025 ВСН 
    </footer>
       
    </div>

</template>

<script setup lang="ts">

</script>

<style scoped>

</style>