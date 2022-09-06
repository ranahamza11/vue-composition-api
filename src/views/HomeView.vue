<script setup>
import { ref, watch } from "vue";
import {useStorage} from "@/composables/useStorage";

let food = useStorage('food', 'salad');
let age = useStorage('age', 14);

</script>

<template>
  <main>
    <p>
      what is your favorite food <input type="text" v-model="food"/>
    </p>

    <p>
      How old are you? <input type="text" v-model="age"/>
    </p>

  </main>
</template>
