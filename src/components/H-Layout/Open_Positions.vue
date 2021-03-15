<template>
  <div :class='OpenPositionsContainer'>
    <div>
      <h3 :class='header'> We are hiring </h3>
      <hr/>
      <p :class='body'> All of our work is open source, and we code primarily in Go. We design protocols and architect systems, while working closely with a variety of external contributors and users from around the world. If you like working with distributed systems, databases, blockchain protocols, or cryptography, we think you might like working with us!

      We value professionalism, kindness, experience and curiosity. We work hard to communicate clearly and with empathy, and our team has a knack for building stable distributed systems while also finding new ways to integrate cutting-edge technologies. We are an engineering-driven culture: All of our work is open source, and we limit our meetings so that our team can focus on building great systems.

      Our team is multicultural and values diversity, and we make decisions in a collaborative and transparent way. We’re a small team, growing quickly, positioned in the center of one of the largest and most promising blockchain ecosystems. We are a non-profit, and in some ways, we resemble a collective more than a traditional software startup. But we’re not too crunchy: Because our software helps secure billions of dollars in value, we’re able to offer salaries that are competitive in a global market, along with a variety of other benefits and perks.</p>
    </div>
    <div>
      <!-- <img /> -->
      <!-- Map through open roles from OpenPositions DB -->
    </div>
  </div>
</template>

<script>
import { defineComponent } from '@vue/composition-api'

export default defineComponent({
  name: 'OpenPositions',
})
</script>