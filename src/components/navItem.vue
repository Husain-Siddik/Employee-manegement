<script setup>
import { BsJustifyLeft, AnOutlinedPlus, CaNotificationNew, ChMessage, CgProfile, AkChevronDown } from '@kalimahapps/vue-icons';


</script>



<template>
    <div class=" flex w-10/12 h-10 border text-3xl justify-between">
        <div class="flex  gap-4 items-center justify-center">
            <div>
                <BsJustifyLeft />
            </div>

            <div class=" flex text-xl justify-center items-center ">
                <p>
                    <AnOutlinedPlus />
                </p>
                <p class="pl-2 text-xl">New item</p>
            </div>
        </div>
        <!-- right side -->
        <div class=" flex gap-6 items-center  justify-center">

            <div>
                <!-- namber of notification div  -->
                <p class="flex gap-1">
                    <p class=" "><CaNotificationNew /></p>
                    <span class="ml-[-17px] mt-[-13px] bg-blue-500 rounded-full p-1.5 text-sm text-white h-6">
                        <span class="p-0.5 pb-1">2</span>
                      </span>
                </p>
            </div>

            <div>
                <ChMessage />
            </div>

            <div class=" flex  items-center  justify-center">
                <CgProfile />
                <p class=" pl-2 text-xl">mohona acter</p>
                <p class="text-xl pl-2">
                    <AkChevronDown />
                </p>
            </div>
        </div>
    </div>
</template>
