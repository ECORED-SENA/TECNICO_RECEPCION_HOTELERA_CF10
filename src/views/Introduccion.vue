<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    .row
      .col-md-7.mb-4(data-aos="fade-right")
        .row.content-usa.mb-4
          .img-usa
            .div
              img(src='@/assets/curso/bandera-usa.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3
            p 
              italic This module will continue with the development of communicative skills in English.
            p 
              italic During the process, you will strengthen the knowledge of hotel technical vocabulary, consolidate mid-level structures, and be located into the language context which will allow you to have more fluid communication to have a better performance in the work environment of the front desk
        .row.content-esp
          .px-md-5.pt-md-2.pb-md-2.py-2.px-3
            p En este módulo, se continuará con el desarrollo de habilidades comunicativas en lengua inglesa.  
            p Durante el proceso, usted afianzará el conocimiento de vocabulario técnico hotelero, consolidará estructuras de nivel medio y se ubicará en el contexto idiomático, lo que le permitirá tener una comunicación más fluida para desenvolverse mejor en el ámbito laboral de la recepción.
          .img-esp
            .div
              img(src='@/assets/curso/bandera-esp.svg' alt='Bandera ESPAÑA')  
      .col-md-5.mb-4(data-aos="fade-left")
        figure
          img(src='@/assets/curso/intro-img.jpg', alt='Imagen decorativa')



</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped>
.introduccion
</style>
