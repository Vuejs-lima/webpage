<template>
  <section class="bg-main-gray">
    <h2 class="py-16 font-fira text-4xl text-center">Organizadores</h2>
    <div class="grid">
      <img src="~/assets/img/imagen_1.png" alt="" />
      <img src="~/assets/img/imagen_2.png" alt="" />
      <img src="~/assets/img/imagen_3.png" alt="" />
      <img src="~/assets/img/imagen_4.png" alt="" />
      <img src="~/assets/img/imagen_5.png" alt="" />
      <div class="bg-tertiary flex justify-center items-center">
        <h3 class="text-white font-fira text-6xl">Tú</h3>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Organizers'
}
</script>

<style lang="css" scoped>
.grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
}
</style>
