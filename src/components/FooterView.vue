<script setup lang="ts">
import { PhMagnifyingGlass } from '@phosphor-icons/vue'
</script>
<template>
  <footer class="bg-black text-white">
    <div class="c-footer">
      <form class="flex gap-10 items-center">
        <div>
          <img src="../assets/logo.svg" alt="Logo" class="w-16" />
        </div>
        <div
          class="border-[#837379] border flex overflow-hidden flex-1 rounded items-center focus-within:bg-[#001821]"
        >
          <PhMagnifyingGlass class="ml-4" color="#837379" />
          <input
            placeholder="Search here..."
            type="search"
            class="p-4 bg-transparent flex-1 focus:outline-none placeholder:text-[#837379]"
          />
          <button class="bg-primary text-[#E9D800] px-8 self-stretch" type="submit">Search</button>
        </div>
      </form>
      <div class="grid grid-cols-2 md:grid-cols-6 gap-10">
        <div class="flex flex-col gap-10">
          <div class="flex flex-col gap-5">
            <div class="font-medium text-xl">World</div>
            <ul class="flex flex-col gap-5">
              <li>
                <RouterLink to="/">France</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Americas</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Asia</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Australia</RouterLink>
              </li>
              <li>
                <RouterLink to="/">China</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Europe</RouterLink>
              </li>
              <li>
                <RouterLink to="/">India</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Middle East</RouterLink>
              </li>
              <li>
                <RouterLink to="/">United Kingdom</RouterLink>
              </li>
            </ul>
          </div>
          <div class="flex flex-col gap-5">
            <div class="font-medium text-xl">Travel</div>
            <ul class="flex flex-col gap-5">
              <li>
                <RouterLink to="/">Destinations</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Food and Drink</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Stay</RouterLink>
              </li>
              <li>
                <RouterLink to="/">News</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Videos</RouterLink>
              </li>
            </ul>
          </div>
        </div>
        <div class="flex flex-col gap-10">
          <div class="flex flex-col gap-5">
            <div class="font-medium text-xl">US Politics</div>
            <ul class="flex flex-col gap-5">
              <li>
                <RouterLink to="/">The Biden Presidency</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Facts First</RouterLink>
              </li>
              <li>
                <RouterLink to="/">US Elections</RouterLink>
              </li>
            </ul>
          </div>
          <div class="flex flex-col gap-5">
            <div class="font-medium text-xl">Sports</div>
            <ul class="flex flex-col gap-5">
              <li>
                <RouterLink to="/">Football</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Tenis</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Olympics</RouterLink>
              </li>
              <li>
                <RouterLink to="/">US Sports</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Climbing</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Motorsport</RouterLink>
              </li>
              <li>
                <RouterLink to="/">ESports</RouterLink>
              </li>
            </ul>
          </div>
          <div class="flex flex-col gap-5">
            <div class="font-medium text-xl">Features</div>
            <ul class="flex flex-col gap-5">
              <li>
                <RouterLink to="/">Climate</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Storm Tracker</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Wildfire Tracker</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Video</RouterLink>
              </li>
            </ul>
          </div>
        </div>
        <div class="flex flex-col gap-10">
          <div class="flex flex-col gap-5">
            <div class="font-medium text-xl">Business</div>
            <ul class="flex flex-col gap-5">
              <li>
                <RouterLink to="/">Markets</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Tech</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Media</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Success</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Perspectives</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Videos</RouterLink>
              </li>
            </ul>
          </div>
          <div class="flex flex-col gap-5">
            <div class="font-medium text-xl">Videos</div>
            <ul class="flex flex-col gap-5">
              <li>
                <RouterLink to="/">Live TV</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Digital Studios</RouterLink>
              </li>
              <li>
                <RouterLink to="/">CNN Films</RouterLink>
              </li>
              <li>
                <RouterLink to="/">HNL</RouterLink>
              </li>
              <li>
                <RouterLink to="/">TV Schedule</RouterLink>
              </li>
              <li>
                <RouterLink to="/">TV Shows A-Z</RouterLink>
              </li>
              <li>
                <RouterLink to="/">CNNVR</RouterLink>
              </li>
            </ul>
          </div>
        </div>
        <div class="flex flex-col gap-10">
          <div class="flex flex-col gap-5">
            <div class="font-medium text-xl">Health</div>
            <ul class="flex flex-col gap-5">
              <li>
                <RouterLink to="/">Life, But Better</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Fitness </RouterLink>
              </li>
              <li>
                <RouterLink to="/">Food</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Sleep</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Mindfulness</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Relationships</RouterLink>
              </li>
            </ul>
          </div>
          <div class="flex flex-col gap-5">
            <div class="font-medium text-xl">Style</div>
            <ul class="flex flex-col gap-5">
              <li>
                <RouterLink to="/">Arts</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Design</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Fashion</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Architecture</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Luxury</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Beauty</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Video</RouterLink>
              </li>
            </ul>
          </div>
        </div>
        <div class="flex flex-col gap-10">
          <div class="flex flex-col gap-5">
            <div class="font-medium text-xl">Health</div>
            <ul class="flex flex-col gap-5">
              <li>
                <RouterLink to="/">Stars</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Screen</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Binge</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Culture</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Media</RouterLink>
              </li>
            </ul>
          </div>
          <div class="flex flex-col gap-5">
            <div class="font-medium text-xl">Style</div>
            <ul class="flex flex-col gap-5">
              <li>
                <RouterLink to="/">Arts</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Design</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Fashion</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Architecture</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Luxury</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Beauty</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Video</RouterLink>
              </li>
            </ul>
          </div>
        </div>
        <div class="flex flex-col gap-10">
          <div class="flex flex-col gap-5">
            <div class="font-medium text-xl">Tech</div>
            <ul class="flex flex-col gap-5">
              <li>
                <RouterLink to="/">Innovate</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Gadget</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Foreseeable Future</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Mission: Ahead</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Upstarts</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Work Transformed</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Innovative Cities</RouterLink>
              </li>
            </ul>
          </div>
          <div class="flex flex-col gap-5">
            <div class="font-medium text-xl">More</div>
            <ul class="flex flex-col gap-5">
              <li>
                <RouterLink to="/">Photos</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Longform </RouterLink>
              </li>
              <li>
                <RouterLink to="/">Investigations</RouterLink>
              </li>
              <li>
                <RouterLink to="/">CNN Profiles</RouterLink>
              </li>
              <li>
                <RouterLink to="/">CNN Leadership</RouterLink>
              </li>
              <li>
                <RouterLink to="/">CNN Newsletters</RouterLink>
              </li>
              <li>
                <RouterLink to="/">Work for CNN</RouterLink>
              </li>
            </ul>
          </div>
        </div>
      </div>
      <hr class="border-[#232324]" />
      <div class="flex items-center justify-between text-sm">
        <div class="flex flex-1 items-center gap-8">
          <RouterLink to="/">About Us</RouterLink>
          <RouterLink to="/">Privacy Policy</RouterLink>
        </div>
        <div class="flex gap-4 items-center">
          <div class="uppercase">Follow Us</div>
          <div class="border border-white rounded p-1">
            <svg
              width="20"
              height="20"
              viewBox="0 0 35 35"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M19.146 28V18.4365H22.4038L22.8881 14.6921H19.146V12.307C19.146 11.2265 19.45 10.4867 21.0159 10.4867H23V7.14839C22.0346 7.04593 21.0642 6.99646 20.0933 7.0002C17.2137 7.0002 15.2366 8.74114 15.2366 11.9371V14.6851H12V18.4295H15.2437V28H19.146Z"
                fill="white"
              />
            </svg>
          </div>
          <div class="border border-white rounded p-1">
            <svg
              width="20"
              height="20"
              viewBox="0 0 33 33"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M27.7764 14.2477H26.85V14.2H16.5V18.8H22.9992C22.0511 21.4778 19.5032 23.4 16.5 23.4C12.6895 23.4 9.60001 20.3105 9.60001 16.5C9.60001 12.6895 12.6895 9.60001 16.5 9.60001C18.2589 9.60001 19.8592 10.2636 21.0776 11.3474L24.3304 8.09465C22.2765 6.18048 19.5291 5 16.5 5C10.1491 5 5 10.1491 5 16.5C5 22.8509 10.1491 28 16.5 28C22.8509 28 28 22.8509 28 16.5C28 15.7289 27.9207 14.9763 27.7764 14.2477Z"
                fill="#FFC107"
              />
              <path
                d="M6.3259 11.1473L10.1042 13.9183C11.1266 11.3871 13.6025 9.6 16.5 9.6C18.2589 9.6 19.8591 10.2636 21.0775 11.3474L24.3303 8.09465C22.2764 6.18048 19.5291 5 16.5 5C12.0828 5 8.25215 7.49378 6.3259 11.1473Z"
                fill="#FF3D00"
              />
              <path
                d="M16.5 28.0006C19.4704 28.0006 22.1695 26.8638 24.2102 25.0152L20.6509 22.0034C19.4575 22.9109 17.9993 23.4018 16.5 23.4006C13.5088 23.4006 10.969 21.4933 10.0122 18.8317L6.26208 21.721C8.16534 25.4453 12.0305 28.0006 16.5 28.0006Z"
                fill="#4CAF50"
              />
              <path
                d="M27.7763 14.2479H26.85V14.2002H16.5V18.8002H22.9992C22.5457 20.0746 21.7287 21.1883 20.6492 22.0035L20.6509 22.0024L24.2102 25.0142C23.9583 25.2431 28 22.2502 28 16.5002C28 15.7291 27.9207 14.9764 27.7763 14.2479Z"
                fill="#1976D2"
              />
            </svg>
          </div>
          <div class="border border-white rounded p-1">
            <svg
              width="20"
              height="20"
              viewBox="0 0 36 36"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M25.3931 17.7401C25.3805 15.6089 26.3531 14.0027 28.317 12.8184C27.2186 11.256 25.5568 10.3966 23.3662 10.231C21.2921 10.0685 19.0229 11.431 18.192 11.431C17.3139 11.431 15.3059 10.2873 13.7259 10.2873C10.4652 10.3373 7 12.8684 7 18.0182C7 19.54 7.28011 21.1118 7.84034 22.7305C8.58941 24.8617 11.2898 30.0834 14.1067 29.999C15.5797 29.9646 16.6215 28.9615 18.5382 28.9615C20.3983 28.9615 21.3614 29.999 23.0043 29.999C25.8464 29.9584 28.2887 25.2117 29 23.0743C25.1886 21.29 25.3931 17.8495 25.3931 17.7401ZM22.0853 8.20921C23.681 6.32803 23.5362 4.6156 23.489 4C22.079 4.08125 20.4486 4.95309 19.5202 6.02492C18.4973 7.17488 17.8961 8.5967 18.0252 10.1998C19.5485 10.3154 20.9396 9.53728 22.0853 8.20921Z"
                fill="white"
              />
            </svg>
          </div>
        </div>
      </div>
    </div>
    <div class="bg-[#010101] py-3 text-center font-light text-sm text-gray-300">
      © {{ new Date().getFullYear() }} Access24.All Rights Reserved.
    </div>
  </footer>
</template>
