<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal
      .titulo-principal__numero
        span 9
      h1 <em>Payment Forms</em> / Formas de pago
    
    .row.mb-4
      .col-md-7.mb-4(data-aos="fade-right")
        .row.content-usa.mb-4
          .img-usa
            .div
              img(src='@/assets/curso/bandera-usa.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3
            p 
              italic Whenever you close an account and issue an invoice, you must receive a payment. In this section, you will study the payment forms legally accepted and guaranteed by the Colombian state and the accommodation establishment.
        .row.content-esp
          .px-md-5.pt-md-2.pb-md-2.py-2.px-3
            p Siempre que se va a cerrar una cuenta y a expedir una factura, se debe recibir un pago. En este apartado, se estudiarán las formas de pago legalmente aceptadas y avaladas por el Estado colombiano y el establecimiento de alojamiento. 
          .img-esp
            .div
              img(src='@/assets/curso/bandera-esp.svg' alt='Bandera ESPAÑA')  
      .col-md-5.mb-4(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema9-img.png', alt='Imagen decorativa')


    .row.justify-content-center.bg-azul.mb-5
      .col-md-10.p-4.py-5
        SlyderE(indicadores="izquierda")
          .row
            .col-md-6.mb-4.mb-md-0
              p
                italic In the Republic of Colombia, including its islands of San Andrés and Providencia, the national currency is the Colombian peso, identified by the sign of the same name ($) and whose abbreviation is COP. The national currency is presented in notes and coins.
              .division-acento-contenido  
              p.mb-0 En la República de Colombia, incluyendo sus islas de San Andrés y Providencia, la moneda nacional es el peso colombiano, identificado con el signo del mismo nombre ($) y cuya abreviatura es COP. La moneda nacional se presenta en billetes y monedas.
            .col-md-6
              figure
                img.mb-2(src='@/assets/curso/tema9-slider1.png', alt='Imagen decorativa')
                figcaption Official currency is Colombian peso (COP). These are the bills and coins.
          .row
            .col-md-12
              p
                italic In Colombia, by regulation, it is forbidden to invoice in foreign currencies. And those who receive foreign currency as a form of payment must operate as professional money exchangers. Beyond this consideration, the currencies that are accepted in Colombia are: U.S. dollars and euros.
              .division-acento-contenido  
              p En Colombia, por normatividad, está prohibido facturar en moneda extranjera. Y quienes reciben moneda extranjera como forma de pago deben operar como cambistas profesionales. Más allá de esta consideración, las monedas que se aceptan en Colombia son: dólares americanos y euros.
            .row
              .col-md-6.mb-4.mb-md-0
                figure
                  img.mb-2(src='@/assets/curso/tema9-slider2-1.png', alt='Imagen decorativa')
                  figcaption In hotels, it is possible to pay with American dollars. These are the bills.
              .col-md-6
                figure
                  img.mb-2(src='@/assets/curso/tema9-slider2-2.png', alt='Imagen decorativa')
                  figcaption Sometimes also the hotels receive euros. These are the bills.
          .row
            .col-md-6.mb-4.mb-md-0
              p
                italic This is the most widespread form of payment, for its ease of use and immediate confirmation since what the cards do is to debit from the cardholder’s account and deposit into the hotel account. In this section, the important thing is to comply with the security regulations about the use of cards and identification of cardholders to avoid fraud.
              .division-acento-contenido  
              p.mb-0 Este es la forma de pago más extendida, por su facilidad de uso y confirmación inmediata, ya que las tarjetas lo que hacen es debitar de la cuenta del tarjetahabiente y depositar en la cuenta del hotel. En este apartado, lo importante es cumplir las normativas de seguridad en el uso de tarjetas e identificación de tarjetahabientes para evitar los fraudes.
            .col-md-6
              figure
                img.mb-2(src='@/assets/curso/tema9-slider3.png', alt='Imagen decorativa')
                figcaption The most common forms of payment are credit & debit cards
          .row
            .col-md-6.mb-4.mb-md-0
              h4 <em>Money Collectors</em>
              p
                italic This form of payment is becoming increasingly relevant, since they are the forms of payment used by e-commerce companies. Here can be mentioned: 
              ul.lista-ul--color
                li.mb-1
                  i.fas.fa-atom
                  italic Collect terminals, such as Baloto, Efecty, Todopagos, etc. 
                li.mb-1
                  i.fas.fa-atom
                  italic Digital Wallets: Nequi, Daviplata, Mercado Pago.   
              .division-acento-contenido  
              p.mb-0 Esta forma de pago se está tornando cada vez más relevante, ya que son las formas de pago usadas por las compañías de comercio electrónico. Aquí se pueden mencionar: 
              ul.lista-ul--color
                li.mb-1
                  i.fas.fa-atom
                  | Terminales de recaudo, como Baloto, Efecty, Todopagos, etc.
                li.mb-1
                  i.fas.fa-atom
                  | Billeteras Digitales: Nequi, Daviplata, Mercado Pago. 
            .col-md-6
              figure
                img.mb-2(src='@/assets/curso/tema9-slider4.png', alt='Imagen decorativa')
                figcaption Now the clients have virtual payment methods: Payment Collectors
          .row
            .col-md-6.mb-4.mb-md-0
              h4 <em>Payment Gateways</em>
              p
                italic These forms of payment are made available to customers through:
              ul.lista-ul--color
                li.mb-1
                  i.fas.fa-atom
                  italic Payment links.
                li.mb-1
                  i.fas.fa-atom
                  italic QR Codes.
                li.mb-1
                  i.fas.fa-atom
                  italic Payment buttons.
                li.mb-1
                  i.fas.fa-atom
                  italic Integration to payment gateways.     
              p      
                italic Finally, there are also companies that receive payments using Bitcoin and other virtual currencies. 
              .division-acento-contenido  
              p.mb-0 Estas formas de pago se brindan a los clientes mediante:
              ul.lista-ul--color
                li.mb-1
                  i.fas.fa-atom
                  | Enlaces de pago.
                li.mb-1
                  i.fas.fa-atom
                  | Códigos QR. 
                li.mb-1
                  i.fas.fa-atom
                  | Botones de pago.
                li.mb-1
                  i.fas.fa-atom
                  | Integración a pasarelas de pago.  
              p Para finalizar, hay también compañías que ofrecen pagos mediante Bitcoin y otras monedas virtuales.       
            .col-md-6
              figure
                img.mb-2(src='@/assets/curso/tema9-slider5.png', alt='Imagen decorativa')
                figcaption Now the clients have virtual payments. There are Payment Gateways.


</template>

<script>
export default {
  name: 'Tema9',
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
