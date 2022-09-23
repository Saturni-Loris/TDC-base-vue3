<script setup>

import { supabase } from "../supabase";
import card from "../components/card";

console.log("supabase :", supabase); // pour vérifier et "garder" supabase dans le code

const maisons = []; // à remplacer par l'appel à Supabase


</script>

<template>
  <div v-for="maison of maisons" class="p-3 pt-12">
    <card v-bind="maison" />
    <div>
      <h1>aaa</h1>
    </div>
  </div>
</template>
