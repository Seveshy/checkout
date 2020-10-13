<template>

<div>

    <div class="container-card">

        <div class="ck-wrapper_info">
            <article>
                <input type="radio" checked="checked" name="radio">
                <span class="info"> Cartão de Credito </span>
            </article>

            <article>
                <img alt="Vue logo" src="../assets/visa-color.png">
            </article>
        </div>

         <label>Numero do Cartão*</label>
        <input class="ck-input" type="number" required>

        <label>Nome impresso do cartão*</label>
        <input class="ck-input" type="text" required>

    <div class="ck-container_cel">
        <article>
            <label class="ck-validate_txt">Validate*</label>
            <input class="ck-cel_ddd" type="number" required>
        </article>

        <article class="ck-wrapper_cod">
            <label class="ck-cod_txt">Cod Segurança*</label>
            <input class="ck-cel_number" type="number" required>
        </article>
    
    </div>

    <label>Parcelas*</label>

    <select>
        <option value="price-tree">3x de R$ 549*</option>
        <option value="price-two">2x de R$ 1184</option>
        <option value="price-one">1x de R$ 2368</option>
    </select>

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

      <div class="ck-footer">
      
      <button class="ck-btn">Pay Now</button>

        <a href="#">
          <img  class="ck-securety_logo" alt="Vue logo" src="../assets/secure.png">
          Secure Payments
        </a>


        <img alt="Vue logo" src="../assets/footer.png">
      </div>

    </div>
</div>

   
</template>
<style>

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
  height: 52px;
  border-radius: 6px;
  color:#fff;
  font-weight: bold;
  border: none;
  font-size: 16px;
  margin-top: 42px;
  outline: none;
  cursor: pointer;
  margin-bottom: 26px;

}

.ck-footer {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;

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

    .container-card {
        color: #191D3A;
        width: 624px;
        height: 924px;
        border-radius: 6px;
        border: 1px solid #D5D8E6;
        box-sizing: border-box;
        background: #fff;
        display: flex;
        flex-direction: column; 
        padding: 30px;
        margin-left: 14px;
    }

    .ck-wrapper_info {
        display: flex;
        justify-content: space-between;
        margin-bottom: 18px;
    }

    .info {
        font-style: normal;
        font-weight: bold;
        font-size: 16px;
        line-height: 22px;        
        margin-bottom: 24px;
        color: #FD6481; 
    }

    .ck-input {
        width: 560px;
        height: 40px;
        border-radius: 6px;
        border: 1px solid #D5D8E6;
        box-sizing: border-box;
        padding: 12px;
        outline: none;
    }

    select {
        border-radius: 6px;
        border: 1px solid #D5D8E6;
        box-sizing: border-box;
        padding: 12px;
        outline: none;
        background: #fff;
        color: #191D3A;
    }

    .ck-radio {
        width: 16px;
        height: 16px;
        background: #FD6481;
    }




    label {
        margin: 20px 0px 10px 5px;
        font-weight: bold;
    }

    .ck-container_cel {
        display: flex;
        margin-top: 14px;
    }

    .ck-cel_ddd {
        width: 131px;
        height: 40px;
        padding: 12px;
        border: 1px solid #D5D8E6;
        box-sizing: border-box;
        border-radius: 6px;
        outline: none;
    }

    .ck-cel_number {
        width: 270px;
        height: 40px;
        padding: 12px;
        border: 1px solid #D5D8E6;
        box-sizing: border-box;
        border-radius: 6px;
        outline: none;
    }

    .ck-wrapper_cod {
      margin-left: 12px;
    }

    .ck-validate_txt {
        margin-bottom: 12px;
    }

    .ck-cod_txt {
        margin-bottom: 12px;
    }

    

</style>
<script>


export default {
}
</script>

