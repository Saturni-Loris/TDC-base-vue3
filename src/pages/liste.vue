<template>
    <div v-for="maison of maisons" class="p-3 pt-12">
        <card v-bind="maison" />
    </div>
</template>
  
<script setup lang="ts">
import card from '../components/card.vue';

import maisons from "../assets/maisons.json";



// const maisons = [{
//     rue: "Rue des pickpockets",
//     prix: "2400 €",
//     nbdimensions: "99m²",
//     nbbed: "7",
//     nbbath: "3",
//     ville: "Mulhouse",
// }, {
//     rue: "Rue de l'amour infini",
//     prix: "54854 €",
//     nbdimensions: "49m²",
//     nbbed: "5",
//     nbbath: "1",
//     ville: "Montbéliard ",
// }]
</script>