<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal
      .titulo-principal__numero
        span 1
      h1 <em>Rates </em> / Tarifas

    .row.mb-4
      .col-md-7.mb-4(data-aos="fade-right")
        .row.content-usa.mb-4
          .img-usa
            .div
              img(src='@/assets/curso/bandera-usa.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3
            p 
              italic It is the value paid by hotel users in exchange for the product or service they use. The rates are composed of the price and other additional concepts and are governed by the supply and demand game in the touristic market. Hotels have various types of rates depending on the market segment they are targeting. Look at some of them.
        .row.content-esp
          .px-md-5.pt-md-2.pb-md-2.py-2.px-3
            p Es el valor que pagan los usuarios del hotel a cambio del producto o servicio que utilizan. Las tarifas se componen del precio y otros conceptos adicionales, y se rigen por el juego de la oferta y la demanda en el mercado turístico. Los hoteles tienen varios tipos de tarifas dependiendo del segmento de mercado al que se dirigen. Observe algunas de ellas.
          .img-esp
            .div
              img(src='@/assets/curso/bandera-esp.svg' alt='Bandera ESPAÑA')  
      .col-md-5(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema1-img1.png', alt='Imagen decorativa')    
   
    AcordeonB.mb-4(tipo="a" clase-tarjeta="tarjeta bg-naranja")
      .row(titulo="<em>Rack Rate</em> / Tarifa <em>Rack</em>")
        .col-md-2
          img.px-md-4(src='@/assets/curso/tema1-acord1.svg', alt='Imagen decorativa') 
        .col-md-10
          p 
            italic It is the official rate charged by the hotel, to which no discount applies. It serves as a reference for rate management.
          .division-acento-contenido  
          p Es la tarifa oficial que cobra el hotel, a la cual no se aplica ningún descuento. Sirve de referencia para el manejo de tarifas.   
      .row(titulo="<em>Net or Floor Rate</em> / Tarifa Neta o de Piso")
        .col-md-2
          img.px-md-3(src='@/assets/curso/tema1-acord2.svg', alt='Imagen decorativa') 
        .col-md-10
          p 
            italic This is the fee that is assigned to intermediaries, such as travel agencies, bed banks and marketing platforms, on which they can generate their profit or mark-up.
          .division-acento-contenido  
          p Esta es la tarifa que se asigna a intermediarios como agencias de viaje, bancos de camas y plataformas de marketing, sobre la cual ellos pueden generar su utilidad o sobreprecio. 
      .row(titulo="<em>Confirmed Rate</em> / Tarifa Confirmada")
        .col-md-2
          img.px-md-3(src='@/assets/curso/tema1-acord3.svg', alt='Imagen decorativa') 
        .col-md-10
          p 
            italic It is the rate that was informed to the client at the time of booking. If when the guest arrives there is not available room according to the confirmed rate, another one of better category is usually given for the same price, which means doing an upgrade.
          .division-acento-contenido  
          p Es la tarifa que se le informó al cliente al momento de la reserva. Si al llegar el huésped no hay disponible una habitación acorde con la tarifa confirmada, se suele dar otra de mejor categoría por el mismo precio, lo que significa hacer una mejora.
      .row(titulo="<em>Negotiated Rate</em> / Tarifa Negociada")
        .col-md-2
          img.px-md-3(src='@/assets/curso/tema1-acord4.svg', alt='Imagen decorativa') 
        .col-md-10
          p 
            italic This one has a discount on the rack rate and some conditions on its granting. It usually occurs only in negotiations with companies, agencies, associations, among others, based on a minimum production of nights per month. 
          .division-acento-contenido  
          p Esta tiene un descuento sobre la tarifa <em>rack</em> y unas condiciones en su otorgamiento. Por lo general, se da solo en negociaciones con empresas, agencias, asociaciones, entre otras, con base en una producción mínima de noches por mes.
      .row(titulo="<em>Complementary</em> / Tarifa Complementaria")
        .col-md-2
          img.px-md-3(src='@/assets/curso/tema1-acord5.svg', alt='Imagen decorativa') 
        .col-md-10
          p 
            italic They are the rates granted to certain entities or people who represent some interest for the hotel. For example: other hotels, associations, conglomerates with defined conditions, hotel employees, friends and family, etc.
          .division-acento-contenido  
          p Son las tarifas que se otorgan a determinadas entidades o personas que representan algún interés para el hotel. Por ejemplo: otros hoteles, asociaciones, conglomerados con condiciones delimitadas, empleados del hotel, amigos y familiares, etc.
      .row(titulo="<em>Promotional Rates</em> / Tarifas Promocionales")
        .col-md-2
          img.px-md-3(src='@/assets/curso/tema1-acord6.svg', alt='Imagen decorativa') 
        .col-md-10
          p 
            italic They are discounts which are applied for hotel promotion purposes, following some policies and restrictions. Example: non-refundable rates, children under 12 do not pay, pay 3 nights and stay 4. 
          .division-acento-contenido  
          p Son descuentos que se aplican para fines de promoción del hotel, siguiendo unas políticas y restricciones. Ejemplo: tarifas no reembolsables, menores de 12 años no pagan, pague 3 noches y hospédese 4.  
      .row(titulo="<em>BAR Rate</em> / Tarifa BAR")
        .col-md-2
          img.px-md-3(src='@/assets/curso/tema1-acord7.svg', alt='Imagen decorativa') 
        .col-md-10
          p 
            italic With the increase in distribution channels, there was a time when the hotelier lost control over his price. It was common to see clients arriving at the hotel who had found, through an intermediary, a lower rate than the one offered directly by the hotel. To solve this problem, strengthen direct sales, and increase rate transparency, hoteliers began to publish the BAR (Best Available Rate) on their websites. The Best Available Rate guarantees that a lower rate will not be found in any distribution channel.  The management of this type of rate is not only about price, but also about the value of the rate.
          .division-acento-contenido  
          p Con el aumento de los canales de distribución, hubo un momento en que el hotelero perdió el control sobre su precio. Era usual que llegaran clientes al hotel que habían encontrado, a través de un intermediario, una tarifa inferior que la ofrecida directamente por el hotel. Para dar solución a esta problemática, fortalecer la venta directa y aumentar la transparencia de las tarifas, los hoteleros comenzaron a publicar en sus webs la <em>BAR (Best Available Rate,</em> en inglés). La mejor tarifa disponible garantiza que no se va a encontrar una tarifa inferior en ningún canal de distribución.  El manejo de este tipo de tarifas no tiene que ver solo con precio, sino con el valor de la tarifa.
      .row(titulo="<em>Group Rates </em> / Tarifa Grupo o Evento")
        .col-md-2
          img.px-md-3(src='@/assets/curso/tema1-acord8.svg', alt='Imagen decorativa') 
        .col-md-10
          p 
            italic These rates are created based on availability and market conditions at the time the quote is requested. And they apply to groups or special events, for example, fairs, concerts, congresses.
          .division-acento-contenido  
          p Estas tarifas se crean con base en la disponibilidad y las condiciones de mercado del momento en que se pide la cotización. Y aplican para grupos o eventos especiales, por ejemplo, ferias, conciertos, congresos.
      .row(titulo="<em>Long Stay Rate</em> / Tarifa Larga Estadía")
        .col-md-2
          img.px-md-3(src='@/assets/curso/tema1-acord9.svg', alt='Imagen decorativa') 
        .col-md-10
          p 
            italic It applies for a minimum number of nights a month. With some frequency, there are people who decide to live in hotels, due to the advantages that this provides them, and are classified as permanent guests.
          .division-acento-contenido  
          p Aplica para un número mínimo de noches al mes. Con alguna frecuencia, hay personas que deciden vivir en hoteles, debido a las ventajas que ello les proporciona, y se catalogan como huéspedes permanentes.
      .row(titulo="<em>Packages or Plans</em> / Paquetes o Planes")
        .col-md-2
          img.px-md-3(src='@/assets/curso/tema1-acord10.svg', alt='Imagen decorativa') 
        .col-md-10
          p 
            italic Packages are a way to market hotel products, to provide customers with more services, for more attractive prices. It can be packaged with own or third-party products. Example: wedding night plan, package with food and tour included.
          .division-acento-contenido  
          p Los paquetes son una forma de comercializar productos hoteleros, para brindar a los clientes más servicios, por precios más atractivos. Se puede empaquetar con productos propios o de terceros. Ejemplo: plan noche de bodas, paquete con alimentación y excursiones incluidas.                

    .row.justify-content-center



    .h4.subtitulo-naranja.mb-4(data-aos="fade-right") 
      span 
        italic Meal Plans / 
        | Planes de alimentación



</template>

<script>
import AcordeonB from '../components/AcordeonB'
export default {
  name: 'Tema1',
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
