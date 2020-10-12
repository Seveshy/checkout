<template>

<div class="ck-flex">

    <div>
        <div class="container-cardCredit">

        <article class="ck-wrapper_title">
            <span class="ck-title"> DADOS PESSOAIS </span>
        </article>

        <label>Nome*</label>
        <input class="ck-input" type="text" required>

        <label>Email*</label>
        <input class="ck-input" type="text" required>

    <div class="ck-container_cel">
        <article>
            <label class="ck-validate_txt">CPF*/CNPJ</label>
            <input class="ck-cpf" type="number" required>
        </article>

        <article class="ck-wrapper_phone">
            <label class="ck-cod_txt">Celular com DDD*</label>
            <input class="ck-cel_ddd" type="number" required>
        </article>
    
    </div>

    </div>

    <div class="container-delivery">

        <div class="ck-wrapper_info">
            <article>
                <span class="ck-title"> DADOS DE ENTREGA </span>
            </article>
        </div>

        <label>CEP*</label>
        <input class="ck-cel_ddd" type="number" required>

        <label>Endereço*</label>
        <input class="ck-input" type="text" required>

    <div class="ck-container_cel">
        <article>
            <label class="ck-validate_txt">Numero</label>
            <input class="ck-cpf" type="number" required>
        </article>

        <article class="ck-wrapper_phone">
            <label class="ck-cod_txt">Complemento*</label>
            <input class="ck-cel_ddd" type="text" required>
        </article>
    
    </div>

    <label>Bairro*</label>
    <input class="ck-input" type="text" required>

    <div class="ck-container_cel">
        <article class="ck-wrapper_city">
            <label class="ck-validate_txt">Cidade</label>
            <input class="ck-cpf" type="number" required>
        </article>

        <article class="ck-wrapper_state">
            <label class="ck-cod_txt">Estado*</label>
            <select class="ck-input_state">
                <option value="price-tree">São Paulo</option>
                <option value="price-two">Rio de Janeiro</option>
                <option value="price-one">Minas Gerais</option>
            </select>        
        </article>
    </div>

    </div>
    </div>

    <div class="container-payCard">

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

</div>

   
</template>
<style>

    .container-payCard {
        width: 440px;
        height: 800;
        background-color: #fff;
        border-radius: 6px;
        border: 1px solid #D5D8E6;
        margin-left: 22px;
    }

    .container-cardCredit {
        color: #191D3A;
        width: 624px;
        height: 345px;
        border-radius: 6px;
        border: 1px solid #D5D8E6;
        box-sizing: border-box;
        background: #fff;
        display: flex;
        flex-direction: column; 
        padding: 30px;
    }

     .container-delivery {
        color: #191D3A;
        width: 624px;
        height: 565px;
        border-radius: 6px;
        border: 1px solid #D5D8E6;
        box-sizing: border-box;
        background: #fff;
        display: flex;
        flex-direction: column; 
        padding: 30px;
        margin-top: 14px;
    }

    .ck-wrapper_phone {
        margin-left: 12px;
    }

    .ck-wrapper_state {
        margin-left: 12px;
        display: flex;
        flex-direction: column;
        margin-top: 9px;
    }

    .ck-wrapper_city {
        display: flex;
        flex-direction: column;
    } 

    .ck-wrapper_info {
        display: flex;
        justify-content: space-between;
        margin-bottom: 18px;
    }

    .ck-title {
        font-style: normal;
        font-weight: bold;
        font-size: 16px;
        line-height: 22px;        
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

    label {
        margin: 20px 0px 10px 5px;
        font-weight: bold;
    }

    .ck-container_cel {
        display: flex;
        margin-top: 14px;
    }

    .ck-cel_ddd {
        width: 280px;
        height: 40px;
        padding: 12px;
        border: 1px solid #D5D8E6;
        box-sizing: border-box;
        border-radius: 6px;
        outline: none;
    }

    .ck-cpf {
        width: 270px;
        height: 40px;
        padding: 12px;
        border: 1px solid #D5D8E6;
        box-sizing: border-box;
        border-radius: 6px;
        outline: none;
        margin-top: 12px;
    }

    .ck-input_state {
        width: 270px;
    }

    .ck-flex {
        display: flex;
    }


</style>
<script>


export default {
}
</script>

