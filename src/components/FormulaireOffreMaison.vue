<script setup lang="ts">
import { ref } from "@vue/reactivity";
const maison = ref({});
</script>

<template>
    <div>
        <div class="p-2">
            <h2 class="text-2xl">Formulaire</h2>
            <FicheOffreMaison v-bind="maison" />
        </div>
        <div class="p-2 text-green-600">
            <!-- On passe la "ref" à FormKit -->
            <FormKit type="form" v-model="maison">
                <FormKit class="" name="Nom" label="nom" />
                <hr>
                <FormKit name="prix" label="Prix" type="number" />
                <hr>
                <FormKit name="favori" label="" type="checkbox" />
            </FormKit>
        </div>
    </div>
</template>
