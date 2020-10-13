
<template>

  <div id="app">


     <!-- Descomente aqui !-->
      
      <!-- 
      
      <h1>Checkout</h1>

         <div class="flex">
       <div>
          <Checkout />
          <CreditCheckout />
          <Boleto />
          <Paypal />
       </div>

      <div>
        <Paymant />
      </div>

      </div>
        
      !-->

  <CreditCheckout />

  </div>
</template>

<script>

// import Checkout from './components/Checkout'
// import Paymant from './components/Paymant'
//import CreditCar from './components/CreditCar'
// import Boleto from './components/Boleto'
// import Paypal from './components/Paypal'
import CreditCheckout from './components/CreditCheckout'

export default {
  components: {
    // Checkout,
    // Paymant,
   // CreditCar,
   //  Boleto,
   //  Paypal,
    CreditCheckout
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