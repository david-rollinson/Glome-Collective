<template>
    <navigation />
    <div class="text-container" style="width:85%;">
        <video width="300" controls>
        <source src="/video/exquisite_horpse.mp4" type="video/mp4">
        Your browser does not support the video tag.
        </video>
        <video width="300" controls>
        <source src="/video/obsessed_with_your_face.mp4" type="video/mp4">
        Your browser does not support the video tag.
        </video>
        <video width="300" controls>
        <source src="/video/binary_dither.mp4" type="video/mp4">
        Your browser does not support the video tag.
        </video>
        <video width="300" controls>
        <source src="/video/art_should_be.mp4" type="video/mp4">
        Your browser does not support the video tag.
        </video>
        <video width="650" controls>
        <source src="/video/rest_is_noise.mp4" type="video/mp4">
        Your browser does not support the video tag.
        </video>
        <video width="650" controls>
        <source src="/video/light_beams.mp4" type="video/mp4">
        Your browser does not support the video tag.
        </video>
        <video width="650" controls>
        <source src="/video/how_long_can_you_sing.mp4" type="video/mp4">
        Your browser does not support the video tag.
        </video>
        <p>More coming soon...</p>
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

  video {
    padding-right: 50px;
    padding-bottom: 50px;
  }

  p {
    position: relative;
    padding-right: 50px;
    padding-bottom: 50px;
  }


  </style>