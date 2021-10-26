<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal
      .titulo-principal__numero
        span 3
      h1 <em>Superlatives </em> / Superlativos

    .row.mb-4
      .col-md-7.mb-4(data-aos="fade-right")
        .row.content-usa.mb-4
          .img-usa
            .div
              img(src='@/assets/curso/bandera-usa.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3
            p <em>The adjective when is used in the superlative form describes an object that is at the upper or lower end of a quality. Like the comparative, it is used in sentences in which a subject is compare to a group, according to the following structure: </em>
            p 
              italic-strong.etiqueta Noun (subject) + verb + the + adjective in superlative degree + noun (object).
            p.mb-0   
              strong Examples:
            p.mb-0   
              italic Peter + is + the + highest + of the classroom.
            p  
              italic Your room + is + the + most comfortable + of the hotel.
        .row.content-esp
          .px-md-5.pt-md-2.pb-md-2.py-2.px-3
            p Cuando un adjetivo se utiliza en forma superlativa, describe un objeto que se encuentra en el extremo superior o inferior de una cualidad. Al igual que el comparativo, se utiliza en oraciones en las que comparamos un sujeto con un grupo, de acuerdo con la siguiente estructura:
            p 
              strong.etiqueta Sustantivo (sujeto) + verbo + el (la) + adjetivo en grado superlativo + sustantivo (objeto).
            p.mb-0   
              strong Ejemplos:
            p.mb-0 Pedro + es + el + más alto + del salón.
            p.mb-0 Su habitación + es + la + más cómoda + del hotel.
          .img-esp
            .div
              img(src='@/assets/curso/bandera-esp.svg' alt='Bandera ESPAÑA')  
      .col-md-5.mb-4(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema3-img.png', alt='Imagen decorativa')

    .row.justify-content-center.mb-5
      .col-md-11.bg-naranja-suave.p-4
        .row
          .col-md-5
            img(src='@/assets/curso/tema3-cta.svg', alt='Imagen decorativa')
          .col-md-7
            #video_cta.titulo-segundo
              h3 <em>See this video series</em> / Ver esta serie de videos
            p.mb-1 <em>We invite you to review the following vídeo to complement the information:</em>
            p Se le invita a revisar los siguientes videos para complementar la información:
            .row
              .col-md-6
                .row.align-items-center.mb-4
                  .col-md-5
                    p.mb-0 Lección 1:
                  .col-md-6
                    a.boton--sm.color-primario.me-3(:href="('https://www.youtube.com/watch?v=WALXkZx78GQ&t=36s')" target="_blank" type="application/pdf")
                      span Enlace 
                      i.fas.fa-link
                .row.align-items-center.mb-4
                  .col-md-5
                    p.mb-0 Lección 2:
                  .col-md-6
                    a.boton--sm.color-primario.me-3(:href="('https://www.youtube.com/watch?v=a-GEGiqDnKY')" target="_blank" type="application/pdf")
                      span Enlace 
                      i.fas.fa-link 
                .row.align-items-center.mb-4
                  .col-md-5
                    p.mb-0 Lección 3:
                  .col-md-6
                    a.boton--sm.color-primario.me-3(:href="('https://www.youtube.com/watch?v=5xjSUPczYEY')" target="_blank" type="application/pdf")
                      span Enlace 
                      i.fas.fa-link 
                .row.align-items-center.mb-4
                  .col-md-5
                    p.mb-0 Lección 4:
                  .col-md-6
                    a.boton--sm.color-primario.me-3(:href="('https://www.youtube.com/watch?v=enOQ_V5H5sU')" target="_blank" type="application/pdf")
                      span Enlace 
                      i.fas.fa-link       
              .col-md-6
                .row.align-items-center.mb-4
                  .col-md-5
                    p.mb-0 Lección 5:
                  .col-md-6
                    a.boton--sm.color-primario.me-3(:href="('https://www.youtube.com/watch?v=fJnnhyDM6f4')" target="_blank" type="application/pdf")
                      span Enlace 
                      i.fas.fa-link
                .row.align-items-center.mb-4
                  .col-md-5
                    p.mb-0 Lección 6:
                  .col-md-6
                    a.boton--sm.color-primario.me-3(:href="('https://www.youtube.com/watch?v=HCyYePYxy0I')" target="_blank" type="application/pdf")
                      span Enlace 
                      i.fas.fa-link 
                .row.align-items-center.mb-4
                  .col-md-5
                    p.mb-0 Lección 7:
                  .col-md-6
                    a.boton--sm.color-primario.me-3(:href="('https://www.youtube.com/watch?v=2fqHjsDiqyk')" target="_blank" type="application/pdf")
                      span Enlace 
                      i.fas.fa-link 

    .h4.subtitulo-naranja.mb-4(data-aos="fade-right") 
      span 
        italic Numbers / 
        | Números

    .row
      .col-md-7.mb-4(data-aos="fade-right")
        .row.content-usa.mb-4
          .img-usa
            .div
              img(src='@/assets/curso/bandera-usa.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3
            p 
              italic Knowing how to express numbers in English is an important skill at the front desk. You will have to give dates, show billing statements, explain the value of the currency, and many other interactions that involve talking about numbers.
        .row.content-esp
          .px-md-5.pt-md-2.pb-md-2.py-2.px-3
            p Saber expresar los números en inglés es una habilidad importante en la recepción. Usted tendrá que dar fechas, mostrar estados de cuenta, explicar el valor de la moneda y muchas otras interacciones que implican hablar de números.
          .img-esp
            .div
              img(src='@/assets/curso/bandera-esp.svg' alt='Bandera ESPAÑA')  
      .col-md-5.mb-4(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema3-img2.jpg', alt='Imagen decorativa')    

    AcordeonB.mb-5(tipo="a" clase-tarjeta="tarjeta bg-naranja" data-aos="fade-down")
      .row(titulo="<em>The ordinal numbers</em> / Los números ordinales")
        .col-md-6
          p 
            italic They are used to indicate order. That is, they point to the place of the indicated object within a series, to establish the position of the object in the middle of an ordered set of elements of the same class. Ordinals are generally used as adjectives before the noun
          p.mb-0 
            italic-strong Example:
          p <em> Your room is on the fourth floor to the left of the elevator.</em>
          .division-acento-contenido  
          p Se utilizan para indicar orden. Es decir, señalan el lugar del objeto indicado dentro de una serie, para establecer la posición de este en medio de un conjunto ordenado de elementos de la misma clase. Los ordinales generalmente se utilizan como adjetivos antes del sustantivo. 
          p.mb-0
            strong Ejemplo:
          p Su habitación está en el cuarto piso a la izquierda del ascensor.
        .col-md-6
          img(src='@/assets/curso/tema3-acord1.png', alt='Imagen decorativa') 

      .row(titulo="<em>The cardinal numbers</em> / Los números cardinales")
        p <em>They represent the amount of elements in a set. This quantity can be finite or infinite. They are the numbers used on a day-to-day basis to count and do mathematical operations.</em>
        p <em>In general, cardinal numbers are a generality of the natural number, allowing comparison of the number of elements of sets.</em>
        .division-acento-contenido
        p Representan la cantidad de elementos de un conjunto. Esta cantidad puede ser finita o infinita. Son los números empleados en el día a día para contar y hacer operaciones matemáticas.
        p En general, los números cardinales son una generalidad del número natural, permitiendo comparar la cantidad de elementos de conjuntos.
        .row
          .col-md-6
            .tabla-b.tabla-1.color-acento-contenido.mb-2
              table  
                thead.tabla-b__header 
                  tr
                    th(colspan="3")  
                      h3.text-white.mb-0 <em>Cardinal number</em>
                  tr.fila-subtitulo-naranja
                    th
                      h4.mb-0 <em>Symbol</em>
                    th
                      h4.mb-0 <em>Notation</em>
                    th
                      h4.mb-0 <em>Translation</em>
                tbody
                  tr.text-center.fila-blanca
                    td 0
                    td.tabla-borde-left <em>zero</em>
                    td.tabla-borde-left cero   
                  tr.text-center.fila-naranja
                    td 1
                    td.tabla-borde-left <em>one</em>
                    td.tabla-borde-left uno   
                  tr.text-center.fila-blanca
                    td 2
                    td.tabla-borde-left <em>two</em>
                    td.tabla-borde-left dos 
                  tr.text-center.fila-naranja
                    td 3
                    td.tabla-borde-left <em>three</em>
                    td.tabla-borde-left tres 
                  tr.text-center.fila-blanca
                    td 4
                    td.tabla-borde-left <em>four</em>
                    td.tabla-borde-left cuatro 
                  tr.text-center.fila-naranja
                    td 5
                    td.tabla-borde-left <em>five</em>
                    td.tabla-borde-left cinco    
                  tr.text-center.fila-blanca
                    td 6
                    td.tabla-borde-left <em>six</em>
                    td.tabla-borde-left seis  
                  tr.text-center.fila-naranja
                    td 7
                    td.tabla-borde-left <em>seven</em>
                    td.tabla-borde-left siete  
                  tr.text-center.fila-blanca
                    td 8
                    td.tabla-borde-left <em>eight</em>
                    td.tabla-borde-left ocho  
                  tr.text-center.fila-naranja
                    td 9
                    td.tabla-borde-left <em>nine</em>
                    td.tabla-borde-left nueve  
                  tr.text-center.fila-blanca
                    td 10
                    td.tabla-borde-left <em>ten</em>
                    td.tabla-borde-left diez 
                  tr.text-center.fila-naranja
                    td 11
                    td.tabla-borde-left <em>eleven</em>
                    td.tabla-borde-left once 
                  tr.text-center.fila-blanca
                    td 12
                    td.tabla-borde-left <em>twelve</em>
                    td.tabla-borde-left doce
                  tr.text-center.fila-naranja
                    td 13
                    td.tabla-borde-left <em>thirteen</em>
                    td.tabla-borde-left trece                       
                  tr.text-center.fila-blanca
                    td 14
                    td.tabla-borde-left <em>fourteen</em>
                    td.tabla-borde-left catorce 
                  tr.text-center.fila-naranja
                    td 15
                    td.tabla-borde-left <em>fifteen</em>
                    td.tabla-borde-left quince 
                  tr.text-center.fila-blanca
                    td 16
                    td.tabla-borde-left <em>sixteen</em>
                    td.tabla-borde-left dieciséis 
                  tr.text-center.fila-naranja
                    td 17
                    td.tabla-borde-left <em>seventeen</em>
                    td.tabla-borde-left diecisiete 
                  tr.text-center.fila-blanca
                    td 18
                    td.tabla-borde-left <em>eighteen</em>
                    td.tabla-borde-left dieciocho 
                  tr.text-center.fila-naranja
                    td 19
                    td.tabla-borde-left <em>nineteen</em>
                    td.tabla-borde-left diecinueve  
                  tr.text-center.fila-blanca
                    td 20
                    td.tabla-borde-left <em>twenty</em>
                    td.tabla-borde-left veinte  
                  tr.text-center.fila-naranja
                    td 30
                    td.tabla-borde-left <em>thirty</em>
                    td.tabla-borde-left treinta 
                  tr.text-center.fila-blanca
                    td 40
                    td.tabla-borde-left <em>forty</em>
                    td.tabla-borde-left cuarenta 
                  tr.text-center.fila-naranja
                    td 50
                    td.tabla-borde-left <em>fifty</em>
                    td.tabla-borde-left cincuenta 
                  tr.text-center.fila-blanca
                    td 60
                    td.tabla-borde-left <em>sixty</em>
                    td.tabla-borde-left sesenta 
                  tr.text-center.fila-naranja
                    td 70
                    td.tabla-borde-left <em>seventy</em>
                    td.tabla-borde-left setenta 
                  tr.text-center.fila-blanca
                    td 80
                    td.tabla-borde-left <em>eighty</em>
                    td.tabla-borde-left ochenta 
                  tr.text-center.fila-naranja
                    td 90
                    td.tabla-borde-left <em>ninety</em>
                    td.tabla-borde-left noventa 
                  tr.text-center.fila-blanca
                    td 100
                    td.tabla-borde-left <em>one hundred</em>
                    td.tabla-borde-left cien                            
          .col-md-6
            .tabla-b.tabla-1.color-acento-contenido.mb-2
              table  
                thead.tabla-b__header 
                  tr
                    th(colspan="3")  
                      h3.text-white.mb-0 <em>Cardinal number</em>
                  tr.fila-subtitulo-naranja
                    th
                      h4.mb-0 <em>Symbol</em>
                    th
                      h4.mb-0 <em>Notation</em>
                    th
                      h4.mb-0 <em>Translation</em>
                tbody
                  tr.text-center.fila-blanca
                    td  
                    td.tabla-borde-left  
                    td.tabla-borde-left     
                  tr.text-center.fila-naranja
                    td 1st
                    td.tabla-borde-left <em>first</em>
                    td.tabla-borde-left primero   
                  tr.text-center.fila-blanca
                    td 2nd
                    td.tabla-borde-left <em>second</em>
                    td.tabla-borde-left segundo 
                  tr.text-center.fila-naranja
                    td 3rd
                    td.tabla-borde-left <em>third</em>
                    td.tabla-borde-left tercero 
                  tr.text-center.fila-blanca
                    td 4th
                    td.tabla-borde-left <em>fourth</em>
                    td.tabla-borde-left cuatro 
                  tr.text-center.fila-naranja
                    td 5th
                    td.tabla-borde-left <em>five</em>
                    td.tabla-borde-left cinco    
                  tr.text-center.fila-blanca
                    td 6th
                    td.tabla-borde-left <em>six</em>
                    td.tabla-borde-left seis  
                  tr.text-center.fila-naranja
                    td 7th
                    td.tabla-borde-left <em>seventh</em>
                    td.tabla-borde-left séptimo  
                  tr.text-center.fila-blanca
                    td 8th
                    td.tabla-borde-left <em>eighth</em>
                    td.tabla-borde-left octavo  
                  tr.text-center.fila-naranja
                    td 9th
                    td.tabla-borde-left <em>ninth</em>
                    td.tabla-borde-left noveno  
                  tr.text-center.fila-blanca
                    td 10th
                    td.tabla-borde-left <em>tenth</em>
                    td.tabla-borde-left décimo 
                  tr.text-center.fila-naranja
                    td 11th
                    td.tabla-borde-left <em>eleventh</em>
                    td.tabla-borde-left undécimo 
                  tr.text-center.fila-blanca
                    td 12th
                    td.tabla-borde-left <em>twelfth</em>
                    td.tabla-borde-left doceavo
                  tr.text-center.fila-naranja
                    td 13th
                    td.tabla-borde-left <em>thirteenth</em>
                    td.tabla-borde-left treceavo                       
                  tr.text-center.fila-blanca
                    td 14th
                    td.tabla-borde-left <em>fourteenth</em>
                    td.tabla-borde-left catorceavo 
                  tr.text-center.fila-naranja
                    td 15th
                    td.tabla-borde-left <em>fifteenth</em>
                    td.tabla-borde-left quinceavo 
                  tr.text-center.fila-blanca
                    td 16th
                    td.tabla-borde-left <em>sixteenth</em>
                    td.tabla-borde-left dieciséisavo 
                  tr.text-center.fila-naranja
                    td 17th
                    td.tabla-borde-left <em>seventeenth</em>
                    td.tabla-borde-left diecisieteavo 
                  tr.text-center.fila-blanca
                    td 18th
                    td.tabla-borde-left <em>eighteenth</em>
                    td.tabla-borde-left dieciochoavo 
                  tr.text-center.fila-naranja
                    td 19th
                    td.tabla-borde-left <em>nineteenth</em>
                    td.tabla-borde-left diecinueveavo  
                  tr.text-center.fila-blanca
                    td 20th
                    td.tabla-borde-left <em>twentieth</em>
                    td.tabla-borde-left vigésimo  
                  tr.text-center.fila-naranja
                    td 30th
                    td.tabla-borde-left <em>thirtieth</em>
                    td.tabla-borde-left trigésimo 
                  tr.text-center.fila-blanca
                    td 40th
                    td.tabla-borde-left <em>fortieth</em>
                    td.tabla-borde-left cuadragésimo 
                  tr.text-center.fila-naranja
                    td 50th
                    td.tabla-borde-left <em>fiftieth</em>
                    td.tabla-borde-left quincuagésimo 
                  tr.text-center.fila-blanca
                    td 60th
                    td.tabla-borde-left <em>sixtieth</em>
                    td.tabla-borde-left sexagésimo 
                  tr.text-center.fila-naranja
                    td 70th
                    td.tabla-borde-left <em>seventieth</em>
                    td.tabla-borde-left septuagésimo 
                  tr.text-center.fila-blanca
                    td 80th
                    td.tabla-borde-left <em>eightieth</em>
                    td.tabla-borde-left octagésimo 
                  tr.text-center.fila-naranja
                    td 90th
                    td.tabla-borde-left <em>ninetieth</em>
                    td.tabla-borde-left nonagésimo 
                  tr.text-center.fila-blanca
                    td 100th
                    td.tabla-borde-left <em>hundredth</em>
                    td.tabla-borde-left centésimo 

      .row(titulo="<em>Expressing quantities in English</em> / Expresando cantidades en inglés")
        .col-md-6
          p 
            italic As a receptionist, you will have to express amounts at some occasions, referring to accounts or prices. See how to do it.
          p.mb-0 
            italic-strong Example:
          p <em>Mr. Pedroza, your total account is $254.325 Colombian pesos (two hundred and fifty-four thousand three hundred and twenty-five Colombian pesos).</em>
          p <em>It would be $72,66 dollars (seventy-two dollars and sixty-six cents).</em>
          .division-acento-contenido  
          p Como recepcionista, usted deberá en algunas oportunidades expresar cantidades, referidas a las cuentas o a los precios. Observe cómo se hace.
          p.mb-0
            strong Ejemplo:
          p Sr. Pedroza su cuenta total es $254.325 pesos colombianos (doscientos cincuenta y cuatro mil trescientos veinticinco pesos colombianos).
          p Serian $ 72,66 dólares (setenta y dos dólares con sesenta y seis centavos).
        .col-md-6
          img(src='@/assets/curso/tema3-acord3.png', alt='Imagen decorativa')     


    .row.justify-content-center
      .col-md-10
        .tarjeta.color-acento-botones.p-3
          .row.justify-content-around.align-items-center.px-md-3
            .col-3.col-sm-2.col-lg-2
              img.px-md-4(src="@/assets/curso/tema3-cta1.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-2 <em>See this video</em> / Ver este video
                  p.mb-0.text-small We invite you to review the following vídeo to complement the information.
                  p.mb-0.text-small Se le invita a revisar el siguiente video para complementar la información
                .col-sm-auto
                  a.boton.color-primario(:href="('https://www.youtube.com/watch?v=9MzsJd2j7Vc')" target="_blank")
                    span Enlace
                    i.fas.fa-link    
        





</template>

<script>
import AcordeonB from '../components/AcordeonB'
export default {
  name: 'Tema3',
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
