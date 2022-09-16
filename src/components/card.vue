
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
            {{prix}}
          </h3>
          <h3 class="text-base text-gray-500">/month</h3>
        </div>
        <h3 class="text-2xl font-semibold leading-8 text-gray-900">
          {{ville}}
        </h3>
        <h3 class="text-base leading-8 text-gray-400">
          {{ rue }}
        </h3>
        <hr class="my-2 border-t-2 border-indigo-100" />
        <div class="flex justify-between text-sm font-normal text-gray-600">
          <div>
            <bed class="inline-block align-top text-gray-600" /> {{nbbed}} Beds
          </div>
          <div>
            <bath class="inline-block align-top" /> {{nbbath}} Bathrooms
          </div>
          <div>
            <dimension class="inline-block align-top text-gray-600" /> {{nbdimensions}}
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

defineProps({
  rue: String,
  prix: String,
  nbbath: String,
  nbbed: String,
  nbdimensions: String,
  ville: String,
});
</script>