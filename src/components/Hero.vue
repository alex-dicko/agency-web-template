<script setup>
import logo from "@/assets/hero_photo.png"
</script>

<template>
    <div class="bg-[#F5F7FA] flex justify-center">
        <div class="container flex flex-row  items-center pt-[96px] pb-[96px]">
            <div class="w-[60%] flex flex-col  gap-[32px]">
                <div class="flex flex-col gap-[16px]">
                    <h1 class="text-[64px] font-semibold leading-[76px]">Content required <span class="text-[#4CAF4F]">content required.</span></h1>
                    <p>Content required content required content required content required?</p>
                </div>
                <a href="" class="px-[32px] py-[14px] bg-[#4CAF4F] w-fit text-white rounded">
                    Register
                </a>
            </div>
            <img :src="logo" alt="" class=" w-[40%] aspect-[400 / 400]">
        </div>
    </div>
</template>