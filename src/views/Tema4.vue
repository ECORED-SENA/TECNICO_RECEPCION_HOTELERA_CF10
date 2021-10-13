<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal
      .titulo-principal__numero
        span 4
      h1 <em>Spelling Names</em> / Deletreando nombres
    
    .row
      .col-md-7.mb-4(data-aos="fade-right")
        .row.content-usa.mb-4
          .img-usa
            .div
              img(src='@/assets/curso/bandera-usa.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3
            p 
              italic It will be common in your job as a receptionist to address guests by their names, especially in telephone communication where you will not have eye contact. Spelling names and surnames will be other of the key skills for your work.
            p 
              italic Remember that when spelling in English it is better if you use the International Phonetic Alphabet, which is the communication standard used for phonetic transcription.
        .row.content-esp
          .px-md-5.pt-md-2.pb-md-2.py-2.px-3
            p Será común en su labor como recepcionista tener que dirigirse a los huéspedes por su nombre, sobre todo en la comunicación telefónica, donde no tendrá contacto visual. Deletrear nombres y apellidos será otra de las habilidades claves para su labor.
            p Recuerde que al deletrear en inglés es mejor utilizar el alfabeto fonético internacional, que es el estándar de comunicación usado para la transcripción fonética.
          .img-esp
            .div
              img(src='@/assets/curso/bandera-esp.svg' alt='Bandera ESPAÑA')  
      .col-md-5.mb-4(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema4-img1.png', alt='Imagen decorativa')

</template>

<script>
export default {
  name: 'Tema4',
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
