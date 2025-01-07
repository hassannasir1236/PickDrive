<template>
    <div class="relative w-full h-96">
        <!-- Full-Size Background Image -->
        <img 
        src="@/assets/images/endsectioniamge.png" 
        alt="Background" 
        class="absolute inset-0 w-full h-96 object-cover"
        />

        <!-- Overlay Layer -->
        <div class="absolute inset-0 bg-black bg-opacity-20"></div>

        <!-- Content on Top -->
        <div class="relative flex flex-col items-center justify-center h-96 text-white px-4">
            <h1 class="text-4xl md:text-2xl font-bold mb-4">What are you waiting for?</h1>
            <p class="text-xs md:text-xs text-center mb-6">
                Join hundreds of thousands of happy users.
            </p>
            <div class="flex flex-row items-center justify-around top-32">
                <a href="#" class="">
                    <img src="@/assets/images/PlayStore.png" alt="Responsive Image" class="w-[100px] h-[100px] object-contain">
                </a>
                <a href="#" class="">
                    <img src="@/assets/images/AppStore.png" alt="Responsive Image" class="w-[100px] h-[100px] object-contain ml-4">
                </a>
            </div>
        </div>
    </div>
</template>
<script>   
export default {
    name: 'EndSectionpage',
    components: {
    }
}
</script>