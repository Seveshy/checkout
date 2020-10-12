<template>
  <div class="container-pay">
    <article class="ck-wrapper">
      
      <img alt="Vue logo" src="../assets/flag-of-brazil.png">

    </article>

  <div class="main">
    <span class="ck-order"> Order Summary </span>

   <div class="ck-card">
      <article class="ck-card-info">
        <span> Product </span>
        <span> Paymant </span>
        <span> Pay with </span>
      </article>

    <article class="ck-card_price">
      <span> Webinar Control </span>
      <span> OU EM 12 X DE R$ 17,96* </span>
      <span> Credit Card </span>      
    </article>
  </div>

    <hr class="ck-hr" />

      <article class="ck-overall">
        <span class="ck-overall_txt"> Total: </span>
        <span class="ck-price_txt"> $250.00 </span>
      </article>

    <button class="ck-btn">Pay Now</button>
  <div class="ck-footer">
   
      <a href="#"> 
        <img  class="ck-securety_logo" alt="Vue logo" src="../assets/secure.png">
        Secure Payments
      </a>


    <img alt="Vue logo" src="../assets/footer.png">
  </div>
  </div>

  </div>
   
</template>

<script>



export default {
    
}
</script>
<style>
  .container-pay {
    width: 440px;
    height: 962px;
    background-color: #fff;
    border-radius: 6px;
    border: 1px solid #D5D8E6;
    margin-left: 22px;

  }

  .main {
    width: 360px;
    margin: 0 auto;
  }

  .ck-order {
      font-weight: bold;
      color: #191D3A;
      margin-top: 30px;
      font-style: normal;
      font-size: 20px;
      line-height: 27px;
  }

  .ck-wrapper {
    background-color: #FD6481;
    height: 296px;
    margin-bottom: 32px;
    display: flex;
    justify-content: center;
    align-items: center;

    
  }


  .ck-card {
    display: flex;
    justify-content: space-between;
    font-style: normal;
    font-weight: 600;
    font-size: 14px;
    line-height: 19px;
  }

  .ck-card-info {
    color: #989AB3;
    font-style: normal;
    font-weight: 600;
    font-size: 14px;
    line-height: 19px;
    display: flex;
    flex-direction: column;
  }

  span {
    margin-top: 32px
  }

  .ck-card_price {
    color: #191D3A;
    font-size: 14px;
    display: flex;
    flex-direction: column;
    font-weight: 300;
  }

  .ck-overall {
    display: flex;
    justify-content: space-between;
  }

  .ck-overall_txt {
    font-weight: bold;
    font-size: 18px;
  }

  .ck-price_txt {
    color: #FD6481;
    font-weight: bold;
    font-size: 28px;
  }

  .ck-btn {
    background: #FD6481;
    width: 360px;
    height: 56px;
    border-radius: 6px;
    color:#fff;
    font-weight: bold;
    border: none;
    font-size: 16px;
    margin-top: 42px;
    outline: none;
    cursor: pointer;
  }

  .ck-footer {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    margin-top: 32px;
    
  }

  a {
    color: #989AB3;
    font-size: 14px;
    line-height: 19px;
    text-decoration: none;
    margin-bottom: 32px;
  }

  .ck-securety_logo {
    margin: 5px 5px -2px 0px;
  }

  .ck-hr {
    margin-top: 15%;
  }

</style>