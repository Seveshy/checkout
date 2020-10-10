
<template>

  <div id="app">

      <h1>Checkout</h1>

      <div class="flex">
       <div>
          <Checkout />
          <CreditCar />
          <Boleto />
          <Paypal />
       </div>

      <div>
        <Paymant />
      </div>

      </div>
      


  </div>
</template>

<script>

import Checkout from './components/Checkout'
import Paymant from './components/Paymant'
import CreditCar from './components/CreditCar'
import Boleto from './components/Boleto'
import Paypal from './components/Paypal'

export default {
  components: {
    Checkout,
    Paymant,
    CreditCar,
    Boleto,
    Paypal
  }
}


</script>

<style>
  #app {
    margin-top: 5%;
  }
  body {
    font-family: 'Nunito Sans', sans-serif;
    background: #fff;
    padding: 0;
    width: 1160px;
    margin: 0 auto;
  }

  .flex {
    display: flex;
  }

</style>