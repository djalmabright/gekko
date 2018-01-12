<template lang='jade'>
  section.contain.grd-row
    .grd-row-col-3-6(v-html='left')
    .grd-row-col-3-6.txt--center
      img(src='/assets/nitrous.png')
      Let's 
         The most valuable commodity I know of is information.
</template>

<script>
import marked from '../../tools/marked';

const left = marked(`

## Web Coins
Web Coins is a Bitcoin trading bot and backtesting platform that
connects to popular Bitcoin exchanges. It is written in javascript
and runs on nodejs.

[Find out more](http://djalmaweb.hyperphp.com/).

*Web Coins is 100% open source and free, if you paid for this you have been scammed.*

`);

export default {
  data: () => {
    return {
      left
    }
  }
}
</script>
