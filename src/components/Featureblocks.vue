<script setup>
    import icon from "@/assets/feature_icon.png"
</script>

<template>
    <div class="flex justify-center pt-[75px]">
        <div class="container text-center">
            <h1 class="text-[#4D4D4D] font-semibold text-[36px] leading-[44px]">Manage your entire community <br>in a single system</h1>
            <p class="text-[#717171] text-[16px]">Content required required required required?</p>

            <div class="grid grid-cols-3 justify-between gap-[130px] items-center">
                <div class="flex justify-center items-center">
                    <div class="card shadow-md rounded flex justify-center aspect-[1 / 1]">
                        <img :src="icon" alt="" class="w-[65px] h-[56px]">
                    </div>
                </div>
                <div class="flex justify-center items-center">
                    <div class="card shadow-md rounded flex justify-center items-center h-[300px] w-[300px]">
                        <img :src="icon" alt="" class="w-[65px] h-[56px]">
                    </div>
                </div>
                <div class="flex justify-center items-center">
                    <div class="card shadow-md rounded flex justify-center items-center h-[300px] w-[300px]">
                        <img :src="icon" alt="" class="w-[65px] h-[56px]">
                    </div>
                </div>
            </div>
        </div>
    </div>
</template> 
