<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal
      .titulo-principal__numero
        span 1
      h1 
        italic Rates 
        | / Tarifas

    .row
      .col-md-7.mb-4(data-aos="fade-right")
        .row.content-usa.mb-4
          .img-usa
            .div
              img(src='@/assets/curso/bandera-usa.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3
            p 
              italic It is the value paid by hotel users in exchange for the product or service they use. The rates are composed of the price and other additional concepts and are governed by the supply and demand game in the touristic market. Hotels have various types of rates depending on the market segment they are targeting. Look at some of them.
        .row.content-esp
          .px-md-5.pt-md-2.pb-md-2.py-2.px-3
            p Es el valor que pagan los usuarios del hotel a cambio del producto o servicio que utilizan. Las tarifas se componen del precio y otros conceptos adicionales, y se rigen por el juego de la oferta y la demanda en el mercado turístico. Los hoteles tienen varios tipos de tarifas dependiendo del segmento de mercado al que se dirigen. Observe algunas de ellas.
          .img-esp
            .div
              img(src='@/assets/curso/bandera-esp.svg' alt='Bandera ESPAÑA')  
      .col-md-5.mb-4(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema1-img1.png', alt='Imagen decorativa')    
   
    AcordeonB.mb-4(tipo="a" clase-tarjeta="tarjeta bg-naranja-suave")
      .row(titulo="1.1 <em>Rack Rate</em> / Tarifa <em>Rack</em>")
        .col-md-2
          img.px-md-4(src='@/assets/curso/tema1-acord1.svg', alt='Imagen decorativa') 
        .col-md-10
          p 
            italic It is the official rate charged by the hotel, to which no discount applies. It serves as a reference for rate management.
          .division-acento-contenido  
          p Es la tarifa oficial que cobra el hotel, a la cual no se aplica ningún descuento. Sirve de referencia para el manejo de tarifas.   
      .row(titulo="1.2 <em>Net or Floor Rate</em> / Tarifa Neta o de Piso")
        .col-md-2
          img.px-md-3(src='@/assets/curso/tema1-acord2.svg', alt='Imagen decorativa') 
        .col-md-10
          p 
            italic This is the fee that is assigned to intermediaries, such as travel agencies, bed banks and marketing platforms, on which they can generate their profit or mark-up.
          .division-acento-contenido  
          p Esta es la tarifa que se asigna a intermediarios como agencias de viaje, bancos de camas y plataformas de marketing, sobre la cual ellos pueden generar su utilidad o sobreprecio. 
  

    .h4.subtitulo-naranja.mb-4(data-aos="fade-right") 
      span 
        italic Meal Plans / 
        | Planes de alimentación



</template>

<script>
import AcordeonB from '../components/AcordeonB'
export default {
  name: 'Tema1',
  components: {
    AcordeonB,
  },
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
