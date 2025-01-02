<template>
    <div class="max-w-full mx-auto z-10 relative">
        <NavBar />
        <!-- car image -->
        <div class="">
            <div class="max-h-[180px]">
                <img src="@/assets/images/car.png" alt="Responsive Image" class="w-full max-h-[250px]">
            </div>
            
            
        <!-- main section  -->
         <div class="flex flex-row items-center justify-around">
            <div>
                <h1 class="text-4xl font-bold text-gray-800">Welcome to Car Rental</h1>
                <p class="text-gray-600">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded mt-4">Get Started</button>
                <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded mt-4">Get Started</button>
            </div>
            <!-- image section -->
             <div>
                <img src="@/assets/images/MainSectionMobile.png" alt="Responsive Image" class="max-w-full  h-auto">
             </div>
         </div>
        </div>
    </div>
    <section class="skewed">
    </section>
</template>
<script>
import NavBar from '../NavBar.vue';
export default {
    name: 'LandingPage',
    components: {
        NavBar
    }
}
</script>
<style scoped>
.skewed {
  position: absolute;
  top: 0;
  bottom: 0;
  right: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: #DEEEEB;
  z-index: 0;
  transform: skewY(344deg);
  transform-origin: top left;
}
</style>