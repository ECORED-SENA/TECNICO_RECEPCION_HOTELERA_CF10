<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal
      .titulo-principal__numero
        span 7
      h1 <em>Types of Clients</em> / Tipos de Clientes
    
    .row.mb-4
      .col-md-7.mb-4(data-aos="fade-right")
        .row.content-usa.mb-4
          .img-usa
            .div
              img(src='@/assets/curso/bandera-usa.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3
            p 
              italic Each guest is unique, their motivation to travel is specific; therefore, the willingness and attitude of the receptionist is essential to give the quality service that is being sought within the establishment and what each client is paying for.
            p 
              italic Look at the most common types of customers.
        .row.content-esp
          .px-md-5.pt-md-2.pb-md-2.py-2.px-3
            p Cada huésped es único, la motivación de su viaje es específica, por lo que la disposición y actitud del recepcionista es indispensable para dar el servicio de calidad que se espera del establecimiento y por el cual el cliente paga.
            p Observe los tipos de clientes más comunes.
          .img-esp
            .div
              img(src='@/assets/curso/bandera-esp.svg' alt='Bandera ESPAÑA')  
      .col-md-5.mb-4(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema7-img.png', alt='Imagen decorativa')

    TabsF.color-acento-botones.color-naranja
      .row.tarjeta.bg-azul.p-4(titulo="<em>Corporate</em> / Corporativo")
        .col-2
          figure
            img(src='@/assets/curso/tema7-tabs1.svg', alt='Imagen decorativa')
        .col-md-10
          h4 <em>Corporate</em> / Corporativo
          p <em>They are customers who travel for work or business reasons, their stay usually does not exceed one week. They tend to be very demanding with service and are usually less price sensitive.</em>
          .division-acento-contenido
          p Son los clientes que viajan por motivos de trabajo o negocios, su permanencia generalmente no excede una semana. Suelen ser muy exigentes con el servicio, y por lo general son menos sensibles al precio.
      .row.tarjeta.bg-azul.p-4(titulo="<em>Corporate</em> / Corporativo")
        .col-2
          figure
            img(src='@/assets/curso/tema7-tabs1.svg', alt='Imagen decorativa')
        .col-md-10
          h4 <em>Corporate</em> / Corporativo
          p <em>They are customers who travel for work or business reasons, their stay usually does not exceed one week. They tend to be very demanding with service and are usually less price sensitive.</em>
          .division-acento-contenido
          p Son los clientes que viajan



</template>

<script>
import TabsF from '../components/TabsF'
export default {
  name: 'Tema7',
  components: {
    TabsF,
  },
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
