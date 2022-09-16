
<template>
  <h1 class="text-center text-2xl font-bold">Search properties to rent</h1>

  <div class="m-6 flex items-center justify-center">
    <div class="flex rounded border-2 border-gray-200">
      <input type="text" class="w-80 px-4 py-2" placeholder="Search location" />
      <button class="border-l bg-gray-600 px-2 text-white">Search</button>
    </div>
  </div>

  <figure class="flex flex-col">
    <img class="rounded-t-lg" src="../assets/img/pexels-binyamin-mellish-106399 1.png" alt="Image maison" />
    <figcaption class="relative rounded-b-lg border-x-2 border-b-2 px-5 py-7">
      <div class="relative flex flex-col">
        <div class="order-first flex items-center pb-1">
          <h3 class="mr-1 text-2xl font-bold leading-8 text-indigo-500">
            $2,700
          </h3>
          <h3 class="text-base text-gray-500">/month</h3>
        </div>
        <h3 class="text-2xl font-semibold leading-8 text-gray-900">
          Beverly Springfieldg
        </h3>
        <h3 class="text-base leading-8 text-gray-400">
          2821 Lake Sevilla, Palm Harbor, TX
        </h3>
        <hr class="my-2 border-t-2 border-indigo-100" />
        <div class="flex justify-between text-sm font-normal text-gray-600">
          <div>
            <bed class="inline-block align-top text-gray-600" /> 4 Beds
          </div>
          <div>
            <bath class="inline-block align-top" /> 2 Bathrooms
          </div>
          <div>
            <dimension class="inline-block align-top text-gray-600" /> 6x7.5 m²
          </div>
        </div>
        <div class="
            absolute
            top-7
            right-5
            grid
            h-12
            w-12
            place-items-center
            rounded-full
            border-2 border-indigo-100
          ">
          <coeur />
        </div>
      </div>
    </figcaption>
  </figure>

  <figure class="flex flex-col">
    <img class="rounded-t-lg" src="../assets/img/Maison-classique-1-2-870x420.jpg" alt="Image maison" />
    <figcaption class="relative rounded-b-lg border-x-2 border-b-2 px-5 py-7">
      <div class="relative flex flex-col">
        <div class="order-first flex items-center pb-1">
          <h3 class="mr-1 text-2xl font-bold leading-8 text-indigo-500">
            $1,400
          </h3>
          <h3 class="text-base text-gray-500">/month</h3>
        </div>
        <h3 class="text-2xl font-semibold leading-8 text-gray-900">
          W Fulton ST
        </h3>
        <h3 class="text-base leading-8 text-gray-400">25700, Chicago, Il</h3>
        <hr class="my-2 border-t-2 border-indigo-100" />
        <div class="flex justify-between text-sm font-normal text-gray-600">
          <div>
            <bed class="inline-block align-top text-gray-600" /> 2 Beds
          </div>
          <div>
            <bath class="inline-block align-top" /> 1 Bathrooms
          </div>
          <div>
            <dimension class="inline-block align-top text-gray-600" /> 2x4.5 m²
          </div>
        </div>
        <div class="
            absolute
            top-7
            right-5
            grid
            h-12
            w-12
            place-items-center
            rounded-full
            border-2 border-indigo-100
          ">
          <coeur />
        </div>
      </div>
    </figcaption>
  </figure>
</template>



<script setup lang="ts">
import coeur from "./icones/coeur.vue";
import bath from "./icones/bath.vue";
import bed from "./icones/bed.vue";
import dimension from "./icones/dimension.vue";
</script>