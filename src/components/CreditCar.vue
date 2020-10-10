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
        <input class="ck-input">

        <label>Nome impresso do cartão*</label>
        <input class="ck-input">

    <div class="ck-container_cel">
        <article>
            <label>Validate*</label>
            <input class="ck-cel_ddd">
        </article>

        <article>
            <label>Cod Segurança*</label>
            <input class="ck-cel_number">
        </article>
    
    </div>

    <label>Parcelas*</label>

    <select>
        <option value="price-tree">3x de R$ 549*</option>
        <option value="price-two">2x de R$ 1184</option>
        <option value="price-one">1x de R$ 2368</option>
    </select>

    </div>
</div>

   
</template>
<style scoped>

    .container-card {
        color: #191D3A;
        width: 624px;
        height: 450px;
        border-radius: 6px;
        border: 1px solid #D5D8E6;
        box-sizing: border-box;
        background: #fff;
        display: flex;
        flex-direction: column; 
        padding: 30px;
        margin-top: 14px;
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
        width: 413px;
        height: 40px;
        padding: 12px;
        border: 1px solid #D5D8E6;
        box-sizing: border-box;
        border-radius: 6px;
        margin-left: 12px;
        outline: none;
    }

    

</style>
<script>


export default {
}
</script>

