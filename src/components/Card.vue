
<template>
    <div class="card">
<img :src="url" :alt="nombre">
<h2>{{nombre}}</h2>
<a :href="url" target="_blank">Visitar</a>
<a :href="url" target="_blank">Descargar</a>

</div>
</template>
<script>
export default {
    props:{
      url:{
      String,
      },
      nombre:{
        String
      }
    }
}
</script>


<style scoped>

.card{
  border-radius:10px;
  border:1px solid blue;
  padding:2rem;
  margin: 1rem;
  text-align: center;
}
img{
  width: 8rem;
  height: 8rem;
}
a{
  background-color: darkcyan;
  color: white;
  padding: 0.2rem 1rem;
  border-radius: 10px;
  margin: 1rem;
}
a:hover{
  background-color: gray;
}

</style>