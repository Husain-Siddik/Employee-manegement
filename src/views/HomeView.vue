<script setup>
import employeedatatable from '@/components/employeedatatable.vue';
import { AkEyeOpen } from '@kalimahapps/vue-icons';
import { BxSolidTimeFive,MdSharpGroups,MdSharpGroup,BxSolidUser } from '@kalimahapps/vue-icons';
</script>

<template>
  <div class="p-10 h-screen bg-[#F6F7FB] ">
    <!-- upper section -->
    <div>
      <p class="text-2xl pb-5 font-semibold">Analitics <span class="opacity-55 font-normal">DashBoard</span></p>

      <div class="flex gap-8">

        <!-- boxes  -->
        <div class="flex-1 grid grid-cols-2 gap-6 ">

          <div class="bg-white  rounded-lg">
            <div class="">

              <div class="flex  gap-6 p-5 justify-between  ">
                <p class=" flex-1 text-xl opacity-60">Schedules</p>

                <div class="  text-blue-500 bg-blue-200 border p-5 rounded-full  ">
                  <div class="text-4xl flex justify-center items-center text-center h-10 w-10 ">
                    <div>
                      <BxSolidTimeFive />
                    </div>

                  </div>

                </div>
              </div>
              <!-- namber -->
              <p class="text-3xl pl-5 pb-10">2</p>

            </div>

          </div>
          <!-- 2nd -->
          <div class="bg-white  rounded-lg">
            <div>

              <div class="flex  gap-6 p-5 justify-between  ">
                <p class=" flex-1 text-xl opacity-60">Departments</p>

                <div class="  text-blue-500 bg-blue-200 border p-5 rounded-full  ">
                  <div class="text-4xl flex justify-center items-center text-center h-10 w-10 ">
                    <div>
                      <MdSharpGroups/>
                    </div>

                  </div>

                </div>
              </div>
              <!-- namber -->
              <p class="text-3xl pl-5 pb-10">20</p>

            </div>

          </div>
          <!--3rd  -->
          <div class="bg-white  rounded-lg">
            <div>

              <div class="flex  gap-6 p-5 justify-between  ">
                <p class=" flex-1 text-xl opacity-60">Employees</p>

                <div class="  text-blue-500 bg-blue-200 border p-5 rounded-full  ">
                  <div class="text-4xl flex justify-center items-center text-center h-10 w-10 ">
                    <div>
                      <MdSharpGroup/>
                    </div>

                  </div>

                </div>
              </div>
              <!-- namber -->
              <p class="text-3xl pl-5 pb-10">3</p>

            </div>

          </div>
          <!-- 4th -->

          <div class="bg-white  rounded-lg">
            <div>

              <div class="flex  gap-6 p-5 justify-between  ">
                <p class=" flex-1 text-xl opacity-60">Users & Members</p>

                <div class="  text-blue-500 bg-blue-200 border p-5 rounded-full  ">
                  <div class="text-4xl flex justify-center items-center text-center h-10 w-10 ">
                    <div>
                      <BxSolidUser/>
                    </div>

                  </div>

                </div>
              </div>
              <!-- namber -->
              <p class="text-3xl pl-5 pb-10">8</p>

            </div>

          </div>



        </div>
        <!-- boxes  -->

        <!-- table start -->
        <div class=" flex-1 bg-white p-3 rounded-lg ">

          <div>
            <div class="overflow-x-auto">
              <!-- upper the tabil -->
              <div class=" flex justify-between pb-2 opacity-60 font-semibold">
                <p class="text-xl pl-1 pb-3">User & Member</p>

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
                    <th>Name of User</th>
                    <th>User Role</th>
                    <th>Date Joined</th>
                  </tr>
                </thead>
                <tbody>

                  <!-- row 1 -->
                  <tr>

                    <th>1</th>
                    <td>Husain Siddik</td>
                    <td>Super Admin</td>
                    <td>

                      10 hour ago

                    </td>
                  </tr>
                  <!-- row 2 -->
                  <tr>

                    <th>2</th>
                    <td>Husain Rony</td>
                    <td>Super Admin</td>
                    <td>

                      10 hour ago

                    </td>


                  </tr>
                  <!-- row 3 -->
                  <tr>

                    <th>3</th>
                    <td>Rony Ahamed</td>
                    <td>Super Admin</td>
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
        <!-- table end -->
      </div>

    </div>
    <!-- upper section end -->

    <!-- lower section start -->
     <div class="mt-8"> 
      <employeedatatable/>
     </div>
   
      
     <!-- lower section end -->
  </div>
</template>
