<template>
    <div class="p-3 pt-12">
        <FormulaireOffreMaison />
    </div>

    <div class="p-3 pt-12">
        <card v-bind="maison2" />
    </div>
</template>
  
<script setup lang="ts">
import card from '../components/card.vue';
import FormulaireOffreMaison from '../components/FormulaireOffreMaison.vue';

const maison = {
    rue: "Rue des pickpockets",
    prix: "2400 €",
    nbdimensions: "99m²",
    nbbed: "7",
    nbbath: "3",
    ville: "Mulhouse",
    image: "../../public/maisonasma.jpg"
}
const maison2 = {
    rue: "Rue de l'amour infini",
    prix: "54854 €",
    nbdimensions: "49m²",
    nbbed: "5",
    nbbath: "1",
    ville: "Montbéliard "
}
</script>