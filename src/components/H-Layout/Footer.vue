<template>
  <div :class='FooterContainer'>
    <div :class='SocailMedia'>
      <div :class='Discord'>
        <!-- <img /> -->
        <p :class='body'>Be part of the journey</p>
        <p :class='body'>Join our Discord community to shape the future</p>
      </div>
       <div :class='Twitter'>
        <!-- <img /> -->
        <p :class='body'>Stay up to date</p>
        <p :class='body'>Follow @Interchain_io to get the latest updates. </p>
      </div>
    </div>

    <div :class='Info'>
      <div :class='CopyRight'>
        <p :class='body'>© 2021 </p>
        <p :class='body'>Interchain GmbH</p>
      </div>
      <div :class='Contact'>
        <p :class='body'>Questions? Get in touch at</p>
        <p :class='link'>contact@interchain.berlin</p>
      </div>
      <div :class='Newsletter'>
        <!-- Import Newsleter <script/> -->
      </div>
    </div>
  </div>
</template>

<script>
import { defineComponent } from '@vue/composition-api'

export default defineComponent({
  name: 'Footer',
})
</script>