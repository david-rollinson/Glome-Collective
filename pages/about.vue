<template>
  <navigation />
  <div>
  <div class="text-container">
      <div class="about-info">
        <p>Glome Studio are a creative technology collective recently formed out of 'Delta Functions' residency at Thin Air, The Beams.
          A con(glome)rate of talent across many backgrounds, Glome Studio aims to invite audiences into computational creativity through the development
          of participatory, performant digital installations within gallery and commercial contexts.
        </p>
      </div>
  </div>
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

.text-container.about-info{
  /* text-align: center; */
}

</style>