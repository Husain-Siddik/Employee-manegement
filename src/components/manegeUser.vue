<template>

    <div class="h-full w-full ">

        <div>
            <div class="overflow-x-auto">
                <!-- upper the tabil -->
                <div class=" pb-2 opacity-60 font-semibold">
                    <p class="text-xl pl-1 pb-3">User DataTable</p>
                    <div class="flex justify-between px-1">
                        <p>Show

                            <span class="w-1"> <input class="w-12  border p-1 rounded-md" type="number"
                                    placeholder="10">
                            </span>
                            entirs
                        </p>

                        <div class="flex items-center gap-2">
                            <p>Search: </p>
                            <input class="border rounded-md" type="text">
                        </div>
                    </div>
                </div>
                <!--upper the tabil  -->

                <table class="table table-zebra bg-white  rounded-md text-xl cursor-pointer">
                    <!-- head -->
                    <thead class="text-xl">
                        <tr>
                            <th>SL</th>
                            <th>Name</th>
                            <th>Email</th>
                            <th>Phone</th>
                            <th>User Role</th>
                            <th>Status</th>
                            <th>Action</th>
                        </tr>
                    </thead>
                    <tbody>

                        <!-- row 1 -->
                        <tr>

                            <th>1</th>
                            <td>Cy Ganderton</td>
                            <td>Quality Control Specialist</td>
                            <td>+8801329990213</td>
                            <td>
                                <span class="bg-cyan-600 px-2 py-1 rounded-md text-white text-base">
                                    Super Admin
                                </span>
                            </td>

                            <td> <span class="bg-green-500 px-2 py-1 rounded-md text-white text-base">Enable</span></td>

                            <td class="inline-flex gap-2  text-xl ">
                                <span class="text-blue-600 border border-blue-600 p-2">
                                    <BxEdit />
                                </span>

                                <span class=" text-red-600 border border-red-600 p-2">
                                    <AnFilledDelete />
                                </span>
                            </td>
                        </tr>
                        <!-- row 2 -->
                        <tr>
                            <th>2</th>
                            <td>Cy Ganderton</td>
                            <td>Quality Control Specialist</td>
                            <td>Blue</td>
                            <td>Blue</td>
                            <td>Blue</td>
                            <td>Blue</td>
                        </tr>
                        <!-- row 3 -->
                        <tr>
                            <th>3</th>
                            <td>Cy Ganderton</td>
                            <td>Quality Control Specialist</td>
                            <td>Blue</td>
                            <td>Blue</td>
                            <td>Blue</td>
                            <td>Blue</td>
                        </tr>
                        <tr>
                            <th>4</th>
                            <td>Cy Ganderton</td>
                            <td>Quality Control Specialist</td>
                            <td>Blue</td>
                            <td>Blue</td>
                            <td>Blue</td>
                            <td>Blue</td>
                        </tr>

                    </tbody>
                </table>

                <!-- lower section  -->

                <div class="bg-white">
                    <hr>
                    <div class="flex justify-between px-1 py-2 text-lg opacity-55">
                        <p> Showing 1 to 8 of 8 entries</p>
                        <div class="flex gap-2 pr-4">
                            <button class="border px-1"> Previous</button>
                            <button class="border px-1"> Next</button>
                        </div>
                    </div>
                </div>
                <!-- lower section -->
            </div>
        </div>

    </div>
</template>
<script setup>
import { BxEdit, AnFilledDelete } from '@kalimahapps/vue-icons';
</script>