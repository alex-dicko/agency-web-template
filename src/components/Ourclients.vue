<script setup>
import logo from "@/assets/Logo.png"
</script>

<template>
    <div class="flex justify-center pt-[40px] text-center">
        <div class="container flex flex-col gap-[50px]">
            <div class="flex flex-col gap-[8px]">
                <h2 class="font-semibold text-[36px]">Our Clients</h2>
                <p class="text-[16px]">Content required content required content required.</p>
            </div>

            <div class="grid grid-cols-7 items-center justify-center">
                <div class="flex justify-center items-center w-full">
                    <img :src="logo" alt="" class="aspect-[1 / 1] w-[48px] h-[48px] flex justify-center items-center">
                </div>
                <div class="flex justify-center items-center w-full">
                    <img :src="logo" alt="" class="aspect-[1 / 1] w-[48px] h-[48px] flex justify-center items-center">
                </div>
                <div class="flex justify-center items-center w-full">
                    <img :src="logo" alt="" class="aspect-[1 / 1] w-[48px] h-[48px] flex justify-center items-center">
                </div>
                <div class="flex justify-center items-center w-full">
                    <img :src="logo" alt="" class="aspect-[1 / 1] w-[48px] h-[48px] flex justify-center items-center">
                </div>
                <div class="flex justify-center items-center w-full">
                    <img :src="logo" alt="" class="aspect-[1 / 1] w-[48px] h-[48px] flex justify-center items-center">
                </div>
                <div class="flex justify-center items-center w-full">
                    <img :src="logo" alt="" class="aspect-[1 / 1] w-[48px] h-[48px] flex justify-center items-center">
                </div>
                <div class="flex justify-center items-center w-full">
                    <img :src="logo" alt="" class="aspect-[1 / 1] w-[48px] h-[48px] flex justify-center items-center">
                </div>
            </div>
        </div>
    </div>

</template>