<template>
    <section class="w-full bg-[#000000] p-6">
        <div class="grid grid-cols-5 md:grid-cols-5 gap-6 items-start text-left font-['Roboto'] font-medium text-[15px] leading-[17.58px] text-gray-800">
            <!-- Left Side Content -->
            <div class="ml-8 col-span-2">
                <img 
                class="w-40 mt-5 p-2 bg-white rounded-lg" 
                src="@/assets/images/NewLogo.png" 
                alt="Sunset in the mountains" 
                />
                <p class="mt-5 text-white">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
                Nullam id fermentum lorem. Lorem ipsum dolor sit amet, 
                consectetur adipiscing elit. Nullam id fermentum lorem.
                </p>
                <img 
                class="w-40 mt-5" 
                src="@/assets/images/FooterImage.png" 
                alt="Footer Image" 
                />
            </div>
            <div class="col-span-3 flex justify-around align-center my-20">
                <!-- Second Section -->
                <ul class="list-none space-y-2">
                    <li><a href="#" class="text-white hover:text-gray-500 transition">Home</a></li>
                    <li><a href="#" class="text-white hover:text-gray-500 transition">Features</a></li>
                    <li><a href="#" class="text-white hover:text-gray-500 transition">How it works</a></li>
                    <li><a href="#" class="text-white hover:text-gray-500 transition">Tariffs</a></li>
                </ul>

                <!-- Third Section -->
                <ul class="list-none space-y-2">
                    <li><a href="#" class="text-white hover:text-gray-500 transition">About</a></li>
                    <li><a href="#" class="text-white hover:text-gray-500 transition">Cities</a></li>
                    <li><a href="#" class="text-white hover:text-gray-500 transition">Contact us</a></li>
                </ul>

                <!-- Fourth Section -->
                <ul class="list-none space-y-2">
                    <li><a href="#" class="text-white hover:text-gray-500 transition">Become a driver</a></li>
                    <li><a href="#" class="text-white hover:text-gray-500 transition">Terms and Conditions</a></li>
                    <li><a href="#" class="text-white hover:text-gray-500 transition">Privacy Policy</a></li>
                </ul>

                <!-- Fifth Section -->
                <ul class="list-none space-y-2">
                    <li><a href="mailto:info@abc.com" class="text-white hover:text-gray-500 transition">info@abc.com</a></li>
                    <li><a href="tel:+923166717394" class="text-white hover:text-gray-500 transition">+92 3166717394</a></li>
                </ul>
            </div>
        </div>
    </section>
    <!-- copyright tag add -->
    <section class="w-full bg-[#323232] p-2">
        <p class="text-center text-white font-sans pb-2 text-xs bg-shadow-2xl">© 2021 All rights reserved</p>
    </section>
</template>
<script>
export default {
    name: 'FooterPage',
    components: {
    }
}
</script>
<style scoped>
.bg-shadow-2xl {
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.5);
}
</style>