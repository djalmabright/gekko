<template lang='jade'>
  footer.p2.bg--off-white
    .contain
      p
        em Use Web Coins at your own risk.
      p Using Web Coins v{{ version.gekko }} and Web Coins UI v{{ version.ui }}.
</template>

<script>
const gekkoPackage = require('../../../../../package.json');
const uiPackage = require('../../../package.json');

export default {
  data: () => {
    return {
      version: {
        gekko: gekkoPackage.version,
        ui: uiPackage.version
      }
    }
  }
}
</script>
