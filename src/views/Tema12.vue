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
            td <em>plus</em>
            td más
            td <em>add</em>
            td sumar
          tr.text-center.fila-naranja
            td <b>(-)</b>
            td <em>minus</em>
            td menos
            td <em>subtract</em>
            td restar  
          tr.text-center.fila-blanca
            td <b>(+)</b>
            td <em>plus</em>
            td más
            td <em>add</em>
            td sumar
          tr.text-center.fila-naranja
            td <b>(x)</b>
            td <em>multiplied by</em>
            td multiplicado por
            td <em>multiply</em>
            td multiplicar  
          tr.text-center.fila-blanca
            td <b>(÷)</b>
            td <em>divided by</em>
            td dividido por
            td <em>divide</em>
            td dividir
          tr.text-center.fila-naranja
            td <b>(>)</b>
            td <em>greater than</em>
            td mayor que
            td <em>is greater than</em>
            td es mayor que
          tr.text-center.fila-blanca
            td <b>(<)</b>
            td <em>less than</em>
            td menor que
            td <em>is less than</em>
            td es menor que
          tr.text-center.fila-naranja
            td <b>(=)</b>
            td <em>equal</em>
            td igual
            td <em>is equal to</em>
            td es igual a 
          tr.text-center.fila-blanca
            td <b>(≠)</b>
            td <em>is not equal</em>
            td no es igual
            td <em>is not equal to</em>
            td 
          tr.text-center.fila-naranja
            td <b>(%)</b>
            td <em>percentage</em>
            td porcentaje
            td 
            td             


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
                td algo
              tr.text-center.fila-naranja
                td <em>some</em>
                td algo de
              tr.text-center.fila-blanca
                td <em>pretty much</em>
                td bastante
              tr.text-center.fila-naranja
                td <em>the rest of</em>
                td el resto de  
              tr.text-center.fila-blanca
                td <em>half of the</em>
                td la mitad de el/la
              tr.text-center.fila-naranja
                td <em>more</em>
                td más  
              tr.text-center.fila-blanca
                td <em>less</em>
                td menos
              tr.text-center.fila-naranja
                td <em>a lot of</em>
                td mucho(a)  
              tr.text-center.fila-blanca
                td <em>none of</em>
                td nada de
              tr.text-center.fila-naranja
                td <em>not much</em>
                td no mucho  
              tr.text-center.fila-blanca
                td <em>little</em>
                td poco
              tr.text-center.fila-naranja
                td <em>a little bit</em>
                td un poco  
              tr.text-center.fila-blanca
                td <em>enough</em>
                td suficiente
              tr.text-center.fila-naranja
                td <em>several</em>
                td varios                



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
