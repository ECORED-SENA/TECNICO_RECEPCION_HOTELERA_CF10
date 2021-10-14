<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal
      .titulo-principal__numero
        span 8
      h1 <em>Accommodation</em> / Alojamiento
    
    .row.mb-4
      .col-md-7.mb-4(data-aos="fade-right")
        .row.content-usa.mb-4
          .img-usa
            .div
              img(src='@/assets/curso/bandera-usa.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3
            p 
              italic In the hotel industry, accommodation refers to the type of rooms and beds that lodging properties have. You are going to learn what types are these.
        .row.content-esp
          .px-md-5.pt-md-2.pb-md-2.py-2.px-3
            p En la industria hotelera, el alojamiento se refiere al tipo de habitaciones y camas que tienen las propiedades de hospedaje. A continuación, aprenderá cuáles son estos tipos.
          .img-esp
            .div
              img(src='@/assets/curso/bandera-esp.svg' alt='Bandera ESPAÑA')  
      .col-md-5.mb-4(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema8-img.png', alt='Imagen decorativa')


    .row.justify-content-center(data-aos="fade-down")
      .col-md-10
        .tabla-b.tabla-1.color-acento-contenido.borde-tabla-naranja.mb-5(data-aos="fade-down")
          table  
            thead.tabla-b__header 
              tr
                th  
                  h3.text-white.mb-0 <em>Bed types</em> 
                th  
                  h3.text-white.mb-0 <em>Tipos de camas</em>  
                th  
                  h3.text-white.mb-0 <em>Measurements</em> / Medidas    
            tbody
              tr.text-center.fila-blanca
                td <em>single bed</em>
                td cama sencilla
                td 1.00 mts x 1.90 mts
              tr.text-center.fila-naranja
                td <em>semi-double bed</em>
                td cama semidoble
                td 1.20 mts x 1.90 mts
              tr.text-center.fila-blanca
                td <em>full-size bed</em>
                td cama doble o matrimonial
                td 1.40 mts x 1.90 mts
              tr.text-center.fila-naranja
                td <em>queen-size bed </em>
                td cama <em>queen</em>
                td 1.80 mts x 1.90 mts 
              tr.text-center.fila-blanca
                td <em>king-size bed</em>
                td cama <em>king</em>
                td 2.00 mts x 2.00 mts

    .row.justify-content-center(data-aos="fade-down")
      .col-md-10.bg-azul.mb-2.py-4
        h3.text-center <em>Bed types</em>
        TabsE.color-amarillo.color-acento-botones.px-md-5
          .tarjeta.p-4(titulo="<em>Single bed</em> / Cama sencilla")
            figure
              img(src='@/assets/curso/tema8-tabs1.svg', alt='Imagen decorativa')
          .tarjeta.p-4(titulo="<em>Semi-double bed</em> / Cama Semidoble")
            figure
              img(src='@/assets/curso/tema8-tabs2.svg', alt='Imagen decorativa')  
          .tarjeta.p-4(titulo="<em>Full-size bed</em> / Cama doble o matrimonial")
            figure
              img(src='@/assets/curso/tema8-tabs3.svg', alt='Imagen decorativa') 
          .tarjeta.p-4(titulo="<em>Queen-size bed </em> / Cama <em>Queen</em>")
            figure
              img(src='@/assets/curso/tema8-tabs4.svg', alt='Imagen decorativa')   
          .tarjeta.p-4(titulo="<em>King-size bed</em> / Cama <em>King</em>")
            figure
              img(src='@/assets/curso/tema8-tabs5.svg', alt='Imagen decorativa')              
      .col-md-10.mb-5
        figcaption Fuente de imagen: Carpeta Anexos / CF_10 - Bed Types


    .h4.subtitulo-naranja.mb-5(data-aos="fade-right") 
      span 
        italic Room Types / 
        | Tipos de Habitación 

    .row.mb-4
      .col-md-6.border-bottom.px-4
        ul.lista-ul--color
          li.mb-1
            i.fas.fa-atom
            p 
              italic <b>Single room:</b> Room for one person, usually with a single or semi-double bed.
      .col-md-6.border-bottom.px-4 
        ul.lista-ul--color
          li.mb-1
            i.fas.fa-atom
            p <b>Habitación individual:</b> Habitación para una persona, generalmente con cama sencilla o semidoble.
    
    .row.mb-4
      .col-md-6.border-bottom.px-4
        ul.lista-ul--color
          li.mb-1
            i.fas.fa-atom
            p 
              italic <b>Double room:</b> Room for two guests, has a double or a queen bed.
      .col-md-6.border-bottom.px-4 
        ul.lista-ul--color
          li.mb-1
            i.fas.fa-atom
            p <b>Habitación doble:</b> Habitación para dos personas, tiene una cama doble o extra doble.      

    .row.mb-4
      .col-md-6.border-bottom.px-4
        ul.lista-ul--color
          li.mb-1
            i.fas.fa-atom
            p 
              italic <b>Double room (twin beds):</b> Room for two guests in two separate beds.
      .col-md-6.border-bottom.px-4 
        ul.lista-ul--color
          li.mb-1
            i.fas.fa-atom
            p <b>Habitación doble (dos camas individuales):</b> Habitación para dos personas en camas separadas.

    .row.mb-4
      .col-md-6.border-bottom.px-4
        ul.lista-ul--color
          li.mb-1
            i.fas.fa-atom
            p 
              italic <b>Triple room:</b> Room for three (3) people, has a double bed and a single bed, or any other combination of 3 beds.
      .col-md-6.border-bottom.px-4 
        ul.lista-ul--color
          li.mb-1
            i.fas.fa-atom
            p <b>Habitación triple:</b> Habitación para tres (3) personas, cuenta con una cama doble y una cama individual, o cualquier otra combinación de 3 camas.

    .row.mb-4
      .col-md-6.border-bottom.px-4
        ul.lista-ul--color
          li.mb-1
            i.fas.fa-atom
            p 
              italic <b>Suite:</b> It is larger than a normal room. In the most luxurious hotels, the suites can even have multiple rooms. There are business or family class suites.
      .col-md-6.border-bottom.px-4 
        ul.lista-ul--color
          li.mb-1
            i.fas.fa-atom
            p <b>Suite:</b> Es más grande que una habitación normal. En los hoteles más lujosos, las suites pueden incluso tener varias habitaciones. Hay suites de clase empresarial o familiar.

    .row.mb-4
      .col-md-6.border-bottom.px-4
        ul.lista-ul--color
          li.mb-1
            i.fas.fa-atom
            p 
              italic <b>Connecting rooms:</b> This means that two rooms are connected by a door through which you can go from one room to another. Large groups or families often ask for this type of room.
      .col-md-6.border-bottom.px-4 
        ul.lista-ul--color
          li.mb-1
            i.fas.fa-atom
            p <b>Habitaciones comunicadas:</b> esto significa que dos habitaciones están conectadas por una puerta, a través de la cual se puede pasar de una habitación a otra. Los grupos grandes o las familias suelen solicitar este tipo de habitación.      

    .row.mb-4
      .col-md-6.border-bottom.px-4
        ul.lista-ul--color
          li.mb-1
            i.fas.fa-atom
            p 
              italic <b>Adjoining room:</b> Rooms that are next to each other but are not internally connected.
      .col-md-6.border-bottom.px-4 
        ul.lista-ul--color
          li.mb-1
            i.fas.fa-atom
            p <b>Habitaciones contiguas:</b> habitaciones que están una al lado de la otra, pero que no están conectadas internamente.                  


</template>

<script>
import TabsE from '../components/TabsE'
export default {
  name: 'Tema8',
  components: {
    TabsE,
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
