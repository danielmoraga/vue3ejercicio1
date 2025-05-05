<template>
  <div class="container">
    <h1>componentes</h1>
    <Grid>
          <Card url="https://cdn.svgporn.com/logos/vue.svg?response-content-disposition=attachment%3Bfilename%3Dvue.svg" nombre="Vue.js"></Card>
          <Card url="https://cdn.svgporn.com/logos/vueuse.svg?response-content-disposition=attachment%3Bfilename%3Dvueuse.svg" nombre="VueUse.js"></Card>
          <Card url="https://cdn.svgporn.com/logos/react.svg?response-content-disposition=attachment%3Bfilename%3Dreact.svg" nombre="React.js"></Card>
          <Card url="https://cdn.svgporn.com/logos/angular-icon.svg?response-content-disposition=attachment%3Bfilename%3Dangular-icon.svg" nombre="Angular.js"></Card>
    </Grid>
  </div>
</template>
<script>
import Card  from "./components/Card.vue"
import Grid from "./components/Grid.vue";
export default {
  components:{Card, Grid},
}
</script>

<style scoped>

h1{
  text-align: center;
}
.container{
  margin: 0 auto;
  max-width: 1920px;
}

</style>

