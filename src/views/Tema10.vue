<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal
      .titulo-principal__numero
        span 10
      h1 <em>Expressing dates in English</em> / Expresando fechas en inglés
    
    figure
      img(src='@/assets/curso/tema10-img.png', alt='Imagen decorativa')  

    .row.mb-5
      .col-md-6.g-5.h-100
        .row.content-usa3.bg-naranja-suave.h-100
          .img-usa
            div.position3
              img(src='@/assets/curso/bandera-usa.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3 
            p <em>It is also common that when you are making reservations or confirming them, either in person or by phone, you have to use dates to agree on check-in and check-out dates with the client.</em>
            p.mb-0
              strong <em>Example:</em>
            p <em>Dear Mrs. González, I confirm your reservation details.</em>
            p <em>Your check-in will be on June 26, 2021 (June twenty-sixth, two thousand and twenty-one) and you will be staying with us for three (3) nights, until June 29, 2021 (June twenty-ninth, two thousand and twenty-one). </em>
            p <em>The confirmed rate is $349,000 + taxes (three hundred forty-nine thousand pesos, plus taxes).</em>
            p <em>Another use of the expression of dates in English is for celebrations and events. In this way, you can give indications about special events or celebrations. </em> 

      .col-md-6.g-5.h-100
        .row.content-esp3.bg-azul.h-100
          .img-esp3
            div.position3
              img(src='@/assets/curso/bandera-esp.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3
            p También es habitual que al realizar reservas o confirmarlas, ya sea de forma presencial o telefónica, se tengan que usar fechas para acordar las fechas de entrada y salida con cliente.
            p.mb-0 
              strong Ejemplo:
            p Estimada señora González, confirmó los detalles de su reserva.
            p Su registro será el 26 de junio de 2021 (veintiséis de junio de dos mil veintiuno) y se alojará con nosotros por tres (3) noches, hasta el 29 de junio de 2021 (veintinueve de junio de dos mil veintiuno). La tarifa confirmada es de $349.000 + impuestos (trescientos cuarenta y nueve mil pesos, más impuestos).
            p Otro uso de la expresión de fechas en inglés es para las celebraciones o los eventos. De esta forma, se pueden dar indicaciones acerca de eventos especiales o celebraciones.


</template>

<script>
export default {
  name: 'Tema10',
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
