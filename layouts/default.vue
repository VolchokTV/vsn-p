<template>
    <div>
        <header class="shadow-sm bg-white">
       <nav class="container mx-auto p-4 flex justify-between"> 
            <NuxtLink to="/" class="font-bold"> В.С.Н. </NuxtLink>
        
            <ul class="flex gap-4">
                <li>  <NuxtLink to="/"> Home </NuxtLink> </li>
                <li>  <NuxtLink to="/about"> About </NuxtLink> </li>
                <li>  <NuxtLink to="/arts" class="btn"> Arts </NuxtLink> </li>
            </ul>
        </nav>
        </header>
    <div  class="container mx-auto p-4">
        <slot />
    </div>
    
    <footer>
        (c) 2025 ВСН 
    </footer>

    </div>
</template>