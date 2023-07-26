<template>
    <div class="navigation">
        <ul><li><nuxt-link to="/">HOME</nuxt-link></li>
            <li><nuxt-link to="/about">ABOUT</nuxt-link></li>
            <li><nuxt-link to="/work">WORK</nuxt-link></li>
            <li><nuxt-link to="/contact">CONTACT</nuxt-link></li></ul>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
.navigation {
    width: 50%;
    font-family: DotGothic;
    position: absolute;
    font-size: medium;
    list-style:none;
    text-align:center;
    color: darkblue;
    margin: 50px;
}

.navigation ul {
    list-style-type: none;
    display: block;
    padding: 0;
}

.navigation li {
    /* display:inline; */
    text-align: left;
    margin: 10px 10px;
}
</style>