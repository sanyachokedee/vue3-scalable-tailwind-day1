<script lang="ts" setup>
useHead({
 title: "Categories",
 meta: [
   {
     name: "description",
     content: "Categories",
   },
 ],
});
</script>



<template>
 <section class="py-10">
   <div class="container mx-auto">
     <div class="flex flex-wrap gap-5">



       <NuxtLink
         to="/categories/clean-code"
         class="flex items-center justify-center py-2 px-4 rounded text-white shadow-md hover:shadow-lg duration-200 text-2xl uppercase bg-blue-600">
         <span class="font-semibold">#CLEAN CODE</span>
       </NuxtLink>



       <NuxtLink
         to="/categories/clean-code"
         class="flex items-center justify-center py-2 px-4 rounded text-white shadow-md hover:shadow-lg duration-200 text-2xl uppercase bg-blue-600">
         <span class="font-semibold">#JAVASCRIPT</span>
       </NuxtLink>



       <NuxtLink
         to="/categories/clean-code"
         class="flex items-center justify-center py-2 px-4 rounded text-white shadow-md hover:shadow-lg duration-200 text-2xl uppercase bg-blue-600">
         <span class="font-semibold">#DEVOPS</span>
       </NuxtLink>



     </div>
   </div>
 </section>
</template>

