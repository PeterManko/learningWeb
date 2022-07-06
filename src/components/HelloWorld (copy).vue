
<template>
  <!-- <div
    class="w-[360px] cursor-pointer rounded-[8px] bg-pink-300 p-[30px] text-white"
    @click="count++"
  >
    <h1>{{ msg }}</h1>
    <p>count is: {{ count }}</p>
  </div> -->



  <div class="w-[1380px] ">
    <div class="parent md:p-[40px] ">
      <div class="ml-[24px] my-[32px] sm:py-[24px]  flex flex-col">
        <div class="">

           <div class="flex">
            <!-- pfp div -->
             <div class="w-1/6">
                    <div class="relative h-[209px] w-[209px]">
                        <img class="rounded-full" src="https://picsum.photos/209" alt="pfp">
                          <svg xmlns="http://www.w3.org/2000/svg" class="bg-[#FFCA41] rounded-full h-[40px] w-[40px] absolute bottom-0 right-[29px]" viewBox="0 0 20 20" fill="white">
                            <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
                          </svg>
                        
            </div>
            </div>
           <div class="px-[56px] w-full relative">
            <!-- top row -->
            <div class="flex">
              <div class="w-full">
                <h1 class="font-lato text-[24px] font-semibold leading-[32px]" >Alexandra K.</h1>
              </div>
              <!-- languages -->
              <div class="flex">
                      <svg width="24" class="rounded-full mr-[16px]" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H8.00156V24H0V0Z" fill="#009246"/>
                        <path fill-rule="evenodd" clip-rule="evenodd" d="M15.9984 0H24V24H15.9984V0Z" fill="#CE2B37"/>
                      </svg>

                      <svg width="24" class="rounded-full mr-[16px]" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <mask id="mask0_1_185" style="mask-type:alpha" maskUnits="userSpaceOnUse" x="0" y="0" width="24" height="24">
                        <circle cx="12" cy="12" r="12" fill="#C4C4C4"/>
                        </mask>
                        <g mask="url(#mask0_1_185)">
                        <path d="M-12 0H36V24H-12V0Z" fill="#012169"/>
                        <path d="M-12 0V2.6832L30.6336 24H36V21.3168L-6.6336 0.0048H-12V0ZM36 0V2.6832L-6.6336 24H-12V21.3168L30.6336 0H36Z" fill="white"/>
                        <path d="M8.0016 0V24H15.9984V0H8.0016ZM-12 8.0016V15.9984H36V8.0016H-12Z" fill="white"/>
                        <path d="M-12 9.6V14.4H36V9.6H-12ZM9.6 0V24H14.4V0H9.6ZM-12 24L3.9984 15.9984H7.584L-8.424 24H-12ZM-12 0L3.9984 8.0016H0.4224L-12 1.7904V0ZM16.4208 8.0016L32.424 0H36L20.0016 8.0016H16.416H16.4208ZM36.0048 24L19.9968 15.9984H23.5728L36 22.2096V24H36.0048Z" fill="#CE2B37"/>
                        </g>
                      </svg>

                      <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <mask id="mask0_1_186" style="mask-type:alpha" maskUnits="userSpaceOnUse" x="0" y="0" width="24" height="24">
                        <circle cx="12" cy="12" r="12" fill="#C4C4C4"/>
                        </mask>
                        <g mask="url(#mask0_1_186)">
                        <path d="M0 15.9985H24V24.0001H0V15.9985Z" fill="#FFA500"/>
                        <path d="M0 0H24V8.00156H0V0Z" fill="#1E293B"/>
                        <path d="M0 8.00146H24V15.9983H0V8.00146Z" fill="#CE2B37"/>
                        </g>
                      </svg>



              </div>

            </div>
            <!-- tags -->
            <div class=" my-[16px] font-nunito leading-[24px] flex items-start">
              
              <!-- pills -->
              <div class="rounded-full bg-[#EC3A47]/[0.08] text-sm  px-[6px] py-[6px]  text-center mr-[24px]">
                <div class="items-start flex px-[10px] text-[#EC3A47]">
                  <div class="py-[3px] px-[3px]">
                  <svg width="16" height="12" viewBox="0 0 16 12" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                    <path d="M0 1.28571V10.7143C0 11.4241 0.597222 12 1.33333 12H2.66667V0H1.33333C0.597222 0 0 0.575893 0 1.28571ZM3.55556 12H12.4444V0H3.55556V12ZM5.33333 5.35714C5.33333 5.23929 5.43333 5.14286 5.55556 5.14286H7.11111V3.64286C7.11111 3.525 7.21111 3.42857 7.33333 3.42857H8.66667C8.78889 3.42857 8.88889 3.525 8.88889 3.64286V5.14286H10.4444C10.5667 5.14286 10.6667 5.23929 10.6667 5.35714V6.64286C10.6667 6.76071 10.5667 6.85714 10.4444 6.85714H8.88889V8.35714C8.88889 8.475 8.78889 8.57143 8.66667 8.57143H7.33333C7.21111 8.57143 7.11111 8.475 7.11111 8.35714V6.85714H5.55556C5.43333 6.85714 5.33333 6.76071 5.33333 6.64286V5.35714ZM14.6667 0H13.3333V12H14.6667C15.4028 12 16 11.4241 16 10.7143V1.28571C16 0.575893 15.4028 0 14.6667 0Z" fill="#EC3A47"/>
                  </svg>
                </div>
               
                <p class="px-[3px]">First aid</p>
                </div>
              </div>
              
              <!-- pill -->
              <div class="rounded-full bg-[#EC3A47]/[0.08] text-sm  px-[6px]  py-[6px] text-center mr-[24px]">
                <div class="items-start flex px-[10px] text-[#EC3A47]">
                  <div class="py-[3px] px-[3px]">
                  <svg width="16" height="12" viewBox="0 0 16 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M15.6246 3.5H13.7537L13.2337 2.2C12.6993 0.863438 11.424 0 9.98427 0H6.01552C4.57614 0 3.30052 0.863438 2.76583 2.2L2.24583 3.5H0.375199C0.131137 3.5 -0.0479262 3.72938 0.0114489 3.96594L0.198949 4.71594C0.240512 4.88282 0.390512 5.00001 0.5627 5.00001H1.18989C0.7702 5.36657 0.499887 5.89938 0.499887 6.50001V8.00001C0.499887 8.50376 0.692387 8.95845 0.999888 9.31032V11C0.999888 11.5522 1.4477 12 1.99989 12H2.99989C3.55208 12 3.99989 11.5522 3.99989 11V10H11.9999V11C11.9999 11.5522 12.4477 12 12.9999 12H13.9999C14.5521 12 14.9999 11.5522 14.9999 11V9.31032C15.3074 8.95876 15.4999 8.50407 15.4999 8.00001V6.50001C15.4999 5.89938 15.2296 5.36657 14.8102 5.00001H15.4374C15.6096 5.00001 15.7596 4.88282 15.8012 4.71594L15.9887 3.96594C16.0477 3.72938 15.8687 3.5 15.6246 3.5ZM4.6227 2.94282C4.85052 2.37344 5.40208 2 6.01552 2H9.98427C10.5977 2 11.1493 2.37344 11.3771 2.94282L11.9999 4.5H3.99989L4.6227 2.94282ZM2.99989 7.99376C2.39989 7.99376 1.99989 7.59501 1.99989 6.99688C1.99989 6.39876 2.39989 6.00001 2.99989 6.00001C3.59989 6.00001 4.49989 6.8972 4.49989 7.49532C4.49989 8.09345 3.59989 7.99376 2.99989 7.99376ZM12.9999 7.99376C12.3999 7.99376 11.4999 8.09345 11.4999 7.49532C11.4999 6.8972 12.3999 6.00001 12.9999 6.00001C13.5999 6.00001 13.9999 6.39876 13.9999 6.99688C13.9999 7.59501 13.5999 7.99376 12.9999 7.99376Z" fill="#EC3A47"/>
                  </svg>

                </div>
               
                <p class="px-[3px]">Own car</p>
                </div>
              </div>
              <!-- pill -->
              <div class="rounded-full bg-[#EC3A47]/[0.08] text-sm  px-[6px]  py-[6px] text-center mr-[24px]">
                <div class="items-start flex px-[10px] text-[#EC3A47]">
                  <div class="py-[3px] px-[3px]">
                  <svg width="16" height="14" viewBox="0 0 16 14" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M15.9852 11.4404C15.7752 10.9304 15.1902 10.6879 14.6802 10.9004L14.1277 11.1304L13.1602 8.58291C14.3577 7.70791 14.7802 6.07541 14.0227 4.76291L11.8577 1.00041C11.6577 0.652912 11.2302 0.507912 10.8577 0.660412L8.00017 1.84541L5.14267 0.660412C4.77017 0.505412 4.34267 0.652912 4.14267 1.00041L1.97767 4.76291C1.22267 6.07541 1.64267 7.70791 2.84017 8.58041L1.87267 11.1279L1.32017 10.8979C0.81017 10.6854 0.22767 10.9279 0.0151701 11.4379C-0.0273299 11.5404 0.0201701 11.6579 0.12267 11.7004L4.18017 13.3854C4.28267 13.4279 4.39767 13.3804 4.44017 13.2779C4.65017 12.7679 4.41017 12.1829 3.90017 11.9704L3.34767 11.7404L4.33267 9.15041C4.44267 9.16291 4.55267 9.18291 4.66017 9.18291C5.95267 9.18291 7.14517 8.35541 7.49517 7.05041L8.00017 5.16541L8.50517 7.05041C8.85517 8.35541 10.0477 9.18291 11.3402 9.18291C11.4477 9.18291 11.5577 9.16291 11.6677 9.15041L12.6502 11.7404L12.0977 11.9704C11.5877 12.1829 11.3452 12.7679 11.5577 13.2779C11.6002 13.3804 11.7177 13.4279 11.8177 13.3854L15.8777 11.7004C15.9777 11.6579 16.0277 11.5429 15.9852 11.4404ZM6.89767 4.65291L4.09517 3.49041L5.00767 1.90541L7.37017 2.88541L6.89767 4.65291ZM9.10267 4.65291L8.63017 2.88541L10.9927 1.90541L11.9052 3.49041L9.10267 4.65291Z" fill="#EC3A47"/>
                  </svg>

                </div>
               
                <p class="px-[3px]">Event jobs</p>
                </div>
              </div>
              <!-- pill -->
              <div class="rounded-full bg-[#EC3A47]/[0.08] text-sm  px-[6px]  py-[6px] text-center mr-[24px]">
                <div class="items-start flex px-[10px] text-[#EC3A47]">
                  <div class="py-[3px] px-[3px]">
                  <svg width="12" height="16" viewBox="0 0 12 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M10.5 5H1.5C0.671562 5 0 5.67156 0 6.5V13.5C0 14.3284 0.671562 15 1.5 15H2V15.5C2 15.7762 2.22375 16 2.5 16H3.5C3.77625 16 4 15.7762 4 15.5V15H8V15.5C8 15.7762 8.22375 16 8.5 16H9.5C9.77625 16 10 15.7762 10 15.5V15H10.5C11.3284 15 12 14.3284 12 13.5V6.5C12 5.67156 11.3284 5 10.5 5ZM10 11.75C10 11.8881 9.88813 12 9.75 12H2.25C2.11188 12 2 11.8881 2 11.75V11.25C2 11.1119 2.11188 11 2.25 11H9.75C9.88813 11 10 11.1119 10 11.25V11.75ZM10 8.75C10 8.88813 9.88813 9 9.75 9H2.25C2.11188 9 2 8.88813 2 8.75V8.25C2 8.11187 2.11188 8 2.25 8H9.75C9.88813 8 10 8.11187 10 8.25V8.75ZM4.5 1.5H7.5V4H9V1.5C9 0.671562 8.32844 0 7.5 0H4.5C3.67156 0 3 0.671562 3 1.5V4H4.5V1.5Z" fill="#EC3A47"/>
                  </svg>

                </div>
               
                <p class="px-[3px]">Traveller</p>
                </div>
              </div>
              
               <div class="rounded-full bg-[#EC3A47]/[0.08] text-sm  px-[6px]  py-[6px] text-center mr-[24px]">
                <div class="items-start flex px-[10px] text-[#EC3A47]">
                  <div class="py-[3px] px-[3px]">
                 <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M3.8025 7.505C3.715 7.2025 3.6075 6.675 3.6075 6.675H3.595C3.595 6.675 3.4875 7.2025 3.4 7.505L3.1225 8.4425H4.075L3.8025 7.505ZM15.4 4H8.4V12H15.4C15.7325 12 16 11.7325 16 11.4V4.6C16 4.2675 15.7325 4 15.4 4ZM14.8 7C14.8 7.165 14.665 7.3 14.5 7.3H14.215C14.0425 7.89 13.6725 8.485 13.1475 9.0475C13.3575 9.2075 13.575 9.36 13.8 9.4975C13.9375 9.5825 13.9825 9.76 13.9025 9.9025L13.705 10.25C13.62 10.3975 13.4325 10.445 13.2875 10.3575C12.9725 10.1625 12.675 9.955 12.4025 9.735C12.13 9.9525 11.835 10.1625 11.5175 10.3575C11.3725 10.445 11.185 10.3975 11.1 10.25L10.9025 9.9025C10.8225 9.7625 10.8675 9.5825 11.0075 9.4975C11.24 9.355 11.4575 9.205 11.66 9.0475C11.4625 8.8375 11.2875 8.6225 11.135 8.405C11.035 8.2625 11.08 8.065 11.2275 7.9775L11.39 7.88L11.5725 7.7725C11.7075 7.6925 11.8825 7.73 11.9725 7.8575C12.0975 8.0325 12.2425 8.2075 12.4075 8.38C12.745 8.025 13.0025 7.6575 13.1575 7.3H10.3C10.135 7.3 10 7.165 10 7V6.6C10 6.435 10.135 6.3 10.3 6.3H11.9V5.9C11.9 5.735 12.035 5.6 12.2 5.6H12.6C12.765 5.6 12.9 5.735 12.9 5.9V6.3H14.5C14.665 6.3 14.8 6.435 14.8 6.6V7ZM0 4.6V11.4C0 11.7325 0.2675 12 0.6 12H7.6V4H0.6C0.2675 4 0 4.2675 0 4.6ZM1.4725 10.0025L2.91 5.775C2.9525 5.6525 3.065 5.5725 3.195 5.5725H4.0075C4.135 5.5725 4.25 5.655 4.2925 5.775L5.73 10.0025C5.795 10.1975 5.6525 10.4 5.445 10.4H4.8725C4.8078 10.4 4.74485 10.379 4.69304 10.3403C4.64123 10.3015 4.60333 10.247 4.585 10.185L4.35 9.3875H2.845L2.6175 10.1825C2.58 10.31 2.4625 10.4 2.33 10.4H1.7575C1.5525 10.4 1.4075 10.1975 1.4725 10.0025Z" fill="#EC3A47"/>
                  </svg>


                </div>
               
                <p class="px-[3px]">Multilingual</p>
                </div>
              </div>

               <div class="rounded-full bg-[#EC3A47]/[0.08] text-sm  px-[6px] py-[6px] text-center mr-[24px]">
                <div class="items-start flex px-[10px] text-[#EC3A47]">
                  <div class="py-[3px] px-[3px]">
                  

                </div>
               
                <p class="px-[3px]">+2 more</p>
                </div>
              </div>
              
            </div>
           </div>

           
           

          </div>
          <!-- text -->
           <div class="my-[32px] font-lato font-[16px] font-normal leading-[28px]">
              <p class="">
                👋🏻 Reliable and with a strong motivation to grow professionally in the education sector, she knows how to take care of tasks
                assigned with commitment and resoluteness, always acting in compliance with the feedback and recommendations of colleagues
                and above with a view to continuous improve.
                </p>
            </div>

            <!-- buttons -->
           <div class="font-lato font-bold leading-[24px] font-[24px] items-start flex-row">
              <button class="rounded-full ml- bg-[#EC3A47] py-[12px] px-[32px] text-white mr-[32px]">
                BOOK NOW
              </button>
              <a href="htttps://notlikethis.com" class="text-[#EC3A47] py-[12px]">EXPLORE PROFILE</a>
            </div>
        </div>
          </div>
          </div>
          
           
    </div>
</template>
<script setup>
import { ref } from "vue";

defineProps({
  msg: String,
});

const count = ref(0);
</script>
