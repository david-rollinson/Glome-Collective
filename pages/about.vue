<template>
  <navigation />
  <div>
    This is the {{ this.$route.name }} page.
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

</style>