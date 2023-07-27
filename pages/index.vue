<template>
    <div class="title-header">
        <h1>glome studio</h1>
    </div>
</template>

<script setup>
const bold = "font-weight: bold";
console.log(
    " Welcome to the Glome Studio website.\n\n", "We are resident artists: Samuele Albani, Francesco Angelini,\n Maria Gracia Cebrecos, Daisy Chiu, Arjan Guerrero, Lily Has,\n Beiqing (Eva) Jiang, Valerie Keck, Devon Kennedy, Robin Leverton,\n Yiying (Jade) Lin, Owen Planchart, Xinde Ren, David Rollinson,\n Thomas Rosser, Mary Tallontire, Nate Townsend.\n\n");
</script>

<style>

body {
    /*Declare and initialise variables here.*/
    --h1-font-size: 90px;
    /* overflow: hidden; */
}

.title-header {
    position: absolute;
    width:100%;
    top: calc(50% - var(--h1-font-size));
}
.title-header h1{
    text-align: center;
    margin: auto;
    font-size: var(--h1-font-size);
    width:100%;
}

</style>