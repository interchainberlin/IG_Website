<template>
  <div :class='UpdateContainer'>
    <!-- <tag /> -->
    <!-- Pull update infrom from Blog DB -->
    <p> ICF Update — March 1st </p>
    <p> Description of newest IG / ICF update </p>
    <!-- <button> Read → </button> -->
  </div>
</template>

<script>
import { defineComponent } from '@vue/composition-api'

export default defineComponent({
  name: 'Updates',
})
</script>