<template>
<h1 class="font-sans text-lg md:text-2xl lg:text-3xl font-extrabold md:mt-4 xs-m-46 sm:mt-4 mb-4 text-center text-gray-800">
  How It Works
</h1>
<!-- first section -->
<section class="grid grid-cols-1 md:grid-cols-2 gap-6 items-center p-6">
  <!-- Left Side Content -->
  <div class="text-left ml-8">
    <h1 class="text-xl md:text-base font-bold mb-4">Save on ride</h1>
    <p class="text-base md:text-lg text-gray-600 mb-6">
        With inDriver, you can book rides way cheaper! 
        Say no to compulsory rates and high-demand 
        manipulations.
    </p>
  </div>

  <!-- Right Side Image -->
  <div class="text-center md:text-right flex justify-center">
    <img
     src="@/assets/images/HowItsWorksMobile.png"
      alt="Save on ride"
      class="w-full md:w-3/4 lg:w-2/3 object-cover rounded-lg"
    />
  </div>
</section>

<!-- Second section -->
<section class="grid grid-cols-1 md:grid-cols-2 gap-6 items-center p-6">
   <!-- Left Side Image -->
   <div class="text-center md:text-right flex justify-center">
    <img
     src="@/assets/images/ItsWorkSecondImage.png"
      alt="Save on ride"
      class="w-full md:w-3/4 lg:w-2/3 object-cover rounded-lg"
    />
  </div>
    <!-- Right Side Content -->
  <div class="text-left ml-8">
    <h1 class="text-xl md:text-base font-bold mb-4">Offer your own price</h1>
    <p class="text-base md:text-lg text-gray-600 mb-6">
        With inDriver, you can book rides way cheaper! 
        Say no to compulsory rates and high-demand 
        manipulations.
    </p>
  </div>
</section>

<!-- Third section -->
<section class="grid grid-cols-1 md:grid-cols-2 gap-6 items-center p-6">
  <!-- Left Side Content -->
  <div class="text-left ml-8">
    <h1 class="text-xl md:text-base font-bold mb-4">Select the best driver</h1>
    <p class="text-base md:text-lg text-gray-600 mb-6">
        With inDriver, you can book rides way cheaper! 
        Say no to compulsory rates and high-demand 
        manipulations.
    </p>
  </div>

  <!-- Right Side Image -->
  <div class="text-center md:text-right flex justify-center">
    <img
     src="@/assets/images/ItsWorkThirdImage.png"
      alt="Save on ride"
      class="w-full md:w-3/4 lg:w-2/3 object-cover rounded-lg"
    />
  </div>
</section>

<!-- Fourth section -->
<section class="grid grid-cols-1 md:grid-cols-2 gap-6 items-center p-6">
   <!-- Left Side Image -->
   <div class="text-center md:text-right flex justify-center">
    <img
     src="@/assets/images/ItsWorkFourthImage.png"
      alt="Save on ride"
      class="w-full md:w-3/4 lg:w-2/3 object-cover rounded-lg"
    />
  </div>
    <!-- Right Side Content -->
  <div class="text-left ml-8">
    <h1 class="text-xl md:text-base font-bold mb-4">Average vehicle arrive time : 5
        min</h1>
    <p class="text-base md:text-lg text-gray-600 mb-6">
        With inDriver, you can book rides way cheaper! 
        Say no to compulsory rates and high-demand 
        manipulations.
    </p>
  </div>
</section>

</template>
<script>
export  default {
    name: 'ItsWork',
    components: {
    }
}
</script>
<style scoped>
@media (min-width: 280px) {
  .xs-m-46 {
   margin-top: 200px;
  }
}

</style>