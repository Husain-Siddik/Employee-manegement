<template>
    <div>
        <div class=" flex-1 bg-white p-3 rounded-lg ">

            <div>
                <div class="overflow-x-auto">
                    <!-- upper the tabil -->
                    <div class=" flex justify-between pb-2 opacity-60 font-semibold">
                        <p class="text-xl pl-1 pb-3">Employee Data table</p>

                        <div class="">
                            <button
                                class="inline-flex items-center justify-center gap-3 border p-2 font-semibold text-white hover:text-black bg-gray-600 hover:bg-gray-400">
                                <span>
                                    <AkEyeOpen />
                                </span>
                                View</button>
                        </div>

                    </div>
                    <!--upper the tabil  -->

                    <table class="table table-zebra bg-white  rounded-md text-xl cursor-pointer">
                        <!-- head -->
                        <thead class="text-xl">
                            <tr>
                                <th>SL</th>
                                <th>Name of Employee</th>
                                <th>Department</th>
                                <th>Disignation</th>
                                <th>Date Joined</th>
                            </tr>
                        </thead>
                        <tbody>

                            <!-- row 1 -->
                            <tr>

                                <th>1</th>
                                <td>Husain Siddik</td>
                                <td>human Resource</td>
                                <td>CEO</td>
                                <td>

                                    10 hour ago

                                </td>
                            </tr>
                            <!-- row 2 -->
                            <tr>

                                <th>2</th>
                                <td>Husain Rony</td>
                                <td>Operation & Supply Chain</td>
                                <td>COO</td>
                                <td>

                                    10 hour ago

                                </td>


                            </tr>
                            <!-- row 3 -->
                            <tr>

                                <th>3</th>
                                <td>Rony Ahamed</td>
                                <td>Human Resource</td>
                                <td>CIO</td>
                                <td>

                                    10 hour ago

                                </td>
                            </tr>
                            <!-- row 4 -->
                            <tr>

                                <th>3</th>
                                <td>Raju Ahamed</td>
                                <td>Adminastritator</td>
                                <td>

                                    10 hour ago

                                </td>
                            </tr>


                        </tbody>
                    </table>

                </div>
            </div>

        </div>
    </div>
</template>

<script setup>
import { AkEyeOpen } from '@kalimahapps/vue-icons';
</script>

