<template>
  <div :class='TeamContainer'>
     <h3 :class='header'> Meet Our Team </h3>
     <!-- Map through Team DB -->
     <button>Join our Team →</button>
  </div>
</template>

<script>
import { defineComponent } from '@vue/composition-api'

export default defineComponent({
  name: 'Team',
})
</script>