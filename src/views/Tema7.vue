<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal
      .titulo-principal__numero
        span 7
      h1 <em>Types of Clients</em> / Tipos de Clientes
    
    .row.mb-4
      .col-md-7.mb-4(data-aos="fade-right")
        .row.content-usa.mb-4
          .img-usa
            .div
              img(src='@/assets/curso/bandera-usa.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3
            p 
              italic Each guest is unique, their motivation to travel is specific; therefore, the willingness and attitude of the receptionist is essential to give the quality service that is being sought within the establishment and what each client is paying for.
            p 
              italic Look at the most common types of customers.
        .row.content-esp
          .px-md-5.pt-md-2.pb-md-2.py-2.px-3
            p Cada huésped es único, la motivación de su viaje es específica, por lo que la disposición y actitud del recepcionista es indispensable para dar el servicio de calidad que se espera del establecimiento y por el cual el cliente paga.
            p Observe los tipos de clientes más comunes.
          .img-esp
            .div
              img(src='@/assets/curso/bandera-esp.svg' alt='Bandera ESPAÑA')  
      .col-md-5.mb-4(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema7-img.png', alt='Imagen decorativa')

    TabsF.color-acento-botones.color-naranja.mb-4
      .row.tarjeta.bg-azul.p-4(titulo="<em>Corporate</em> / Corporativo")
        .col-2
          figure
            img(src='@/assets/curso/tema7-tabs1.svg', alt='Imagen decorativa')
        .col-md-10
          h4 <em>Corporate</em> / Corporativo
          p <em>They are customers who travel for work or business reasons, their stay usually does not exceed one week. They tend to be very demanding with service and are usually less price sensitive.</em>
          .division-acento-contenido
          p Son los clientes que viajan por motivos de trabajo o negocios, su permanencia generalmente no excede una semana. Suelen ser muy exigentes con el servicio, y por lo general son menos sensibles al precio.
      .row.tarjeta.bg-azul.p-4(titulo="<em>Senior citizens</em> / Tercera edad")
        .col-2
          figure
            img(src='@/assets/curso/tema7-tabs2.svg', alt='Imagen decorativa')
        .col-md-10
          h4 <em>Senior citizens</em> / Tercera edad
          p <em>Older adults who, due to their availability of time and resources, generally travel for leisure purposes. They are known as the “Boomer” generation.</em>
          .division-acento-contenido
          p Los adultos mayores que por su disponibilidad de tiempo y recursos viajan generalmente con fines de esparcimiento. Se les conoce como la generación <em>“Boomer”</em>.
      .row.tarjeta.bg-azul.p-4(titulo="<em>Families</em> / Familias")
        .col-2
          figure
            img(src='@/assets/curso/tema7-tabs3.svg', alt='Imagen decorativa')
        .col-md-10
          h4 <em>Families</em> / Familias
          p <em>This type of traveler now occurs more frequently, and hotels face the request for the accommodation service for families in holiday seasons or weekends. In this group, the availability of money is tighter, so they are open to listening to all-inclusive offers and multiple accommodations.</em>
          .division-acento-contenido
          p Este tipo de viajero ahora se ve con más frecuencia, y los hoteles afrontan la solicitud del servicio de alojamiento para las familias en temporadas de vacaciones o fines de semana. En este grupo, la disponibilidad de dinero es más ajustada, por lo que son abiertos a escuchar ofertas de todo incluido y a las acomodaciones múltiples.
      .row.tarjeta.bg-azul.p-4(titulo="<em>Diplomats – Government</em> / Diplomáticos - Gobierno ")
        .col-2
          figure
            img(src='@/assets/curso/tema7-tabs4.svg', alt='Imagen decorativa')
        .col-md-10
          h4 <em>Diplomats – Government</em> / Diplomáticos - Gobierno 
          p <em>They are people who work with the state and travel for work, but they have an additional nuance and that is that usually and by the position they hold or the rank they have, their treatment may require a specific protocol, mainly for their safety.</em>
          .division-acento-contenido
          p Son personas que trabajan con el Estado y viajan por trabajo, pero tienen un matiz adicional y es que, por lo general y en virtud del cargo que desempeñan o del rango que tienen, su tratamiento puede requerir un protocolo específico, principalmente por su seguridad.
      .row.tarjeta.bg-azul.p-4(titulo="<em>Groups</em> / Grupos")
        .col-2
          figure
            img(src='@/assets/curso/tema7-tabs5.svg', alt='Imagen decorativa')
        .col-md-10
          h4 <em>Groups</em> / Grupos
          p <em>This type of guests is a congregation of people traveling on the same dates and with similar travel motivations (a convention, a tour, etc.) They have certain specific treatments and services common to all of them.</em>
          .division-acento-contenido
          p Esta tipología de huéspedes es una congregación de personas que viajan en las mismas fechas y con motivaciones de viaje similares (una convención, un tour, etc.). Poseen ciertos tratamientos y servicios específicos comunes a todos ellos.   
      .row.tarjeta.bg-azul.p-4(titulo="<em>Luxury travelers </em> / Viajeros de lujo")
        .col-2
          figure
            img(src='@/assets/curso/tema7-tabs6.svg', alt='Imagen decorativa')
        .col-md-10
          h4 <em>Luxury travelers</em> / Viajeros de lujo
          p <em>These travelers are the ones who have the highest expectations and are willing to pay for the experience. Usually, the price is not a problem for them. They are sophisticated and pay a lot of attention to the value of what they get (value for money).</em>
          .division-acento-contenido
          p Estos viajeros son los que tienen mayores expectativas y están dispuestos a pagar por la experiencia. Por lo general, el precio no es problema para ellos. Son sofisticados y se fijan mucho en el valor de lo que obtienen, (relación calidad/precio).

    p
      italic By identifying these types of travelers, it will be easier for you to address them properly.
    p.mb-5 Si logra identificar estos tipos de viajeros, le será más fácil dirigirse a ellos de una forma adecuada.  

    .h4.subtitulo-naranja.mb-4(data-aos="fade-right") 
      span 
        italic Guest Information / 
        | Información del huésped

    .row.justify-content-center(data-aos="fade-down")
      .col-md-10
        figure
          img(src='@/assets/curso/tema7-img2.png', alt='Imagen decorativa')     

    .row.mb-4
      .col-md-6.g-5.h-100
        .row.content-usa3.bg-naranja-suave.h-100
          .img-usa
            div.position3
              img(src='@/assets/curso/bandera-usa.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3 
            p <em>In the process of taking reservations and during the check-in of foreigners, you must take and provide information to the guest. Understanding and expressing yourself correctly is important. See some information that may be required.</em>
      .col-md-6.g-5.h-100
        .row.content-esp3.bg-azul.h-100
          .img-esp3
            div.position3
              img(src='@/assets/curso/bandera-esp.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3
            p En el proceso de toma de reservas y durante el check-in de extranjeros, se deberá tomar y brindar información al huésped. Entender y expresarse de forma correcta es importante. Observe alguna información que podrá ser requerida.

    AcordeonB.mb-4(tipo="a" clase-tarjeta="tarjeta bg-naranja" data-aos="fade-down")
      .row(titulo="<em>Countries</em> / Países")
        .col-2
          img.px-md-4(src='@/assets/curso/tema7-acord1.svg', alt='Imagen decorativa') 
        .col-md-10
          p 
            italic During check-in and because of the migration information process, the origin and destination of the passenger are inquired. A person will identify himself but will not necessarily come from or go to his or her country of origin.
          .division-acento-contenido  
          p Durante el <em>check-in</em> y de cara al proceso de información migratoria, se indaga sobre la procedencia y el destino del pasajero. Una persona se identificará, pero no necesariamente vendrá o se dirigirá a su país de origen. 
      .row(titulo="<em>Nationalities</em> / Nacionalidades")
        .col-2
          img.px-md-4(src='@/assets/curso/tema7-acord2.svg', alt='Imagen decorativa') 
        .col-md-10
          p 
            italic In the same way, at check-in you must enter the nationality information. At this point, the recommendation is to check if the person has dual nationality, as this can affect the management of billing and taxes.
          .division-acento-contenido  
          p De la misma forma, durante el registro usted deberá ingresar la información de nacionalidad. En este punto, la recomendación es revisar si la persona cuenta con doble nacionalidad, ya que esto puede afectar la gestión de facturación e impuestos.
      .row(titulo="<em>Personal information</em> / Información personal")
        .col-2
          img.px-md-4(src='@/assets/curso/tema7-acord3.svg', alt='Imagen decorativa') 
        .col-md-10
          p 
            italic The personal information of guests is sensitive. Remember that this is protected by confidentiality and privacy laws, so you should only inquire about the necessary and relevant data for your work. (Address, phone number, e-mail, marital status). 
          .division-acento-contenido  
          p La información personal de los huéspedes, es delicada. Recuerde que esta está protegida por leyes de confidencialidad y privacidad, por lo que solo debe indagar por los datos necesarios y relevantes para su trabajo. (Dirección, número de teléfono, correo electrónico, estado civil). 
      .row(titulo="<em>Documents</em> / Documentos")
        .col-2
          img.px-md-4(src='@/assets/curso/tema7-acord4.svg', alt='Imagen decorativa') 
        .col-md-10
          p 
            italic The identity documents must comply with the current rules of identification and acceptance by the hotel. You must keep abreast of developments in this regard. Always be attentive to the originality of the documentation presented, and if you have any news about it, be prudent with the handling of this.
          .division-acento-contenido  
          p Los documentos de identidad deben cumplir con las normas vigentes de identificación y aceptación por parte de hotel. Su deber es mantenerse al tanto de las novedades en este sentido. Esté siempre atento a la originalidad de la documentación presentada y si tiene alguna novedad al respecto, sea prudente con el manejo de esta.
      .row(titulo="<em>Purpose of the trip</em> / Propósito del viaje")
        .col-2.px-md-3
          img.px-md-4(src='@/assets/curso/tema7-acord5.svg', alt='Imagen decorativa') 
        .col-md-10
          p 
            italic It will help you reveal what type of traveler is the one in front of you, and meet the requirements and requests accordingly.
          .division-acento-contenido  
          p Le ayudará a develar el tipo de viajero que tiene enfrente y, de esta forma, atender los requerimientos y solicitudes adecuadamente.
      .row(titulo="<em>Credit card number</em> / Número de tarjeta de crédito")
        .col-2
          img.px-md-4(src='@/assets/curso/tema7-acord6.svg', alt='Imagen decorativa') 
        .col-md-10
          p 
            italic This is another extremely sensitive item. Taking the data correctly can make the difference between being able to collect an account or not. On the other hand, keeping financial data secure is a very high responsibility. The recommendation is to follow the management protocols. 
          .division-acento-contenido  
          p Este es otro elemento extremadamente sensible. Tomar los datos de manera correcta puede hacer la diferencia entre poder cobrar una cuenta o no. Por otro lado, mantener los datos financieros seguros es una responsabilidad muy grande. La recomendación es seguir los protocolos de manejo. 
      .row(titulo="<em>Schedules</em> / Horarios")
        .col-2
          img.px-md-4(src='@/assets/curso/tema7-acord7.svg', alt='Imagen decorativa') 
        .col-md-10
          p 
            italic Reporting schedules is also a common activity, so knowing how to express the time will be useful.
          .division-acento-contenido  
          p Informar horarios es también una actividad común, por lo que conocer la forma de expresar el tiempo le será útil.                




    .row.justify-content-center
      .col-md-10
        .tarjeta.color-acento-botones.p-3
          .row.justify-content-around.align-items-center.px-md-3
            .col-3.col-sm-2.col-lg-2
              img.px-md-4(src="@/assets/curso/tema7-cta.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-2 Lista de Países y Nacionalidades en inglés
                  p.mb-0.text-small Se le invita a revisar el siguiente documento de listas de países
                  p.mb-0.text-small Anexo_1 - Lista de Países y Nacionalidades en inglés (Aprende Inglés con Sila, 2021)
                .col-sm-auto
                  a.boton.color-primario(:href="obtenerLink('/downloads/Anexo_1-Lista-de-paises-ingles_español.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download       

</template>

<script>
import AcordeonB from '../components/AcordeonB'
import TabsF from '../components/TabsF'
export default {
  name: 'Tema7',
  components: {
    TabsF,
    AcordeonB,
  },
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
