<template>

<div>
    <h1>Checkout</h1>
    
    <div class="container">

        <span class="info"> Informações pessoais </span>

        <label>Email*</label>
        <input class="ck-input">

        <label>Name*</label>
        <input class="ck-input">

    <label>Celular*</label>
    <div class="ck-container_cel">
        <input class="ck-cel_ddd">

        <input class="ck-cel_number">
    </div>

    <label>CPF*</label>
    <input class="ck-input">

    </div>
</div>

   
</template>
<style scoped>

    .container {
        color: #191D3A;
        width: 624px;
        height: 396px;
        border-radius: 6px;
        border: 1px solid #D5D8E6;
        box-sizing: border-box;
        background: #fff;
        display: flex;
        flex-direction: column; 
        padding: 30px;
    }

    .info {
        font-weight: bold;
        margin-bottom: 24px;
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



    label {
        margin: 10px 0px 10px 5px;
        font-weight: bold;
    }

    .ck-container_cel {
        display: flex;
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

