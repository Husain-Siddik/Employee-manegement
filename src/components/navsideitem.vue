<script setup>
import { AnOutlinedUser } from '@kalimahapps/vue-icons';
import { CaUserSettings } from '@kalimahapps/vue-icons';
import { HiSolidAdjustmentsVertical } from '@kalimahapps/vue-icons';
import { HiUserGroup } from '@kalimahapps/vue-icons';
import { AnOutlinedUsergroupAdd } from '@kalimahapps/vue-icons';

// 
import { FaRegFileLines } from '@kalimahapps/vue-icons';
import { BxTimeFive } from '@kalimahapps/vue-icons';
import { BsCalendar3 } from '@kalimahapps/vue-icons';
import { BsCalendar4 } from '@kalimahapps/vue-icons';
import { HiArrowTrendingUp } from '@kalimahapps/vue-icons';
</script>

<template>
    <div class=" bg-slate-600 w-72  min-h-fit p-3 hidden md:block ">
        <h1 class="text-2xl text-slate-200 pb-3 ">HRMS</h1>
        <h1 class="text-base text-slate-400 flex gap-3 items-center
         hover:bg-[#E7E7E7] hover:text-black hover:text-xl hover:rounded-md  hover:pl-2 
        "> <span>
                <HiSolidAdjustmentsVertical />
            </span class="">Daseboard</h1>

        <div class="text-slate-400  space-y-2  py-4  ">

            <h1> User Manegement</h1>

            <router-link to="/manegeUser">
                <p
                    class="flex  items-center gap-2 hover:bg-[#E7E7E7] hover:text-black hover:text-xl hover:rounded-md  hover:pl-2  ">
                    <span>
                        <AnOutlinedUser />

                    </span>Manege user
                </p>
            </router-link>


            <p
                class="flex  items-center gap-2 hover:bg-[#E7E7E7] hover:text-black hover:text-xl hover:rounded-md  hover:pl-2 ">
                <span class="text-2xl">
                    <CaUserSettings />
                </span> User Settings
            </p>
        </div>

        <!-- next -->
        <div class="text-slate-400  space-y-2  py-4">
            <h1> Employee Manegement</h1>

            <router-link to="/manegeEmployee">
                <p
                    class="flex  items-center gap-2 hover:bg-[#E7E7E7] hover:text-black hover:text-xl hover:rounded-md  hover:pl-2 ">
                    <span>
                        <HiUserGroup />
                    </span>Manege Employee
                </p>
            </router-link>

            <p
                class="flex  items-center gap-2 hover:bg-[#E7E7E7] hover:text-black hover:text-lg hover:rounded-md  hover:pl-2">
                <span class="text-2xl">
                    <AnOutlinedUsergroupAdd />
                </span>Manege Departments
            </p>
            <div
                class="flex  items-center gap-2 hover:bg-[#E7E7E7] hover:text-black hover:text-xl hover:rounded-md  hover:pl-2">
                <div class="text-xl">
                    <FaRegFileLines />
                </div>
                <div>
                    <p class="">Manege Designation</p>
                </div>
            </div>
        </div>

        <!-- attendence -->

        <div class="text-slate-400  space-y-2  py-4">
            <h1> Attendence</h1>

            <router-link to="/manegeschedule">
                <p
                    class="flex  items-center gap-2 hover:bg-[#E7E7E7] hover:text-black hover:text-xl hover:rounded-md  hover:pl-2 ">
                    <span>
                        <BxTimeFive />
                    </span>Schedule
                </p>
            </router-link>

            <p
                class="flex  items-center gap-2 hover:bg-[#E7E7E7] hover:text-black hover:text-xl hover:rounded-md  hover:pl-2">
                <span class="">
                    <BsCalendar3 />
                </span>Daily Attendence
            </p>
            <div
                class="flex  items-center gap-2 hover:bg-[#E7E7E7] hover:text-black hover:text-xl hover:rounded-md  hover:pl-2">
                <div class="">
                    <BsCalendar4 />
                </div>
                <div>
                    <p>
                        Sheet report
                    </p>
                </div>
            </div>
        </div>
        <!--  leave manegement -->
        <h1 class="text-base text-slate-400  items-center  pb-4 "> <span>
                <!-- <HiSolidAdjustmentsVertical /> -->
            </span>Leave Manegement</h1>

        <div class="flex text-slate-400 items-center  gap-2">
            <div>
                <HiArrowTrendingUp />
            </div>
            <div>
                Manage Leave
            </div>
        </div>
    </div>
</template>
