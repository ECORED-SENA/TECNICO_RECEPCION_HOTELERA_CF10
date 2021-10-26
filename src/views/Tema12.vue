<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal
      .titulo-principal__numero
        span 12
      h1 <em>Mathematical Expressions</em> / Expresiones matemáticas
    
    .row.mb-4
      .col-md-7.mb-4(data-aos="fade-right")
        .row.content-usa.mb-4
          .img-usa
            .div
              img(src='@/assets/curso/bandera-usa.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3
            p 
              italic To correctly express numerical and mathematical quantities, it is necessary to know some terms commonly used in this type of expressions.
        .row.content-esp
          .px-md-5.pt-md-2.pb-md-2.py-2.px-3
            p Para expresar correctamente cantidades numéricas y matemáticas, es necesario conocer algunos términos de uso común en este tipo de expresiones.
          .img-esp
            .div
              img(src='@/assets/curso/bandera-esp.svg' alt='Bandera ESPAÑA')  
      .col-md-5.mb-4(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema12-img.png', alt='Imagen decorativa')


    .tabla-b.tabla-1.color-acento-contenido.borde-tabla-naranja.mb-5(data-aos="fade-down")
      table  
        thead.tabla-b__header 
          tr
            th  
              h3.text-white.mb-0 <em>Symbol</em>
            th  
              h3.text-white.mb-0 <em>Meaning</em> 
            th  
              h3.text-white.mb-0 <em>Significado</em>  
            th  
              h3.text-white.mb-0 <em>Operation</em>  
            th  
              h3.text-white.mb-0 <em>Operación</em>         
        tbody
          tr.text-center.fila-blanca
            td <b>(+)</b>
            td.tabla-borde-left <em>plus</em>
            td.tabla-borde-left más
            td.tabla-borde-left <em>add</em>
            td.tabla-borde-left sumar
          tr.text-center.fila-naranja
            td <b>(-)</b>
            td.tabla-borde-left <em>minus</em>
            td.tabla-borde-left menos
            td.tabla-borde-left <em>subtract</em>
            td.tabla-borde-left restar  
          tr.text-center.fila-blanca
            td <b>(x)</b>
            td.tabla-borde-left <em>multiplied by</em>
            td.tabla-borde-left multiplicado por
            td.tabla-borde-left <em>multiply</em>
            td.tabla-borde-left multiplicar  
          tr.text-center.fila-naranja
            td <b>(÷)</b>
            td.tabla-borde-left <em>divided by</em>
            td.tabla-borde-left dividido por
            td.tabla-borde-left <em>divide</em>
            td.tabla-borde-left dividir
          tr.text-center.fila-blanca
            td <b>(>)</b>
            td.tabla-borde-left <em>greater than</em>
            td.tabla-borde-left mayor que
            td.tabla-borde-left <em>is greater than</em>
            td.tabla-borde-left es mayor que
          tr.text-center.fila-naranja
            td <b>(<)</b>
            td.tabla-borde-left <em>less than</em>
            td.tabla-borde-left menor que
            td.tabla-borde-left <em>is less than</em>
            td.tabla-borde-left es menor que
          tr.text-center.fila-blanca
            td <b>(=)</b>
            td.tabla-borde-left <em>equal</em>
            td.tabla-borde-left igual
            td.tabla-borde-left <em>is equal to</em>
            td.tabla-borde-left es igual a 
          tr.text-center.fila-naranja
            td <b>(≠)</b>
            td.tabla-borde-left <em>is not equal</em>
            td.tabla-borde-left no es igual
            td.tabla-borde-left <em>is not equal to</em>
            td.tabla-borde-left no es igual a
          tr.text-center.fila-blanca
            td <b>(%)</b>
            td.tabla-borde-left <em>percentage</em>
            td.tabla-borde-left porcentaje
            td.tabla-borde-left 
            td.tabla-borde-left             


    .h4.subtitulo-naranja.mb-4(data-aos="fade-right") 
      span 
        italic Quantitative adjectives / 
        | Adjetivos cuantitativos

    .row
      .col-md-6.mb-4(data-aos="fade-right")
        .row.content-usa.mb-4
          .img-usa
            .div
              img(src='@/assets/curso/bandera-usa.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3
            p 
              italic Quantitative adjectives are expressions of quantity that qualify the noun imprecisely. In general, they answer the question: How much?
            p 
              italic Look at the most used quantity expressions in English:
        .row.content-esp
          .px-md-5.pt-md-2.pb-md-2.py-2.px-3
            p Los adjetivos cuantitativos son expresiones de cantidad que califican al sustantivo de forma imprecisa. En general, contestan la pregunta: ¿Cuánto?
            p Observe las expresiones de cantidad más usadas en inglés:
          .img-esp
            .div
              img(src='@/assets/curso/bandera-esp.svg' alt='Bandera ESPAÑA')  
      .col-md-6.mb-4(data-aos="fade-left")
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
                td <em>something</em>
                td.tabla-borde-left algo
              tr.text-center.fila-naranja
                td <em>some</em>
                td.tabla-borde-left algo de
              tr.text-center.fila-blanca
                td <em>pretty much</em>
                td.tabla-borde-left bastante
              tr.text-center.fila-naranja
                td <em>the rest of</em>
                td.tabla-borde-left el resto de  
              tr.text-center.fila-blanca
                td <em>half of the</em>
                td.tabla-borde-left la mitad de el/la
              tr.text-center.fila-naranja
                td <em>more</em>
                td.tabla-borde-left más  
              tr.text-center.fila-blanca
                td <em>less</em>
                td.tabla-borde-left menos
              tr.text-center.fila-naranja
                td <em>a lot of</em>
                td.tabla-borde-left mucho(a)  
              tr.text-center.fila-blanca
                td <em>none of</em>
                td.tabla-borde-left nada de
              tr.text-center.fila-naranja
                td <em>not much</em>
                td.tabla-borde-left no mucho  
              tr.text-center.fila-blanca
                td <em>little</em>
                td.tabla-borde-left poco
              tr.text-center.fila-naranja
                td <em>a little bit</em>
                td.tabla-borde-left un poco  
              tr.text-center.fila-blanca
                td <em>enough</em>
                td.tabla-borde-left suficiente
              tr.text-center.fila-naranja
                td <em>several</em>
                td.tabla-borde-left varios                



</template>

<script>
export default {
  name: 'Tema12',
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
