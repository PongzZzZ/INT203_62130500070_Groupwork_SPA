<template>
<nav class="font-sans flex flex-col text-center sm:flex-row sm:text-left sm:justify-between py-4 px-6 bg-white shadow sm:items-baseline w-full">
  <div class="mb-2 sm:mb-0">
    <a href="/" class="text-2xl no-underline text-grey-darkest hover:text-blue-dark">Home</a>
  </div>
  <div>
    <a href="/About" class="text-lg no-underline text-grey-darkest hover:text-blue-dark ml-2">About</a>
  </div>
  
</nav>
</template>

<script>
export default {
  name: 'NavBar',
  props: {
    
  }
}
</script>
