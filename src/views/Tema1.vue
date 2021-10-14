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
   
    AcordeonB.mb-4(tipo="a" clase-tarjeta="tarjeta bg-naranja" data-aos="fade-down")
      .row(titulo="<em>Rack Rate</em> / Tarifa <em>Rack</em>")
        .col-md-1
          img(src='@/assets/curso/tema1-acord1.svg', alt='Imagen decorativa') 
        .col-md-10
          p 
            italic It is the official rate charged by the hotel, to which no discount applies. It serves as a reference for rate management.
          .division-acento-contenido  
          p Es la tarifa oficial que cobra el hotel, a la cual no se aplica ningún descuento. Sirve de referencia para el manejo de tarifas.   
      .row(titulo="<em>Net or Floor Rate</em> / Tarifa Neta o de Piso")
        .col-md-1
          img(src='@/assets/curso/tema1-acord2.svg', alt='Imagen decorativa') 
        .col-md-10
          p 
            italic This is the fee that is assigned to intermediaries, such as travel agencies, bed banks and marketing platforms, on which they can generate their profit or mark-up.
          .division-acento-contenido  
          p Esta es la tarifa que se asigna a intermediarios como agencias de viaje, bancos de camas y plataformas de marketing, sobre la cual ellos pueden generar su utilidad o sobreprecio. 
      .row(titulo="<em>Confirmed Rate</em> / Tarifa Confirmada")
        .col-md-1
          img(src='@/assets/curso/tema1-acord3.svg', alt='Imagen decorativa') 
        .col-md-10
          p 
            italic It is the rate that was informed to the client at the time of booking. If when the guest arrives there is not available room according to the confirmed rate, another one of better category is usually given for the same price, which means doing an upgrade.
          .division-acento-contenido  
          p Es la tarifa que se le informó al cliente al momento de la reserva. Si al llegar el huésped no hay disponible una habitación acorde con la tarifa confirmada, se suele dar otra de mejor categoría por el mismo precio, lo que significa hacer una mejora.
      .row(titulo="<em>Negotiated Rate</em> / Tarifa Negociada")
        .col-md-1
          img(src='@/assets/curso/tema1-acord4.svg', alt='Imagen decorativa') 
        .col-md-10
          p 
            italic This one has a discount on the rack rate and some conditions on its granting. It usually occurs only in negotiations with companies, agencies, associations, among others, based on a minimum production of nights per month. 
          .division-acento-contenido  
          p Esta tiene un descuento sobre la tarifa <em>rack</em> y unas condiciones en su otorgamiento. Por lo general, se da solo en negociaciones con empresas, agencias, asociaciones, entre otras, con base en una producción mínima de noches por mes.
      .row(titulo="<em>Complementary</em> / Tarifa Complementaria")
        .col-md-1
          img(src='@/assets/curso/tema1-acord5.svg', alt='Imagen decorativa') 
        .col-md-10
          p 
            italic They are the rates granted to certain entities or people who represent some interest for the hotel. For example: other hotels, associations, conglomerates with defined conditions, hotel employees, friends and family, etc.
          .division-acento-contenido  
          p Son las tarifas que se otorgan a determinadas entidades o personas que representan algún interés para el hotel. Por ejemplo: otros hoteles, asociaciones, conglomerados con condiciones delimitadas, empleados del hotel, amigos y familiares, etc.
      .row(titulo="<em>Promotional Rates</em> / Tarifas Promocionales")
        .col-md-1
          img(src='@/assets/curso/tema1-acord6.svg', alt='Imagen decorativa') 
        .col-md-10
          p 
            italic They are discounts which are applied for hotel promotion purposes, following some policies and restrictions. Example: non-refundable rates, children under 12 do not pay, pay 3 nights and stay 4. 
          .division-acento-contenido  
          p Son descuentos que se aplican para fines de promoción del hotel, siguiendo unas políticas y restricciones. Ejemplo: tarifas no reembolsables, menores de 12 años no pagan, pague 3 noches y hospédese 4.  
      .row(titulo="<em>BAR Rate</em> / Tarifa BAR")
        .col-md-1
          img(src='@/assets/curso/tema1-acord7.svg', alt='Imagen decorativa') 
        .col-md-10
          p 
            italic With the increase in distribution channels, there was a time when the hotelier lost control over his price. It was common to see clients arriving at the hotel who had found, through an intermediary, a lower rate than the one offered directly by the hotel. To solve this problem, strengthen direct sales, and increase rate transparency, hoteliers began to publish the BAR (Best Available Rate) on their websites. The Best Available Rate guarantees that a lower rate will not be found in any distribution channel.  The management of this type of rate is not only about price, but also about the value of the rate.
          .division-acento-contenido  
          p Con el aumento de los canales de distribución, hubo un momento en que el hotelero perdió el control sobre su precio. Era usual que llegaran clientes al hotel que habían encontrado, a través de un intermediario, una tarifa inferior que la ofrecida directamente por el hotel. Para dar solución a esta problemática, fortalecer la venta directa y aumentar la transparencia de las tarifas, los hoteleros comenzaron a publicar en sus webs la <em>BAR (Best Available Rate,</em> en inglés). La mejor tarifa disponible garantiza que no se va a encontrar una tarifa inferior en ningún canal de distribución.  El manejo de este tipo de tarifas no tiene que ver solo con precio, sino con el valor de la tarifa.
      .row(titulo="<em>Group Rates </em> / Tarifa Grupo o Evento")
        .col-md-1
          img(src='@/assets/curso/tema1-acord8.svg', alt='Imagen decorativa') 
        .col-md-10
          p 
            italic These rates are created based on availability and market conditions at the time the quote is requested. And they apply to groups or special events, for example, fairs, concerts, congresses.
          .division-acento-contenido  
          p Estas tarifas se crean con base en la disponibilidad y las condiciones de mercado del momento en que se pide la cotización. Y aplican para grupos o eventos especiales, por ejemplo, ferias, conciertos, congresos.
      .row(titulo="<em>Long Stay Rate</em> / Tarifa Larga Estadía")
        .col-md-1
          img(src='@/assets/curso/tema1-acord9.svg', alt='Imagen decorativa') 
        .col-md-10
          p 
            italic It applies for a minimum number of nights a month. With some frequency, there are people who decide to live in hotels, due to the advantages that this provides them, and are classified as permanent guests.
          .division-acento-contenido  
          p Aplica para un número mínimo de noches al mes. Con alguna frecuencia, hay personas que deciden vivir en hoteles, debido a las ventajas que ello les proporciona, y se catalogan como huéspedes permanentes.
      .row(titulo="<em>Packages or Plans</em> / Paquetes o Planes")
        .col-md-1
          img(src='@/assets/curso/tema1-acord10.svg', alt='Imagen decorativa') 
        .col-md-10
          p 
            italic Packages are a way to market hotel products, to provide customers with more services, for more attractive prices. It can be packaged with own or third-party products. Example: wedding night plan, package with food and tour included.
          .division-acento-contenido  
          p Los paquetes son una forma de comercializar productos hoteleros, para brindar a los clientes más servicios, por precios más atractivos. Se puede empaquetar con productos propios o de terceros. Ejemplo: plan noche de bodas, paquete con alimentación y excursiones incluidas.                

    .row.justify-content-center.mb-5
      .col-md-5.mx-1.p-4.px-md-5.border-naranja.bg-azul.mb-3(data-aos="fade-down") 
        .row.content-usa2.mb-4
          .img-usa
            .div.position2
              img(src='@/assets/curso/bandera-usa.svg' alt='Bandera USA')
        h4.text-center Many elements influence the rate setup:
        ul.lista-ul--color.mb-0
          li.mb-1
            i.fas.fa-atom
            italic Hotel category
          li.mb-1 
            i.fas.fa-atom
            italic Type of hotel
          li.mb-1 
            i.fas.fa-atom
            italic Season
          li.mb-1 
            i.fas.fa-atom
            italic Day of the week
          li.mb-1 
            i.fas.fa-atom
            italic Stay Length
          li.mb-1 
            i.fas.fa-atom
            italic Hotel location
          li.mb-1 
            i.fas.fa-atom
            italic Location within the hotel
          li.mb-1 
            i.fas.fa-atom
            italic Room type
          li.mb-1 
            i.fas.fa-atom
            italic Meal plan
          li.mb-1 
            i.fas.fa-atom
            italic Discounts     
          li.mb-1 
            i.fas.fa-atom
            italic Individual or group client    
      .col-md-5.mx-1.p-4.px-md-5.border-naranja.bg-azul.mb-3(data-aos="fade-left")
        .row.content-esp2.mb-4
          .img-esp
            .div.position2
              img(src='@/assets/curso/bandera-esp.svg' alt='Bandera ESPAÑA')  
        h4.text-center Muchos elementos influyen en la configuración de las tarifas:
        ul.lista-ul--color.mb-0
          li.mb-1
            i.fas.fa-atom
            | Categoría del hotel
          li.mb-1 
            i.fas.fa-atom
            | Tipo de hotel
          li.mb-1 
            i.fas.fa-atom
            | Temporada
          li.mb-1 
            i.fas.fa-atom
            | Día de la semana
          li.mb-1 
            i.fas.fa-atom
            | Duración de la estancia
          li.mb-1 
            i.fas.fa-atom
            | Ubicación del hotel
          li.mb-1 
            i.fas.fa-atom
            | Ubicación dentro del hotel
          li.mb-1 
            i.fas.fa-atom
            | Tipo de habitación
          li.mb-1 
            i.fas.fa-atom
            | Plan de comidas
          li.mb-1 
            i.fas.fa-atom
            | Descuentos     
          li.mb-1 
            i.fas.fa-atom
            | Cliente individual o grupal            


    .h4.subtitulo-naranja.mb-4(data-aos="fade-right") 
      span 
        italic Meal Plans / 
        | Planes de alimentación

    .row.mb-4
      .col-md-7.mb-4(data-aos="fade-right")
        .row.content-usa.mb-4
          .img-usa
            .div
              img(src='@/assets/curso/bandera-usa.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3
            p 
              italic Hotels offer plans beside to the accommodation, with the purpose of promoting the second line of the hotel industry, which is the sale of food and beverage services.
            p  
              italic Generally, hotels offer the client several plans that are determined by the basic price of the room and the most suitable food option for the client.
        .row.content-esp
          .px-md-5.pt-md-2.pb-md-2.py-2.px-3
            p Los hoteles ofrecen planes junto al alojamiento con el propósito de promover el segundo renglón de la industria hotelera, que es la venta de servicios de alimentos y bebidas. 
            p Generalmente, los hoteles ponen a disposición del cliente varios planes, que están determinados por el precio básico de la habitación y la opción de alimentación más adecuada para el cliente.
          .img-esp
            .div
              img(src='@/assets/curso/bandera-esp.svg' alt='Bandera ESPAÑA')  
      .col-md-5(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema1-img2.png', alt='Imagen decorativa')

    .row.justify-content-center.mb-5
      .col-md-10.bg-azul.p-5
        h4.text-center.mb-5 <em>There are different types of plans</em> / Existen diferentes tipos de planes
        ImagenInfografica.color-acento-botones.mb-5
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/tema1-infografia.svg', alt='Planes de alimentación')

          .tarjeta.color-primario.p-3(x="29.6%" y="24.3%")
            .h5.mb-1 <em>European plan</em>
            p <em>Includes room rate without any food.</em>
            .division-acento-contenido  
            .h5.mb-1 Plan europeo
            p.mb-0 Incluye la tarifa de habitación sin ningún alimento.

          .tarjeta.color-primario.p-3(x="36.6%" y="42.3%")
            .h5.mb-1 <em>Continental plan</em>
            p <em>Includes room rate plus continental breakfast.</em>
            .division-acento-contenido  
            .h5.mb-1 Plan continental
            p.mb-0 Incluye habitación y un desayuno continental.

          .tarjeta.color-primario.p-3(x="50.4%" y="50.3%")
            .h5.mb-1 <em>American plan</em>
            p <em>Includes room rate plus American breakfast + Lunch + Dinner.</em>
            .bg-azul.p-3.mb-3
              p.mb-0
                strong <em>Modified American Plan (PAM): </em>
                | <em>It includes the room and two meals a day, usually breakfast and one of the meals (lunch or dinner).</em>
            .division-acento-contenido  
            .h5.mb-1 Plan Americano
            p Incluye la habitación y tres alimentos.
            .bg-azul.p-3.mb-3
              p.mb-0
                strong <em>Plan Americano Modificado (PAM): </em>
                | <em>Incluye la habitación y dos alimentos diarios, generalmente el desayuno y una de las comidas (almuerzo o cena).</em>


          .tarjeta.color-primario.p-3(x="63.4%" y="41.5%")
            .h5.mb-1 <em>All Inclusive</em>
            p <em>Includes room rate plus American breakfast + Lunch + Dinner.</em>
            .division-acento-contenido  
            .h5.mb-1 Plan todo incluido
            p.mb-0 Incluye tarifa de habitación, desayuno, almuerzo y comida, y actividades programadas. 

          .tarjeta.color-primario.p-3(x="70.4%" y="24.3%")
            .h5.mb-1 <em>Bed & breakfast</em>
            p <em>Includes room rate plus Full breakfast.</em>
            .division-acento-contenido  
            .h5.mb-1 Bed & Breakfast
            p.mb-0 Incluye Cama y Desayuno. Ofrecen habitación con desayuno completo.   



    .h4.subtitulo-naranja.mb-4(data-aos="fade-right") 
      span 
        italic Discounts / 
        | Descuentos

    figure.mb-4(data-aos="fade-down") 
      img(src='@/assets/curso/tema1-img3.png', alt='Imagen decorativa')

    .row.content-usa.mb-4(data-aos="fade") 
      .img-usa
        .div
          img(src='@/assets/curso/bandera-usa.svg' alt='Bandera USA')
      .px-md-5.pb-md-2.pt-5.px-3
        p 
          italic-strong Discounts are a way of promotion. Through this practice, among other things, the hotels can:
        .row.align-items-center.mb-4
          .col-md-4
            ul.lista-ul--color.mb-0
              li.mb-1
                i.fas.fa-atom
                italic Promote the brand
              li.mb-1
                i.fas.fa-atom
                italic Increase the frequency of purchase
              li.mb-1
                i.fas.fa-atom
                italic Increase sales at certain times
              li.mb-1
                i.fas.fa-atom
                italic Increase revenue at peak times     
          .col-md-4.py-3.px-4.bg-naranja
            italic-strong Normally, to access a discount, the client must comply with some rules, which are known as “Terms and conditions”.
        p 
          italic-strong In the market you can find different types of discounts:
        ul.lista-ul--color.mb-0
          li.mb-1
            i.fas.fa-atom
            p <em>Promotional codes: These are codes made up of numbers or letters and that when applied to payment generate a reduction in value. Example: </em>
              italic-strong “GET10”. 
              | <em>The instruction would show something like: </em>
              italic-strong “By entering the code, get a 10% discount on selected items.”
          li.mb-1
            i.fas.fa-atom
            p <em>Discount plans: Here the discount promotes packaged products: </em>
              italic-strong Stay 3 nights x $300 and get all meals for free.
          li.mb-1
            i.fas.fa-atom
            p <em>Discounts on nights: This type of discount is intended to increase occupancy on dates with low demand:  </em>
              italic-strong Pay 3 nights’ accommodation and get the fourth night for free.
          li.mb-1
            i.fas.fa-atom
            p <em>Direct discounts: This type of discount uses the strategy of showing the discount and the original price crossed out, to give the customer the perception that they are benefiting. </em>
              italic-strong Before 
              italic-strong-line $250,000
              italic-strong  - Today $187,500. Save 25%.

    .row.content-esp
      .px-md-5.pt-md-2.pb-md-2.py-2.px-3
        p 
          strong Los descuentos son una forma de promoción. Por medio de esta práctica, se logra, entre otras cosas:
        .row.align-items-center.mb-4
          .col-md-6
            ul.lista-ul--color.mb-0
              li.mb-1
                i.fas.fa-atom
                | Promover la marca
              li.mb-1
                i.fas.fa-atom
                | Aumentar la frecuencia de compra
              li.mb-1
                i.fas.fa-atom
                | Aumentar las ventas en momentos determinados
              li.mb-1
                i.fas.fa-atom
                | Aumentar los ingresos en los momentos pico  
          .col-md-5.py-3.px-4.bg-naranja
            strong Normalmente, para acceder a un descuento, el cliente debe cumplir unas reglas, que se conocen como “Términos y condiciones”. 
        p 
          strong En el mercado, se pueden encontrar diferentes tipos de descuentos:   
        ul.lista-ul--color.mb-0
          li.mb-1
            i.fas.fa-atom
            p Códigos promocionales: Estos son códigos compuestos por números o letras y que, al aplicarse al pago, generan una reducción del valor. Ejemplo: 
              strong “GET10”. 
              | La instrucción mostraría algo como: 
              strong “Al ingresar el código, obtenga un 10% de descuento en artículos seleccionados”.   
          li.mb-1
            i.fas.fa-atom
            p Planes con descuento: Aquí el descuento promueve productos empaquetados: 
              strong Alójese 3 noches x $300 y obtenga todas las comidas gratis.
          li.mb-1
            i.fas.fa-atom
            p Descuentos en noches: Este tipo de descuentos busca aumentar la ocupación en fechas con baja concurrencia: 
              strong Pague 3 noches de alojamiento y obtenga la cuarta noche gratis.
          li.mb-1
            i.fas.fa-atom
            p Descuentos directos: Este tipo de descuentos usa la estrategia de mostrar el descuento y el precio original tachado, para dar la percepción al cliente de que se está beneficiando. 
              strong Antes 
              strong-line $250.000
              strong   -  Hoy $187.500. Ahorre 25%.         
      .img-esp
        .div
          img(src='@/assets/curso/bandera-esp.svg' alt='Bandera ESPAÑA')





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
