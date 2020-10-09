
<template>

  <div id="app">
      <div class="flex">
        <Checkout />
        <Paymant />
      </div>
  </div>
</template>

<script>

import Checkout from './components/Checkout'
import Paymant from './components/Paymant'

export default {
  components: {
    Checkout,
    Paymant
  }
}


</script>

<style>
  
  body {
    font-family: 'Nunito Sans', sans-serif;
    background: #E5E5E5;
    margin: 0;
    padding: 0;
    width: 1160px;
    margin: 0 auto;
  }

  .flex {
    display: flex;
  }

</style>