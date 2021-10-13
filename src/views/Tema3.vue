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
                    td <em>zero</em>
                    td cero   
                  tr.text-center.fila-naranja
                    td 1
                    td <em>one</em>
                    td uno   
                  tr.text-center.fila-blanca
                    td 2
                    td <em>two</em>
                    td dos 
                  tr.text-center.fila-naranja
                    td 3
                    td <em>three</em>
                    td tres 
                  tr.text-center.fila-blanca
                    td 4
                    td <em>four</em>
                    td cuatro 
                  tr.text-center.fila-naranja
                    td 5
                    td <em>five</em>
                    td cinco    
                  tr.text-center.fila-blanca
                    td 6
                    td <em>six</em>
                    td seis  
                  tr.text-center.fila-naranja
                    td 7
                    td <em>seven</em>
                    td siete  
                  tr.text-center.fila-blanca
                    td 8
                    td <em>eight</em>
                    td ocho  
                  tr.text-center.fila-naranja
                    td 9
                    td <em>nine</em>
                    td nueve  
                  tr.text-center.fila-blanca
                    td 10
                    td <em>ten</em>
                    td diez 
                  tr.text-center.fila-naranja
                    td 11
                    td <em>eleven</em>
                    td once 
                  tr.text-center.fila-blanca
                    td 12
                    td <em>twelve</em>
                    td doce
                  tr.text-center.fila-naranja
                    td 13
                    td <em>thirteen</em>
                    td trece                       
                  tr.text-center.fila-blanca
                    td 14
                    td <em>fourteen</em>
                    td catorce 
                  tr.text-center.fila-naranja
                    td 15
                    td <em>fifteen</em>
                    td quince 
                  tr.text-center.fila-blanca
                    td 16
                    td <em>sixteen</em>
                    td dieciséis 
                  tr.text-center.fila-naranja
                    td 17
                    td <em>seventeen</em>
                    td diecisiete 
                  tr.text-center.fila-blanca
                    td 18
                    td <em>eighteen</em>
                    td dieciocho 
                  tr.text-center.fila-naranja
                    td 19
                    td <em>nineteen</em>
                    td diecinueve  
                  tr.text-center.fila-blanca
                    td 20
                    td <em>twenty</em>
                    td veinte  
                  tr.text-center.fila-naranja
                    td 30
                    td <em>thirty</em>
                    td treinta 
                  tr.text-center.fila-blanca
                    td 40
                    td <em>forty</em>
                    td cuarenta 
                  tr.text-center.fila-naranja
                    td 50
                    td <em>fifty</em>
                    td cincuenta 
                  tr.text-center.fila-blanca
                    td 60
                    td <em>sixty</em>
                    td sesenta 
                  tr.text-center.fila-naranja
                    td 70
                    td <em>seventy</em>
                    td setenta 
                  tr.text-center.fila-blanca
                    td 80
                    td <em>eighty</em>
                    td ochenta 
                  tr.text-center.fila-naranja
                    td 90
                    td <em>ninety</em>
                    td noventa 
                  tr.text-center.fila-blanca
                    td 100
                    td <em>one hundred</em>
                    td cien                            
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
                    td  
                    td     
                  tr.text-center.fila-naranja
                    td 1st
                    td <em>first</em>
                    td primero   
                  tr.text-center.fila-blanca
                    td 2nd
                    td <em>second</em>
                    td segundo 
                  tr.text-center.fila-naranja
                    td 3rd
                    td <em>third</em>
                    td tercero 
                  tr.text-center.fila-blanca
                    td 4th
                    td <em>fourth</em>
                    td cuatro 
                  tr.text-center.fila-naranja
                    td 5th
                    td <em>five</em>
                    td cinco    
                  tr.text-center.fila-blanca
                    td 6th
                    td <em>six</em>
                    td seis  
                  tr.text-center.fila-naranja
                    td 7th
                    td <em>seventh</em>
                    td séptimo  
                  tr.text-center.fila-blanca
                    td 8th
                    td <em>eighth</em>
                    td octavo  
                  tr.text-center.fila-naranja
                    td 9th
                    td <em>ninth</em>
                    td noveno  
                  tr.text-center.fila-blanca
                    td 10th
                    td <em>tenth</em>
                    td décimo 
                  tr.text-center.fila-naranja
                    td 11th
                    td <em>eleventh</em>
                    td undécimo 
                  tr.text-center.fila-blanca
                    td 12th
                    td <em>twelfth</em>
                    td doceavo
                  tr.text-center.fila-naranja
                    td 13th
                    td <em>thirteenth</em>
                    td treceavo                       
                  tr.text-center.fila-blanca
                    td 14th
                    td <em>fourteenth</em>
                    td catorceavo 
                  tr.text-center.fila-naranja
                    td 15th
                    td <em>fifteenth</em>
                    td quinceavo 
                  tr.text-center.fila-blanca
                    td 16th
                    td <em>sixteenth</em>
                    td dieciséisavo 
                  tr.text-center.fila-naranja
                    td 17th
                    td <em>seventeenth</em>
                    td diecisieteavo 
                  tr.text-center.fila-blanca
                    td 18th
                    td <em>eighteenth</em>
                    td dieciochoavo 
                  tr.text-center.fila-naranja
                    td 19th
                    td <em>nineteenth</em>
                    td diecinueveavo  
                  tr.text-center.fila-blanca
                    td 20th
                    td <em>twentieth</em>
                    td vigésimo  
                  tr.text-center.fila-naranja
                    td 30th
                    td <em>thirtieth</em>
                    td trigésimo 
                  tr.text-center.fila-blanca
                    td 40th
                    td <em>fortieth</em>
                    td cuadragésimo 
                  tr.text-center.fila-naranja
                    td 50th
                    td <em>fiftieth</em>
                    td quincuagésimo 
                  tr.text-center.fila-blanca
                    td 60th
                    td <em>sixtieth</em>
                    td sexagésimo 
                  tr.text-center.fila-naranja
                    td 70th
                    td <em>seventieth</em>
                    td septuagésimo 
                  tr.text-center.fila-blanca
                    td 80th
                    td <em>eightieth</em>
                    td octagésimo 
                  tr.text-center.fila-naranja
                    td 90th
                    td <em>ninetieth</em>
                    td nonagésimo 
                  tr.text-center.fila-blanca
                    td 100th
                    td <em>hundredth</em>
                    td centésimo 

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
