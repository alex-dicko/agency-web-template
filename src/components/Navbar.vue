<script setup>
// var element = $("nav");
// var elementPosition = $([element]).position().top + $([element]).height();

// $(document).on('scroll', function() {
//     if($(this).scrollTop() > elementPosition){
//         element.addClass('sticky-nav')
//     }
// })

</script>

<template>

    <nav class="flex flex-row items-center justify-center bg-[#F5F7FA]">
        <div class="container grid grid-cols-3 items-center pt-[30px] pb-[30px]">
            <div class="font-bold text-[24px]">Agency Name</div>
            
            <ul class="flex justify-center gap-[50px]">
                <li><a href="#">Home</a></li>
                <li><a href="#about">Services</a></li>
                <li><a href="#work">Features</a></li>
                <li><a href="#work">Products</a></li>
                <li><a href="#work">Testimonials</a></li>
                <li><a href="#work">FAQ</a></li>

            </ul>
            <div class="hidden sm:flex justify-end gap-[34px] items-center">
                <a class="text-[#4CAF4F]">
                    Log In
                </a>
                <a class="rounded py-[10px] px-[20px] bg-[#4CAF4F] text-white">
                    Sign Up
                </a>
            </div>
        </div>
    </nav>

</template>

<style>
.sticky-nav {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
}
</style>
