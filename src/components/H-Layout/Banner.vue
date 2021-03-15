<template>
  <div :class='BannerContainer'>
    <div :class='BannerHeader'>
      <h1>Welcome to Interchain GmbH</h1>
      <p>Building the internet of blockchains</p>
      <div :class='BannerProjectLinks'>
        <!-- <img /> -->
        <p>We are the maintainers of — </p>
        <!-- <img /> Map through project Icons -->
      </div>
    </div>

    <div :class='BannerImage'>
      <!-- <img /> -->
    </div>
  </div>
</template>

<script>
import { defineComponent } from '@vue/composition-api'

export default defineComponent({
  name: 'Banner',
})
</script>
