<template>


    <div class="p-10 h-screen bg-[#F6F7FB] ">
        <div class="flex items-center justify-between pl-1 pb-5 ">
            <div class="text-xl">
                Manege user
            </div>
            <div>
                <button class="btn bg-blue-400 hover:bg-green-700 text-white py-1 ">
                    <span class="text-white ">
                        <AkPlus/>
                    </span>
                    Add new</button>
            </div>
        </div>

        <!-- component -->
        <manegeUser />
    </div>
</template>

<script setup>
import manegeUser from '@/components/manegeUser.vue';

import { AkPlus } from '@kalimahapps/vue-icons';
</script>

<style lang="scss" scoped></style>