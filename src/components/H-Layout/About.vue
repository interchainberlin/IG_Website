<template>
  <div :class='AboutContainer'>
    <div>
      <h3 :class='header'> At Interchain GmbH, </h3>
      <hr/>
      <p :class='body'> We are responsible for stewarding some of the most foundational infrastructure for blockchain ecosystems. Our work helps secure billions of dollars in value across a variety of major blockchain projects, including Cosmos, and we are pioneering new protocols for interoperability across the entire blockchain ecosystem. Our vision is to create a new interconnected ecosystem, a new internet of blockchains: The Interchain.</p>
    </div>
    <div>
      <p :class='body'>Our products include Tendermint Core, a groundbreaking, Byzantine-fault tolerant consensus protocol; the Inter Blockchain Communication protocol, a reliable, ordered, authenticated cross-ledger data transport protocol; and Gaia, the software that powers the Cosmos Hub.</p>
    </div>
  </div>
</template>

<script>
import { defineComponent } from '@vue/composition-api'

export default defineComponent({
  name: 'About',
})
</script>