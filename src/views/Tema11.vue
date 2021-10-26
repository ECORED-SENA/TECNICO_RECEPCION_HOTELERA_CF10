<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal
      .titulo-principal__numero
        span 11
      h1 <em>Seasons</em> / Estaciones
    
    .row.mb-4
      .col-md-7.mb-4(data-aos="fade-right")
        .row.content-usa.mb-4
          .img-usa
            .div
              img(src='@/assets/curso/bandera-usa.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3
            p 
              italic In this section, you will study two topics that are related and that you should know: meteorological season and touristic seasons.
        .row.content-esp
          .px-md-5.pt-md-2.pb-md-2.py-2.px-3
            p En esta sección, se hará referencia a dos temas que están relacionados y que se deben conocer: temporada meteorológica y temporadas turísticas.
          .img-esp
            .div
              img(src='@/assets/curso/bandera-esp.svg' alt='Bandera ESPAÑA')  
      .col-md-5.mb-4(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema11-img.png', alt='Imagen decorativa')

    .h4.subtitulo-naranja(data-aos="fade-right") 
      span 
        italic Seasons / 
        | Estaciones climáticas

    .row.mb-5
      .col-md-6.g-5.h-100
        .row.content-usa3.bg-naranja-suave.h-100
          .img-usa
            div.position3
              img(src='@/assets/curso/bandera-usa.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3 
            p <em>Colombia, being a tropical country, has no seasons. However, in the tourism sector, it is important to know them, since they in themselves mark flows of travelers. </em>
            p <em>The seasons are defined based on four astronomical events known as solstices and equinoxes. On our planet, each of these four periods lasts 91 days on average. The solstices occur in the months of June and December, and the equinoxes occur in March and September. </em>
            p <em>The date of each one is not exact, but they usually occur between the 20th and 23rd of those months. The seasons in the North Hemisphere are the following. Remember that in the South Hemisphere the seasons are opposite to the north. </em>
      .col-md-6.g-5.h-100
        .row.content-esp3.bg-azul.h-100
          .img-esp3
            div.position3
              img(src='@/assets/curso/bandera-esp.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3
            p Colombia, al ser un país tropical, no tiene estaciones. Sin embargo, en el sector turístico, es importante conocerlas, ya que en sí mismas marcan flujos de viajeros. 
            p Las estaciones se definen con base en cuatro eventos astronómicos conocidos como solsticios y equinoccios. En este planeta, cada uno de estos cuatro períodos dura, en promedio, 91 días. Los solsticios ocurren en los meses de junio y diciembre, y los equinoccios ocurren en marzo y septiembre.
            p La fecha de cada uno no es exacta, pero suelen ocurrir entre el 20 y el 23 de esos meses. Las estaciones en el hemisferio norte son las siguientes. Recuerde que en el hemisferio sur las estaciones son opuestas al norte.

    .row.mb-5
      .col-md-6.mb-4
        .content  
          .content-overlay
          img(src="@/assets/curso/tema11-hover1.svg", alt="Summer / Verano") 
          .tarjeta-details.fadeIn-top.text-center.p-1
            h4 Summer / Verano
            p 
              italic-strong It begins on the June solstice, also known as the summer solstice.
            p Comienza en el solsticio de junio, también conocido como solsticio de verano.  
      .col-md-6.mb-4
        .content(@mouseover="mostrarIndicador = false")
          .indicador--click(v-if="mostrarIndicador")  
          .content-overlay
          img(src="@/assets/curso/tema11-hover2.svg", alt="Autumn /Otoño") 
          .tarjeta-details.fadeIn-top.text-center.p-1
            h4 Autumn / Otoño
            p 
              italic-strong It begins at the September equinox, at the end of summer.
            p Comienza en el equinoccio de septiembre, al final del verano.
      .col-md-6.mb-4
        .content  
          .content-overlay
          img(src="@/assets/curso/tema11-hover3.svg", alt="Winter / invierno") 
          .tarjeta-details.fadeIn-top.text-center.p-1
            h4 Winter / invierno
            p 
              italic-strong It begins at the December solstice, when autumn ends.
            p Comienza en el solsticio de diciembre, cuando termina el otoño.
      .col-md-6.mb-4
        .content  
          .content-overlay
          img(src="@/assets/curso/tema11-hover4.svg", alt="Spring / Primavera") 
          .tarjeta-details.fadeIn-top.text-center.p-1
            h4 Spring / Primavera
            p 
              italic-strong It begins at the March equinox, marking the end of winter.
            p Comienza en el equinoccio de marzo, marca el final del invierno.



    .h4.subtitulo-naranja.mb-4(data-aos="fade-right") 
      span 
        italic Touristic seasons / 
        | Temporadas turísticas

    .row.justify-content-center.mb-3
      .col-md-5.mx-1.p-4.px-md-5.border-naranja.bg-azul.mb-3(data-aos="fade-down") 
        .row.content-usa2.mb-4
          .img-usa
            .div.position2
              img(src='@/assets/curso/bandera-usa.svg' alt='Bandera USA')
        p <em>On the other hand, there are tourist seasons, these are related to the holiday periods in which the flow of travelers usually rises. People typically talk about high and low seasons, but this depends on the destination so that the high season in one destination can be the low of another.</em>      
        p <em>Generally, in Colombia, the following are considered.</em>
        h4 
          italic High season:
        ul.lista-ul--color
          li.mb-1
            i.fas.fa-atom
            italic Easter.
          li.mb-1 
            i.fas.fa-atom
            italic Mid-year school holidays.
          li.mb-1 
            i.fas.fa-atom
            italic Recess week.
          li.mb-1 
            i.fas.fa-atom
            italic End-of-year school holidays.
          li.mb-1 
            i.fas.fa-atom
            italic Holiday weekends.
        p 
          italic-strong Consequently, the low season would be the opposite periods. This example applies to destinations with a pure tourist vocation.
      .col-md-5.mx-1.p-4.px-md-5.border-naranja.bg-azul.mb-3(data-aos="fade-left")
        .row.content-esp2.mb-4
          .img-esp
            .div.position2
              img(src='@/assets/curso/bandera-esp.svg' alt='Bandera ESPAÑA')  
        p Por otro lado, hay temporadas turísticas, estas están relacionadas con los periodos vacacionales en los que suele subir el flujo de viajeros. Normalmente, se habla de temporada alta y baja, pero esto depende del destino, por lo que la temporada alta en un destino puede ser la baja de otro.
        p Generalmente, en Colombia, se considera lo siguiente.
        h4 Temporada alta:
        ul.lista-ul--color
          li.mb-1
            i.fas.fa-atom
            | Semana Santa.
          li.mb-1 
            i.fas.fa-atom
            | Vacaciones escolares de mitad de año.
          li.mb-1 
            i.fas.fa-atom
            | Semana de receso.
          li.mb-1 
            i.fas.fa-atom
            | Vacaciones escolares de fin de año.
          li.mb-1 
            i.fas.fa-atom
            | Fines de semana con días festivos.  
        p 
          strong En consecuencia, la baja temporada, serían los períodos opuestos. Este ejemplo es aplicable solo a destinos con vocación puramente turística.


</template>

<script>
export default {
  name: 'Tema11',
  data: () => ({
    mostrarIndicador: true,
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
