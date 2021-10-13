<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal
      .titulo-principal__numero
        span 13
      h1 <em>Hours and Schedules</em> / Horas y horarios
    
    .row
      .col-md-7.mb-4(data-aos="fade-right")
        .row.content-usa.mb-4
          .img-usa
            .div
              img(src='@/assets/curso/bandera-usa.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3
            p 
              italic Expressing the hours in English is essential. Knowing how to say the time is not only useful to answer the possible question “What time is it?” made by a guest, but it will also help you inform about schedules of events, attractions, services, and transportation (trains, planes, buses).
        .row.content-esp
          .px-md-5.pt-md-2.pb-md-2.py-2.px-3
            p Expresar las horas en inglés es fundamental. Saber cómo decir la hora no es solo útil para responder a la eventual pregunta “¿Qué hora es?” hecha por un huésped, sino que además le ayudará a informar acerca de horarios de eventos, atracciones, servicios y medios de transporte (trenes, aviones, buses).
          .img-esp
            .div
              img(src='@/assets/curso/bandera-esp.svg' alt='Bandera ESPAÑA')  
      .col-md-5.mb-4(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema13-img.png', alt='Imagen decorativa')



</template>

<script>
export default {
  name: 'Tema13',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass" scoped></style>
