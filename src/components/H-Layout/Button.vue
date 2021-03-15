<template>
  <div :class='button'>{{title}}</div>
</template>

<script>
import { defineComponent } from '@vue/composition-api'

export default defineComponent({
  name: 'Button',
  props: {
    title: String, 
  },
  data() {
    return {
      button: 'bg-solid-blue text-white p-2 px-10',
    }
  }
})
</script>
