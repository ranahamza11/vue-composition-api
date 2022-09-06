<script setup>
// import flash from "@/mixins/flash";
import {useFlash} from "@/composables/useFlash";
let { flash } = useFlash();


</script>

<template>
  <main>
    <p>
      <button @click="flash('test','it works', 'info')">Click Me</button>
    </p>

  </main>
</template>
