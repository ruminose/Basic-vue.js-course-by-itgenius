<template>
   <RouterView />
</template>

<script>
let brand = " | Vite App"

export default {
   watch:{
      $route(to) {
         document.title = to.meta.title
      }
   }
}
</script>

<style>

</style>
