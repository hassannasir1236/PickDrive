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
                <div class="h-[300px] w-[600px]">
                    <h1 class="text-3xl font-bold text-gray-800">Book a City Taxi to your Destination</h1>
                    <p class="font-sans text-sm font-normal	my-4 leading-normal text-[#007D65]">Choose from a range of categories and prices</p>
                    
                    <div class="flex flex-row items-center justify-around top-32">
                        <a href="#" class="">
                            <img src="@/assets/images/PlayStore.png" alt="Responsive Image" class="">
                        </a>
                        <a href="#" class="">
                            <img src="@/assets/images/AppStore.png" alt="Responsive Image" class="">
                        </a>
                    </div>
                    
                </div>
                <!-- image section -->
                <div>
                    <img src="@/assets/images/MainSectionMobile.png" alt="Responsive Image" class="max-w-full  h-auto">
                </div>
            </div>
        </div>
    </div>
    <section class="absolute top-0 bottom-0 right-0 left-0 w-full h-full bg-[#DEEEEB] z-0 transform skew-y-[349deg] origin-top-left skewed">
        <img src="@/assets/images/MainbottomLogo.png" alt="Responsive Image" class="absolute w-24 h-24 top-[90%] bottom-[39px] left-[50px] rounded-[4px]">
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
  transform: skewY(349deg);
  transform-origin: top left;
}
</style>