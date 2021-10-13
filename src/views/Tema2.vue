<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal
      .titulo-principal__numero
        span 2
      h1 <em>Comparatives </em> / Comparativos

    .row.mb-4
      .col-md-7.mb-4(data-aos="fade-right")
        .row.content-usa.mb-4
          .img-usa
            .div
              img(src='@/assets/curso/bandera-usa.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3
            p <em>The comparative adjectives are used in English to highlight the differences between two objects that they modify. </em>
            p <em>The grammatical structure to form the comparison is as follows:</em>
            p 
              italic-strong.etiqueta Subject + verb + comparative adjective + than + object
            p.mb-0   
              strong Examples:
            p.mb-0   
              italic Pedro + is + faster + than + me.
            p  
              italic His room + is + more comfortable + than yours.  
        .row.content-esp
          .px-md-5.pt-md-2.pb-md-2.py-2.px-3
            p Los adjetivos comparativos se utilizan en inglés para resaltar las diferencias entre dos objetos a los que modifican. 
            p La estructura gramatical para formar la comparación es la siguiente:
            p 
              strong.etiqueta Sujeto + verbo + adjetivo comparativo + than + objeto
            p.mb-0   
              strong Ejemplos:
            p.mb-0 Pedro + es + más rápido + que + yo.
            p.mb-0 Su habitación + es + más cómoda + que la tuya.
          .img-esp
            .div
              img(src='@/assets/curso/bandera-esp.svg' alt='Bandera ESPAÑA')  
      .col-md-5.mb-4(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema2-img.png', alt='Imagen decorativa')

    .row.justify-content-center.mb-3
      .col-md-11.bg-naranja-suave.p-4
        .row
          .col-md-5
            img(src='@/assets/curso/tema2-cta.svg', alt='Imagen decorativa')
          .col-md-7
            #video_cta.titulo-segundo
              h3 <em>See this video series</em> / Ver esta serie de videos
            p.mb-1 <em>We invite you to review the following vídeo to complement the information:</em>
            p Se le invita a revisar los siguientes videos para complementar la información:
            .row.align-items-center
              .col-md-6
                .row.align-items-center.mb-4
                  .col-md-5
                    p.mb-0 Lección 1:
                  .col-md-6
                    a.boton--sm.color-primario.me-3(:href="('https://www.youtube.com/watch?v=oBytkylSufw&t=169s')" target="_blank" type="application/pdf")
                      span Enlace 
                      i.fas.fa-link
                .row.align-items-center.mb-4
                  .col-md-5
                    p.mb-0 Lección 2:
                  .col-md-6
                    a.boton--sm.color-primario.me-3(:href="('https://www.youtube.com/watch?v=eA46BhGhp9Q')" target="_blank" type="application/pdf")
                      span Enlace 
                      i.fas.fa-link 
                .row.align-items-center.mb-4
                  .col-md-5
                    p.mb-0 Lección 3:
                  .col-md-6
                    a.boton--sm.color-primario.me-3(:href="('https://www.youtube.com/watch?v=YWLCZU5Jsbc')" target="_blank" type="application/pdf")
                      span Enlace 
                      i.fas.fa-link 
              .col-md-6
                .row.align-items-center.mb-4
                  .col-md-5
                    p.mb-0 Lección 4:
                  .col-md-6
                    a.boton--sm.color-primario.me-3(:href="('https://www.youtube.com/watch?v=pL9GTpg9UDo&t=4s')" target="_blank" type="application/pdf")
                      span Enlace 
                      i.fas.fa-link
                .row.align-items-center.mb-4
                  .col-md-5
                    p.mb-0 Lección 5:
                  .col-md-6
                    a.boton--sm.color-primario.me-3(:href="('https://www.youtube.com/watch?v=7lmjKN6Sh4s')" target="_blank" type="application/pdf")
                      span Enlace 
                      i.fas.fa-link 
                .row.align-items-center.mb-4
                  .col-md-5
                    p.mb-0 Lección 6:
                  .col-md-6
                    a.boton--sm.color-primario.me-3(:href="('https://www.youtube.com/watch?v=TEHj5a1n_Z8')" target="_blank" type="application/pdf")
                      span Enlace 
                      i.fas.fa-link 


    .row.mb-2  
      .col-md-4.g-5.h-100
        .row.content-usa3.border-naranja.border-redondo-abajo-derecho.bg-azul
          .img-usa
            div.position3
              img(src='@/assets/curso/bandera-usa.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3
            .h3.subtitulo-naranja2.text-center.mb-4
              span 
                italic Adjectives  
            p <em>Adjectives are words that qualify, providing additional information or expressing qualities of a noun. There are several kinds of adjectives. </em>
            .row
              .col-md-6
                ul.lista-ul--color
                  li.mb-1
                    i.fas.fa-atom
                    italic Qualitative
                  li.mb-1
                    i.fas.fa-atom
                    italic Demonstrative
                  li.mb-1
                    i.fas.fa-atom
                    italic Quantitative  
              .col-md-6
                ul.lista-ul--color
                  li.mb-1
                    i.fas.fa-atom
                    italic Possessive
                  li.mb-1
                    i.fas.fa-atom
                    italic Questions
                  li.mb-1
                    i.fas.fa-atom
                    italic Numeric    
      .col-md-4.g-5.h-100
        .row.content-esp3.border-naranja.border-redondo-abajo-derecho.bg-azul
          .img-esp3
            div.position3
              img(src='@/assets/curso/bandera-esp.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3
            .h3.subtitulo-naranja2.text-center.mb-4
              span Adjetivos   
            p Los adjetivos son palabras que califican, aportando información adicional o expresando las cualidades de un sustantivo. Existen varias clases de adjetivos.
            .row
              .col-md-6
                ul.lista-ul--color
                  li.mb-1
                    i.fas.fa-atom
                    | Calificativos
                  li.mb-1
                    i.fas.fa-atom
                    | Demostrativos
                  li.mb-1
                    i.fas.fa-atom
                    | Cuantitativos  
              .col-md-6
                ul.lista-ul--color
                  li.mb-1
                    i.fas.fa-atom
                    | Posesivos
                  li.mb-1
                    i.fas.fa-atom
                    | Interrogativos
                  li.mb-1
                    i.fas.fa-atom
                    | Numéricos         
      .col-md-4.g-5.h-100
        img(src='@/assets/curso/tema2-img2.png', alt='Imagen decorativa')


    .row
      .col-md-4.g-5.h-100
        .row.content-usa3.border-amarillo.border-redondo-abajo-derecho.bg-azul.h-100
          .img-usa
            div.position3
              img(src='@/assets/curso/bandera-usa.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3
            .h3.subtitulo-amarillo.text-center.mb-4
              span 
                italic Adverbs  
            p <em>Adverbs are words that complement a verb, an adjective, or another adverb. These complement the meaning of the verb that they modify indicating the form, the frequency, or the place where things happen.</em>
      .col-md-4.g-5.h-100
        .row.content-esp3.border-amarillo.border-redondo-abajo-derecho.bg-azul.h-100
          .img-esp3
            div.position3
              img(src='@/assets/curso/bandera-esp.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3
            .h3.subtitulo-amarillo.text-center.mb-4
              span Adverbios   
            p Los adverbios son palabras que complementan un verbo, un adjetivo u otro adverbio. Estos complementan el significado del verbo que modifican indicando la forma, la frecuencia o el lugar donde suceden las cosas.         
      .col-md-4.g-5.h-100
        img(src='@/assets/curso/tema2-img3.png', alt='Imagen decorativa')




</template>

<script>
export default {
  name: 'Tema2',
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
