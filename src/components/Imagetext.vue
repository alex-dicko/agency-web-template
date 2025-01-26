<script setup>
import { defineProps } from 'vue';
import photo from "@/assets/text_image.png"

defineProps({
    image: {
        type: Image,
        default: photo,
    },
    text: {
        type: String,
        default: "lorem"
    }
})
</script>

<template>
<div class="flex justify-center pt-[100px] pb-[100px]">
    <div class="container flex flex-row gap-[50px] items-center">
        <div class="w-[40%]">
            <img :src="image" alt="" class="aspect-[440 / 320] w-full">
        </div>
        <div class="flex flex-col gap-[32px] w-[60%]">
            <div class="flex flex-col gap-[16px]">
                <h3 class="font-semibold text-[36px]">The unseen of spending three years at Pixelgrade</h3>
                <p class="text-[14px] text-[#717171]">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed sit amet justo ipsum. Sed accumsan quam vitae est varius fringilla. Pellentesque placerat vestibulum lorem sed porta. Nullam mattis tristique iaculis. Nullam pulvinar sit amet risus pretium auctor. Etiam quis massa pulvinar, aliquam quam vitae, tempus sem. Donec elementum pulvinar odio.</p>
            </div>
            <a href="" class="px-[32px] py-[14px] bg-[#4CAF4F] w-fit text-white rounded">
                    Register
            </a>
        </div>
    </div>
</div>
</template>