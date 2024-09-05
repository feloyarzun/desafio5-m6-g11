<script>
export default {
  name: 'ContactoView',
  methods: {
    volverAlInicio() {
      this.$router.push('/home');
    }
  }
}


</script>

<template>
  <div class="contacto">
    <h1>Contacto</h1>
    <p>Información de contacto.</p>
    <button @click="volverAlInicio" class="btn btn-primary">Volver</button>
  </div>
</template>

<style>
</style>