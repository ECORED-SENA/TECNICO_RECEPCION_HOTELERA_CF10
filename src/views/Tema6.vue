<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal
      .titulo-principal__numero
        span 6
      h1 <em>Reservations</em> / Reservas

    figure
      img(src='@/assets/curso/tema6-img.png', alt='Imagen decorativa')  

    .row.mb-5
      .col-md-6.g-5.h-100
        .row.content-usa3.bg-naranja-suave.h-100
          .img-usa
            div.position3
              img(src='@/assets/curso/bandera-usa.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3 
            p <em>A reservation is the beginning of the agreement between the hotel and a natural or legal person, which results in the accommodation contract, in which the former undertakes to provide the accommodation service under specified characteristics and the latter undertakes to use this service on the agreed date, making a payment for it. Based on this concept there are some types of reservations in the hotel environment, such as:</em>
      .col-md-6.g-5.h-100
        .row.content-esp3.bg-azul.h-100
          .img-esp3
            div.position3
              img(src='@/assets/curso/bandera-esp.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3
            p Una reserva es el inicio del acuerdo entre el hotel y una persona física o jurídica, que da lugar al contrato de alojamiento, en el que el primero se compromete a prestar el servicio de alojamiento bajo características específicas y el segundo se compromete a utilizar este servicio en la fecha acordada, haciendo un pago por el mismo. Con base en este concepto, existen algunos tipos de reservas en el entorno hotelero, tales como:

    AcordeonC.mb-4(tipo="b" clase-tarjeta="acordeon-c border-bottom" data-aos="fade-down")
      .row(titulo="<em>Confirmed Booking (Not Guaranteed) </em> / Reserva confirmada (No Garantizada)")
        .col-md-11
          p 
            italic They are reservations from individuals or intermediaries, in which there is no guarantee. Usually, the hotel sets up a time limit for check-in which usually is at 18:00 hours, after which, if guests do not show up, the reservation is canceled.
          .division-acento-contenido  
          p Son reservas de particulares o intermediarios, en las que no hay garantía. Por lo general, el hotel establece una hora límite para el registro, que generalmente son las 18:00 horas, después de lo cual, si los huéspedes no se presentan, la reserva se cancela.
      .row(titulo="<em>Guaranteed Reservation</em> / Reserva garantizada")
        .col-md-11
          p 
            italic A guaranteed reservation means that the hotel has a guarantee, usually a confirmation letter, a credit card or a deposit, that ensures that, if guests do not show up on the stipulated date, the hotel will charge a predetermined amount. Usually, the first night of accommodation is charged, although this may vary depending on the booking conditions.
          .division-acento-contenido  
          p Una reserva garantizada significa que el hotel tiene una garantía, generalmente una carta de confirmación, una tarjeta de crédito o un depósito, que asegura que, si los huéspedes no se presentan en la fecha estipulada, el hotel cobrará una cantidad predeterminada. Por lo general, se cobra la primera noche de alojamiento, aunque esto puede variar dependiendo de las condiciones de reserva.
      .row(titulo="<em>Provisional Reservation (tentative)</em> / Reserva provisional (tentativa)")
        .col-md-11
          p 
            italic It is a reservation that is made to then be confirmed or guaranteed. In case of no movement happening with the reservation within a previously stipulated period, the reservation is canceled.
          .division-acento-contenido  
          p Es una reserva que se realiza para luego ser confirmada o garantizada. En caso de que no se produzca ningún movimiento con la reserva dentro de un plazo previamente estipulado, la reserva se cancela.
      .row(titulo="<em>Waiting list booking</em> / Reserva en lista de espera")
        .col-md-11
          p 
            italic When a particular date is fully sold, i.e., occupancy for that night is projected at one hundred percent (100%) of the rooms. In this case the hotel, according to its policy, can receive additional reservations, which will go to a waiting list. In practice, this means that, if any of the previously registered reservations are not submitted, the reservations on the waiting list will come in to replace those reservations.
          .division-acento-contenido  
          p Cuando una fecha en particular se vende por completo, es decir, la ocupación para esa noche se proyecta en cien por ciento (100%) de las habitaciones. En este caso, el hotel, de acuerdo con sus políticas, puede recibir reservas adicionales, que irán a una lista de espera. En la práctica, esto significa que, si no se presenta alguna de las reservas previamente registradas, las reservas en la lista de espera entrarán en sustitución de dichas reservas.
      .row(titulo="<em>V.I.P. Reservations</em> / Reservas V.I.P.")
        .col-md-11
          p 
            italic Within hotel slang, the acronym VIP (Very Important Person) is used to identify the reservations of people who require special attention because of their status. These reservations require special attention from all areas of the hotel to ensure the provision of excellent service.
          .division-acento-contenido  
          p Dentro del argot hotelero, el acrónimo VIP (Very Important Person) se utiliza para identificar las reservas de personas que requieren especial atención por su estatus. Estas reservas requieren una atención especial de todas las áreas del hotel para garantizar la prestación de un servicio excelente.
      .row(titulo="<em>Group Bookings</em> / Reservas de grupo")
        .col-md-11
          p 
            italic They are usually bookings they make for groups of more than ten (10) rooms arriving on a date and guaranteed by a company or travel agency. The group’s operating conditions are stipulated in previous contracts.
          .division-acento-contenido  
          p Suelen ser reservas que se realizan para grupos de más de diez (10) habitaciones que llegan en una fecha y están garantizadas por una empresa o agencia de viajes. Las condiciones de operación del grupo están estipuladas en contratos anteriores.
      .row(titulo="<em>Canceled Bookings</em> / Reservas canceladas")
        .col-md-11
          p 
            italic  These reservations are generated either by direct request of the customers in case of not being able to honor the reservation or by the hotel due to a special situation which will force it to give it the proper management according to the established policies.
          .division-acento-contenido  
          p Estas reservas se generan bien por petición directa de los clientes, en caso de no poder cumplir con la reserva, o por el hotel, debido a una situación especial que les obligará a darle el manejo adecuado de acuerdo con las políticas establecidas.
      .row(titulo="<em>Allotment</em> / Allotment")
        .col-md-11
          p 
            italic In the hotel business, it is the agreement or negotiation with companies, travel agents or airlines, in which these are assigned with a certain number of rooms daily, which are guaranteed, either because they use them or resell them.
          .division-acento-contenido  
          p En el negocio hotelero, es un acuerdo o negociación con empresas, agencias de viajes o aerolíneas, en el que se les asigna un determinado número de habitaciones diarias, que están garantizadas, ya sea porque las utilizan o las revenden.
      .row(titulo="<em>No Show</em> / No Show")
        .col-md-11
          p 
            italic This is not a type of reservation, but it is a condition associated with bookings, and occurs when guaranteed reservations are not presented. This control is very important to carry out since it allows the hotel, among other things, to collect the guarantees, give space to the waiting lists, and use this statistic to complement the forecast.
          .division-acento-contenido  
          p Este no es un tipo de reserva, sino que se trata de una condición asociada a las reservas, y se produce cuando no se presentan las reservas garantizadas. Este control es muy importante de llevar a cabo, ya que permite al hotel, entre otras cosas, recoger las garantías, dar espacio a las listas de espera, utilizar esta estadística para complementar las proyecciones.                        

    .row.justify-content-center.bg-naranja-suave
      .col-md-10.py-5
        .video
          iframe(width="560" height="315" src="https://www.youtube.com/embed/MbPhrvkKgH0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    
    
    Separador


    .titulo-segundo
      h2 6.1 <em>Conditions</em> / Condiciones
    
    .row
      .col-md-7.mb-4(data-aos="fade-right")
        .row.content-usa.mb-4
          .img-usa
            .div
              img(src='@/assets/curso/bandera-usa.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3
            p 
              italic As with any commercial agreement, the reservation is governed by certain conditions. These change according to the policy established by the hotel.
            p 
              italic The most relevant conditions or characteristics that the reservation must have are:
            ul.lista-ul--color
              li.mb-1
                i.fas.fa-atom
                italic.mb-0 Arrival date.
              li.mb-1
                i.fas.fa-atom
                italic.mb-0 Departure date.
              li.mb-1
                i.fas.fa-atom
                italic.mb-0 Confirmed rate.
              li.mb-1
                i.fas.fa-atom
                italic.mb-0 Rate inclusions and non-inclusions.
              li.mb-1
                i.fas.fa-atom
                italic.mb-0 Nature of the reservation (flexible, non-refundable).
              li.mb-1
                i.fas.fa-atom
                italic.mb-0 If advance payment is required and the maximum date to make it.
              li.mb-1
                i.fas.fa-atom
                italic.mb-0 Cancellation Policy.  
              li.mb-1
                i.fas.fa-atom
                italic.mb-0 Acceptance.            
            p 
              italic All these terms and conditions must be contained in a document published on the hotel’s website or delivered to the booking holder at the time of receiving confirmation.
        .row.content-esp
          .px-md-5.pt-md-2.pb-md-2.py-2.px-3
            p Como cualquier acuerdo comercial, la reserva se rige por algunas condiciones. Estas cambian de acuerdo con la política establecida por el hotel.  
            p Las condiciones o características más relevantes que debe tener la reserva son:
            ul.lista-ul--color.mb-4
              li.mb-1
                i.fas.fa-atom
                p.mb-0 Fecha de llegada.
              li.mb-1
                i.fas.fa-atom
                p.mb-0 Fecha de salida.
              li.mb-1
                i.fas.fa-atom
                p.mb-0 Tarifa confirmada.
              li.mb-1
                i.fas.fa-atom
                p.mb-0 Inclusiones y no inclusiones de la tarifa.
              li.mb-1
                i.fas.fa-atom
                p.mb-0 Carácter de la reserva (flexible, no reembolsable).
              li.mb-1
                i.fas.fa-atom
                p.mb-0 Si se requiere pago anticipado y la fecha máxima para realizarlo.
              li.mb-1
                i.fas.fa-atom
                p.mb-0 Política de cancelación.   
              li.mb-1
                i.fas.fa-atom
                p.mb-0 Aceptación.           
            p Todas estos términos y condiciones deben estar contenidos en un documento publicado en la web del hotel o entregado al titular de la reserva al momento de recibir la confirmación.
          .img-esp
            .div
              img(src='@/assets/curso/bandera-esp.svg' alt='Bandera ESPAÑA')  
      .col-md-5.mb-4(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema6-1-img.png', alt='Imagen decorativa')


    Separador


    .titulo-segundo
      h2 6.2 <em>Cancellation Fee</em> / Tarifa de cancelación

    .row
      .col-md-7.mb-4(data-aos="fade-right")
        .row.content-usa.mb-4
          .img-usa
            .div
              img(src='@/assets/curso/bandera-usa.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3
            p 
              italic The cancellation fee is the value stipulated by the accommodation establishment and is charged as compensation in case the reservation is canceled out of the allowed period and the room cannot be re-sold. This value should be described in the cancellation policy. 
            p 
              italic According to the established conditions, the cancellation fee can be a percentage or the total of the stay. The most common penalty is the value of the first night of accommodation.
        .row.content-esp
          .px-md-5.pt-md-2.pb-md-2.py-2.px-3
            p La tarifa de cancelación es el valor estipulado por el establecimiento de alojamiento y que se cobra como compensación en caso de que la reserva sea cancelada fuera del periodo permitido y la habitación no se pueda volver a vender. Este valor debe estar descrito en la política de cancelación. 
            p De acuerdo con las condiciones establecidas, el valor de cancelación puede ser un porcentaje o el total de la estadía. La penalidad más usual es el valor de la primera noche de alojamiento.
          .img-esp
            .div
              img(src='@/assets/curso/bandera-esp.svg' alt='Bandera ESPAÑA')  
      .col-md-5.mb-4(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema6-2-img.png', alt='Imagen decorativa')


    Separador


    .titulo-segundo
      h2 6.3 <em>Policies</em> / Políticas

    figure
      img(src='@/assets/curso/tema6-3-img.png', alt='Imagen decorativa')  

    .row.mb-5
      .col-md-6.g-5.h-100
        .row.content-usa3.bg-naranja-suave.h-100
          .img-usa
            div.position3
              img(src='@/assets/curso/bandera-usa.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3 
            p <em>They are agreements established by management between the guest and the establishment and are aimed to clarify the conditions of service provision and the rules of behavior within the establishment. These rules are mentioned on the registration card that the guest signs at the check-in time. In addition to this, a copy of the rules and regulations should also be arranged in all rooms and posted on the website so that guests read and understand the management policies. This may also include local government policies that have to be followed by the guest.</em>
            p <em>The most common policies and rules are:</em>
      .col-md-6.g-5.h-100
        .row.content-esp3.bg-azul.h-100
          .img-esp3
            div.position3
              img(src='@/assets/curso/bandera-esp.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3
            p Son acuerdos establecidos por la dirección entre el huésped y el establecimiento, y tienen como objetivo aclarar las condiciones de prestación del servicio y las reglas de comportamiento dentro del establecimiento. Estas reglas se mencionan en la tarjeta de registro que el huésped firma a la hora del check-in. Además, también se debe disponer una copia de las reglas y regulaciones en todas las habitaciones y publicarse en el sitio web, para que los huéspedes lean y entiendan las políticas de administración. También se pueden incluir las políticas del gobierno local que el huésped debe seguir.
            p Las políticas y reglas más comunes son:

    .row.justify-content-center
      .col-md-10
        PasosA.color-acento-botones.mb-5(tipo="n")
          .row.align-items-center.px-md-5
            .col-md-2.col-6.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/tema6-paso1.svg', alt='Texto que describa la imagen')
            .col-md-9
              p <em>Fee and cancellation policies</em> / Tarifas y políticas de cancelación
          .row.align-items-center.px-md-5
            .col-md-9.mb-4.mb-md-0
              p <em>Invoice settlement</em> / Liquidación de facturas 
            .col-md-2.col-6
              figure
                img(src='@/assets/curso/tema6-paso2.svg', alt='Texto que describa la imagen')

          .row.align-items-center.px-md-5
            .col-md-2.col-6.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/tema6-paso3.svg', alt='Texto que describa la imagen')
            .col-md-9
              p <em>Baggage Handling Policy</em> / Política de manejo de equipaje
          .row.align-items-center.px-md-5
            .col-md-9.mb-4.mb-md-0
              p <em>Check-in and Check-Out policy</em> / Política de check-in y check-out 
            .col-md-2.col-6
              figure
                img(src='@/assets/curso/tema6-paso4.svg', alt='Texto que describa la imagen')

          .row.align-items-center.px-md-5
            .col-md-2.col-6.mb-4.mb-md-0
              figure
                img.px-md-2(src='@/assets/curso/tema6-paso5.svg', alt='Texto que describa la imagen')
            .col-md-9
              p <em>Guest belongings and forgotten objects</em> / Pertenencias de huéspedes y objetos olvidados
          .row.align-items-center.px-md-5
            .col-md-9.mb-4.mb-md-0
              p <em>Pets</em> / Mascotas
            .col-md-2.col-5
              figure
                img.px-md-2(src='@/assets/curso/tema6-paso6.svg', alt='Texto que describa la imagen')

          .row.align-items-center.px-md-5
            .col-md-2.col-6.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/tema6-paso7.svg', alt='Texto que describa la imagen')
            .col-md-9
              p <em>Hazardous goods</em> / Mercancías peligrosas
          .row.align-items-center.px-md-5
            .col-md-9.mb-4.mb-md-0
              p <em>Property damage</em> / Daños a la propiedad 
            .col-md-2.col-4
              figure
                img.px-md-4(src='@/assets/curso/tema6-paso8.svg', alt='Texto que describa la imagen')

          .row.align-items-center.px-md-5
            .col-md-2.col-6.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/tema6-paso9.svg', alt='Texto que describa la imagen')
            .col-md-9
              p <em>Duties and rights of the hotel</em> / Deberes y Derechos del hotel
          .row.align-items-center.px-md-5
            .col-md-9.mb-4.mb-md-0
              p <em>Duties and rights of the guest</em> / Deberes y derechos del huésped
            .col-md-2.col-6
              figure
                img(src='@/assets/curso/tema6-paso10.svg', alt='Texto que describa la imagen')

          .row.align-items-center.px-md-5
            .col-md-2.col-6.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/tema6-paso11.svg', alt='Texto que describa la imagen')
            .col-md-9
              p <em>Photography and video policy</em> / Política de fotografía y video
          .row.align-items-center.px-md-5
            .col-md-9.mb-4.mb-md-0
              p <em>Local government rules</em> / Normas del gobierno local
            .col-md-2.col-6
              figure
                img(src='@/assets/curso/tema6-paso12.svg', alt='Texto que describa la imagen')

          .row.align-items-center.px-md-5
            .col-md-2.col-6.mb-4.mb-md-0
              figure
                img.px-md-2(src='@/assets/curso/tema6-paso13.svg', alt='Texto que describa la imagen')
            .col-md-9
              p <em>Security and evacuation policy</em> / Política de seguridad y evacuación
          .row.align-items-center.px-md-5
            .col-md-9.mb-4.mb-md-0
              p <em>Privacy, data, and information management policies</em> / Políticas de privacidad, datos y administración de la información 
            .col-md-2.col-6
              figure
                img(src='@/assets/curso/tema6-paso14.svg', alt='Texto que describa la imagen')                                    
            




</template>

<script>
import AcordeonC from '../components/AcordeonC'
export default {
  name: 'Tema6',
  components: {
    AcordeonC,
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
