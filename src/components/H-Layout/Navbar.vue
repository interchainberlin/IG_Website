<template>
  <div :class='NavbarContainer'>
    <div :class='IGNav'>
      <div :class='Company'>
        <!-- <img /> -->
        <p :class='header'>Interchain GmbH</p>
      </div>
      <div :class='Menu'>
        <!-- <button>Job</button> -->
        <p :class='subheader'>Team</p>
      </div>
    </div>

    <div :class='ICFBanner'>
      <p :class='subheader'>Interchain Foundation Our Grant Program →</p>
    </div>
  </div>
</template>

<script>
import { defineComponent } from '@vue/composition-api'

export default defineComponent({
  name: 'Navbar',
  data() {
    return {
      NavbarContainer: 'w-full border-2 border-red-500',
      header: 'text-white',
      subheader: 'text-white',

      IGNav: 'bg-gray-800 flex flex-wrap justify-between p-2 pl-9 pr-9',
      Company: '',
      Menu: '',
      ICFBanner: 'bg-black pl-9',


    }
  }
})
</script>