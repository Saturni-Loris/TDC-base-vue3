<template>
  <div>
    <nav>
      <h4 class="text-xl">
        <Bars3Icon class="inline-block h-5 w-5 text-blue-500" />
        menu (dans <code class="font-mono">/src/App.vue</code>)
      </h4>
      <ul>
        <li>
          <router-link class="text-red-600 underline" to="/">
            Accueil
          </router-link>
        </li>

        <li>
          <router-link class="text-red-600 underline" to="simple">
            Simple
          </router-link>
        </li>
        <li>
          <router-link class="text-red-600 underline" to="">
            list-supabase
          </router-link>
        </li>
        <li>
          <router-link class="text-red-600 underline" to="">
            list-fetch
          </router-link>
        </li>
        <li>
          <router-link class="text-red-600 underline" to="new">
            New
          </router-link>
        </li>
      </ul>
    </nav>

  </div>

  <!-- Affiche les pages -->
  <router-view class="m-2 border-2 p-2" />
</template>

<script setup lang="ts">
import { Bars3Icon } from '@heroicons/vue/20/solid';
</script>
