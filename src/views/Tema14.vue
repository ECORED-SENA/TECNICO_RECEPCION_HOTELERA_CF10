<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal
      .titulo-principal__numero
        span 14
      h1 <em> Descriptive adjectives (places) </em> / Adjetivos descriptivos (lugares)
    
    .row.mb-4
      .col-md-7.mb-4(data-aos="fade-right")
        .row.content-usa.mb-4
          .img-usa
            .div
              img(src='@/assets/curso/bandera-usa.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3
            p 
              italic With absolute certainty, within the job at the front desk, you will have to describe a place in the city, guide the guests through streets, neighborhoods, monuments, emblematic buildings, and locate them in the destination. Below you will find some expressions and qualifiers that will help you with your work.
        .row.content-esp
          .px-md-5.pt-md-2.pb-md-2.py-2.px-3
            p Con absoluta seguridad, dentro del trabajo en la recepción, usted tendrá que describir un lugar de la ciudad, guiar a los huéspedes por calles, barrios, monumentos, edificios emblemáticos, y ubicarlos en el destino. A continuación, encontrará algunas expresiones y calificativos que le ayudarán con su trabajo.
          .img-esp
            .div
              img(src='@/assets/curso/bandera-esp.svg' alt='Bandera ESPAÑA')  
      .col-md-5.mb-4(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema14-img.png', alt='Imagen decorativa')


    .row.justify-content-center(data-aos="fade-down")
      .col-md-9
        .tabla-b.tabla-1.color-acento-contenido.borde-tabla-naranja.mb-2
          table  
            thead.tabla-b__header 
              tr
                th  
                  h3.text-white.mb-0 <em>Adjective</em>
                th  
                  h3.text-white.mb-0 <em>Adjetivo</em>  
            tbody
              tr.text-center.fila-blanca
                td <em>amazing</em>
                td.tabla-borde-left asombroso
              tr.text-center.fila-naranja
                td <em>ancient</em>
                td.tabla-borde-left antiguo  
              tr.text-center.fila-blanca
                td <em>beautiful</em>
                td.tabla-borde-left hermoso
              tr.text-center.fila-naranja
                td <em>big</em>
                td.tabla-borde-left grande  
              tr.text-center.fila-blanca
                td <em>boring</em>
                td.tabla-borde-left aburrido
              tr.text-center.fila-naranja
                td <em>breathtaking</em>
                td.tabla-borde-left impresionante  
              tr.text-center.fila-blanca
                td <em>bustling</em>
                td.tabla-borde-left bullicioso
              tr.text-center.fila-naranja
                td <em>busy</em>
                td.tabla-borde-left ocupado  
              tr.text-center.fila-blanca
                td <em>calm</em>
                td.tabla-borde-left calmado
              tr.text-center.fila-naranja
                td <em>cheap</em>
                td.tabla-borde-left barato  
              tr.text-center.fila-blanca
                td <em>crowded</em>
                td.tabla-borde-left concurrido
              tr.text-center.fila-naranja
                td <em>exciting</em>
                td.tabla-borde-left emocionante  
              tr.text-center.fila-blanca
                td <em>expensive</em>
                td.tabla-borde-left caro
              tr.text-center.fila-naranja
                td <em>huge</em>
                td.tabla-borde-left enorme  
              tr.text-center.fila-blanca
                td <em>interesting</em>
                td.tabla-borde-left interesante
              tr.text-center.fila-naranja
                td <em>lively</em>
                td.tabla-borde-left vivo  
              tr.text-center.fila-blanca
                td <em>lovely</em>
                td.tabla-borde-left bonito
              tr.text-center.fila-naranja
                td <em>modern</em>
                td.tabla-borde-left moderno                  
              tr.text-center.fila-blanca
                td <em>polluted</em>
                td.tabla-borde-left contaminado
              tr.text-center.fila-naranja
                td <em>quiet</em>
                td.tabla-borde-left tranquilo  
              tr.text-center.fila-blanca
                td <em>small</em>
                td.tabla-borde-left pequeño
              tr.text-center.fila-naranja
                td <em>unpleasant</em>
                td.tabla-borde-left desagradable  
              tr.text-center.fila-blanca
                td <em>wonderful</em>
                td.tabla-borde-left maravilloso
         


</template>

<script>
export default {
  name: 'Tema14',
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
