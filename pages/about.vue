<template>
  <div class="text-container">
      <div class="about-info">
        <h3>Background:</h3>

        <p>Glome Studio are a creative technology collective recently formed out of 'Delta Functions' residency at Thin Air, The Beams.
          A con(glome)rate of talent across many backgrounds, Glome Studio aims to invite audiences into computational creativity through the development
          of participatory, performant digital installations within gallery and commercial contexts.</p>
      </div>
      <div class="resident-list">
        <p>We are: Samuele Albani, Francesco Angelini, Maria Gracia Cebrecos, Daisy Chiu, Arjan Guerrero, Lily Has, Beiqing (Eva) Jiang, Valerie Keck, Devon Kennedy, Robin Leverton, Yiying (Jade) Lin, Owen Planchart, Xinde Ren, David Rollinson, Thomas Rosser, Mary Tallontire, Nate Townsend.</p>
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

.resident-list {
  position: relative;
  top: 200px;
}

.resident-list p {
  color: black;
}

</style>