<script setup>

import { supabase } from "../supabase";

console.log("supabase :", supabase); // pour vérifier et "garder" supabase dans le code

const maisons = []; // à remplacer par l'appel à Supabase


</script>

<template>
  <div v-for="maison of maisons" class="p-3 pt-12">
    <card v-bind="maison" />
  </div>
</template>
