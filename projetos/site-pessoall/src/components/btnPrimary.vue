<template>
    <button class="btn">{{btnText}}</button>
</template>
<script>
export default {
    props:['btnText']
}
</script>
<style scoped>
.btn{
    margin: 8px;
    text-transform: uppercase;
    font-family: 'Roboto', sans-serif;
    background-color: #F80040;
    border-radius: 32px;
    padding: 8px 16px 8px 16px;
    border: none;
    color: #150941;
    font-weight: bold;
    font-size: 16px;
    transition: all 0.3s ease-in-out;
}
.btn:hover{
    background-color: #c90036;
    color: #fff;
}
</style>