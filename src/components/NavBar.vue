<template>
  <nav class="bg-transparent">
    <div class="max-w-full flex items-center justify-between p-6 mx-auto text-gray-600 capitalize dark:text-gray-300">
        <div >
            <img src="@/assets/images/NewLogo.png" alt="Logo" class="w-30 h-30">
        </div>
        <div>
            <a href="#" class="text-gray-800 transition-colors duration-300 transform dark:text-gray-200 border-b-2 border-blue-500 mx-1.5 sm:mx-6">Home</a>
            <a href="#" class="border-b-2 border-transparent hover:text-gray-800 transition-colors duration-300 transform dark:hover:text-gray-200 hover:border-blue-500 mx-1.5 sm:mx-6">Features</a>
            <a href="#" class="border-b-2 border-transparent hover:text-gray-800 transition-colors duration-300 transform dark:hover:text-gray-200 hover:border-blue-500 mx-1.5 sm:mx-6">How It Works</a>
            <a href="#" class="border-b-2 border-transparent hover:text-gray-800 transition-colors duration-300 transform dark:hover:text-gray-200 hover:border-blue-500 mx-1.5 sm:mx-6">About</a>
            <a href="#" class="border-b-2 border-transparent hover:text-gray-800 transition-colors duration-300 transform dark:hover:text-gray-200 hover:border-blue-500 mx-1.5 sm:mx-6">Contact Us</a>
        </div>
    </div>
</nav>
</template>

<script>    
export default {
    name: 'NavBar',
    components: {
    }
}
</script>
<style>

</style>