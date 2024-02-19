<template>
  <div>

    <h1>Hello World
    <h3>Info : {{ info }}</h3>
    </h1>

    <p>{{ Nombre }}</p>
    <p>{{ Matricula }}</p>
    <p>{{ Grupo }}</p>
    <img :src="require('@/assets/Perro.jpg')"/>
  </div>

</template>

<script>
  export default {
    data () {
      return {
        info: "",
        Nombre: "Luis Avila Lopez",
        Matricula: "20966",
        Grupo: "5A"
      }
    }
  }
</script>