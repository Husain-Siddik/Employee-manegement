<template>
    <div>
        <div class="navbar bg-base-100">
            <div class="navbar-start">
                <div class="dropdown">
                    <div tabindex="0" role="button" class="btn btn-ghost btn-circle">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24"
                            stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M4 6h16M4 12h16M4 18h7" />
                        </svg>
                    </div>
                    <ul tabindex="0"
                        class="menu menu-sm dropdown-content bg-base-100 rounded-box z-[1] mt-3 w-52 p-2 shadow">
                        <!-- navigation items -->
                        <div class="flex items-center rounded-box shadow px-2">
                            <AnOutlinedUser/> 
                            <li><a>Manage User</a></li>
                        </div>
                        <div class="flex items-center rounded-box shadow px-2 mb-2">
                            <CaUserSettings />
                            <li><a>User Settings</a></li>
                        </div>
                        <hr>
                        <div class="flex items-center rounded-box shadow px-2 mt-2">
                            <HiUserGroup/>
                            <li><a>Manege Employee</a></li>
                        </div>
                        <div class="flex items-center rounded-box shadow px-2">
                            <AnOutlinedUsergroupAdd/>
                            <li><a>Manege Department</a></li>
                        </div>
                        <div class="flex items-center rounded-box shadow px-2 mb-2">
                            <BsArrowReturnRight/>
                            <li><a>Manege Designation</a></li>
                        </div>
                        <hr>
                        <div class="flex items-center rounded-box shadow px-2 mt-2">
                            <BsArrowReturnRight/>
                            <li><a>Schedule</a></li>
                        </div>
                        <div class="flex items-center rounded-box shadow px-2">
                            <BsArrowReturnRight/>
                            <li><a>Daily Attendence</a></li>
                        </div>
                        <div class="flex items-center rounded-box shadow px-2">
                            <BsArrowReturnRight/>
                            <li><a>Sheet Report</a></li>
                        </div>
                    </ul>
                </div>

                <div class="flex items-center gap-1 md:pl-5 ">
                    <p>
                        <AkPlus />
                    </p>
                    <p>new Item</p>
                </div>
            </div>

            <div class="navbar-end">
               




                <div class=" flex md:gap-6 items-center  justify-center">

                    <div class="text-xl">
                        <!-- namber of notification div  -->
                        <div class="flex gap-1">
                        <p >
                            <CaNotificationNew />
                        </p>
                        <span class="ml-[-17px] mt-[-13px] bg-blue-500 rounded-full p-1.5 text-sm text-white h-6">
                            <span class="p-0.5 pb-1">2</span>
                        </span>
                        </div>
                    </div>

                    <div>
                        <ChMessage />
                    </div>

                    <div class=" flex  items-center  justify-center">
                        <p class="text-2xl"><CaUserAvatarFilled /></p>
                        <p class=" pl-2 text-xl">Mohona acter</p>
                        <p class="text-xl pl-2">
                            <AkChevronDown />
                        </p>
                    </div>
                </div>

            </div>
        </div>
    </div>
</template>

<script setup>
import { AkPlus } from '@kalimahapps/vue-icons';



import {  CaNotificationNew, ChMessage, AkChevronDown } from '@kalimahapps/vue-icons';
import { CaUserAvatarFilled } from '@kalimahapps/vue-icons';
import { HiUserGroup ,AnOutlinedUsergroupAdd,AnOutlinedUser,CaUserSettings, } from '@kalimahapps/vue-icons';
import { BsArrowReturnRight } from '@kalimahapps/vue-icons';
</script>
