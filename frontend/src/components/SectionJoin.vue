<template lang="pug">
.section
  .section-header
    h1 Don't have a testnet address?
    p There are two ways to generate an address. The first one is, by using Color Wallet and second one is, by using command-line-interface (colorcli) of Color-SDK.
  .section-main
    btn(type="anchor" href="https://rnssolution.github.io/colorprojectdocs/joinTestNet/" value="Join the latest testnet" size="lg" target="_blank" icon="wifi_tethering")
</template>

<script>
import Btn from "@nylira/vue-button";
export default {
  name: "section-join",
  components: {
    Btn
  }
};
</script>
