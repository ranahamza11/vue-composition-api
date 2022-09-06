<script setup>
import {useFlash} from "@/composables/useFlash";
let { flash } = useFlash();
</script>

<template>
  <div>
    <p>
      <button @click="flash('salam','it works on the about page')">Click Me</button>
    </p>
  </div>
</template>


