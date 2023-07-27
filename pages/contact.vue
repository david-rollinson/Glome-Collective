<template>
    <div class="contact-card">
        <h1>contact: <a href="https://www.instagram.com/delta.functions/" target="blank">@delta.functions</a></h1>
    </div>
  </template>
  
  <script>
  export default {
    created(){
      this.currentRoute;
      //this.nombreRuta = this.$route.name;
  },
  computed:{
  
  }
  }
  
  </script>
  
  <style scoped>

    body {
        /*Declare and initialise variables here.*/
        --font-size: 42px;
        overflow: hidden;
    }

    .contact-card {
        position: absolute;
        text-align: center;
        width:100%;
        top: calc(50% - var(--h1-font-size));
    }
  
  </style>