<template lang="pug">
  div
    header-main
    slot
    footer-main
</template>
<script>
import HeaderMain from "../headerMain";
import FooterMain from "../footerMain";

export default {
  components: {FooterMain, HeaderMain}
}
</script>
