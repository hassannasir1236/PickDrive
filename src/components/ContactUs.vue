<template>  
    <h1 class="font-sans text-lg md:text-2xl lg:text-3xl font-extrabold md:mt-4 xs-m-46 sm:mt-4 mb-4 text-center text-gray-800">
        Contact Us
    </h1>  
    <section class="grid grid-cols-1 md:grid-cols-2 gap-6 items-center p-6 mt-14">
        <!-- Left Side Content -->
        <div class="text-left ml-8">
            <form action="">
                <div class="relative mb-6">
                    <label class="flex  items-center mb-2 text-gray-600 text-sm font-medium">Name <svg width="7" height="7" class="ml-1" viewBox="0 0 7 7" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M3.11222 6.04545L3.20668 3.94744L1.43679 5.08594L0.894886 4.14134L2.77415 3.18182L0.894886 2.2223L1.43679 1.2777L3.20668 2.41619L3.11222 0.318182H4.19105L4.09659 2.41619L5.86648 1.2777L6.40838 2.2223L4.52912 3.18182L6.40838 4.14134L5.86648 5.08594L4.09659 3.94744L4.19105 6.04545H3.11222Z" fill="#EF4444" />
                    </svg>
                    </label>
                    <input type="text" id="default-search" class="block w-full bg-[#fafafa] h-11 px-5 py-2.5 leading-7 text-base font-normal shadow-xs text-gray-900 bg-transparent border border-gray-300 rounded-lg  placeholder-gray-400 focus:outline-none focus:bg-red focus:outline-none focus:ring-2 focus:ring-blue-500" placeholder="Name" required="">
                </div>
                <div class="relative mb-6">
                    <label class="flex  items-center mb-2 text-gray-600 text-sm font-medium">Email <svg width="7" height="7" class="ml-1" viewBox="0 0 7 7" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M3.11222 6.04545L3.20668 3.94744L1.43679 5.08594L0.894886 4.14134L2.77415 3.18182L0.894886 2.2223L1.43679 1.2777L3.20668 2.41619L3.11222 0.318182H4.19105L4.09659 2.41619L5.86648 1.2777L6.40838 2.2223L4.52912 3.18182L6.40838 4.14134L5.86648 5.08594L4.09659 3.94744L4.19105 6.04545H3.11222Z" fill="#EF4444" />
                    </svg>
                    </label>
                    <input type="text" id="default-search" class="block w-full bg-[#fafafa] h-11 px-5 py-2.5 leading-7 text-base font-normal shadow-xs text-gray-900 bg-transparent border border-gray-300 rounded-lg  placeholder-gray-400 focus:outline-none focus:bg-red focus:outline-none focus:ring-2 focus:ring-blue-500" placeholder="name@pagedone.com" required="">
                </div>
                <div class="relative mb-6">
                    <label class="flex  items-center mb-2 text-gray-600 text-sm font-medium">Message <svg width="7" height="7" class="ml-1" viewBox="0 0 7 7" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M3.11222 6.04545L3.20668 3.94744L1.43679 5.08594L0.894886 4.14134L2.77415 3.18182L0.894886 2.2223L1.43679 1.2777L3.20668 2.41619L3.11222 0.318182H4.19105L4.09659 2.41619L5.86648 1.2777L6.40838 2.2223L4.52912 3.18182L6.40838 4.14134L5.86648 5.08594L4.09659 3.94744L4.19105 6.04545H3.11222Z" fill="#EF4444"></path>
                    </svg>
                    </label>
                    <div class="flex">
                        <div class="relative w-full">
                            <textarea class="block w-full bg-[#fafafa] h-40 px-4 py-2.5 text-base leading-7 font-normal shadow-xs text-gray-900 bg-transparent border border-gray-300 rounded-lg  placeholder-gray-400 focus:outline-none resize-none focus:bg-red focus:outline-none focus:ring-2 focus:ring-blue-500" placeholder="Write a message..."></textarea>
                        </div>
                    </div>
                </div>
                <div class="flex justify-center">
                    <button class="w-40 h-12 bg-[#00B16E] transition-all duration-700 rounded-lg shadow-xs text-white text-base font-semibold leading-6">Send Message</button>
                </div>
               
            </form>
        </div>

        <!-- Right Side Image -->
        <div class="text-center md:text-right flex justify-center">
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3426.9878233519025!2d73.43247657654493!3d30.802975774550585!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3922a76637d4b56f%3A0xe8324f5861f1b75!2sFantech%20Labs!5e0!3m2!1sen!2s!4v1736156053681!5m2!1sen!2s" width="600" height="250" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
        </div>
    </section>
</template>

<script>    
export default {
    name: 'ContactUs',
    components: {
    }
}
</script>