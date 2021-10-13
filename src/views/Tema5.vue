<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal
      .titulo-principal__numero
        span 5
      h1 <em>Titles</em> / Títulos
    
    .row
      .col-md-7.mb-4(data-aos="fade-right")
        .row.content-usa.mb-4
          .img-usa
            .div
              img(src='@/assets/curso/bandera-usa.svg' alt='Bandera USA')
          .px-md-5.pb-md-2.pt-5.px-3
            p 
              italic When talking about titles in English, we refer to the formality with which people are treated according to gender. There are titles of common use and formal titles, which sometimes are referred to the professions and others to the nobility. 
        .row.content-esp
          .px-md-5.pt-md-2.pb-md-2.py-2.px-3
            p Cuando se habla de títulos en inglés, se hace referencia a la formalidad con la que se trata a las personas según el género. Hay títulos de uso común y títulos formales, que a veces se refieren a las profesiones y otros a la nobleza.
          .img-esp
            .div
              img(src='@/assets/curso/bandera-esp.svg' alt='Bandera ESPAÑA')  
      .col-md-5.mb-4(data-aos="fade-left")
        figure
          img(src='@/assets/curso/tema5-img.png', alt='Imagen decorativa')

    TabsD.color-primario.mb-4
      .row.py-4.py-md-5(titulo="" :icono="require('@/assets/curso/tema5-ico1-a.svg')" :icono2="require('@/assets/curso/tema5-ico1-b.svg')")
        .col-md-7
          p <em>Look at the most common titles and how to use them.</em>
          ul.lista-ul--color.mb-4
            li.mb-1
              i.fas.fa-atom
              p.mb-0
                italic-strong Mr. (ʽmɪstɘr) 
                italic is used with the last name of the man; it is not possible to know if he is single or married.
            li.mb-1
              i.fas.fa-atom
              p.mb-0
                italic If we do not know the last name of the man, we must use, 
                italic-strong Sir (ʽsɘr).
            li.mb-1
              i.fas.fa-atom
              p.mb-0
                italic-strong Mrs. (ʽmɪsɪz) 
                italic is used with the last name of a married woman.
            li.mb-1
              i.fas.fa-atom
              p.mb-0
                italic-strong Miss (ʽmɪs) 
                italic is used with the last name to refer to a young and unmarried woman.
            li.mb-1
              i.fas.fa-atom
              p.mb-0
                italic-strong Ms. (ʽmɪz)  
                italic is used with a woman’s last name when it is not possible to know whether she is single or married. It is more professional.           
            li.mb-1
              i.fas.fa-atom
              p.mb-0
                italic If we do not know the last name of the woman, and she looks young, we can say 
                italic-strong Miss (ʽmɪs),  
                 italic and if she looks 30 years or older, we can say  
                italic-strong Ma’am (maəm).
          .division-acento-contenido        
          p Observe los títulos más comunes y cómo usarlos.
          ul.lista-ul--color.mb-4
            li.mb-1
              i.fas.fa-atom
              p.mb-0
                strong Mr. (ʽmɪstɘr)  
                | se utiliza con el apellido del hombre; no es posible saber si es soltero o casado.
            li.mb-1
              i.fas.fa-atom    
              p.mb-0 Si no sabe el apellido del hombre, se debe usar, 
                strong Sir (ʽsɘr).
            li.mb-1
              i.fas.fa-atom
              p.mb-0
                strong Mrs. (ʽmɪsɪz)   
                | se utiliza con el apellido de una mujer casada.
            li.mb-1
              i.fas.fa-atom
              p.mb-0
                strong Miss (ʽmɪs)   
                | se usa con el apellido para referirse a una mujer joven y soltera.
            li.mb-1
              i.fas.fa-atom
              p.mb-0
                strong Ms. (ʽmɪz)   
                | se utiliza con el apellido de una mujer cuando no es posible saber si es soltera o casada. Es más profesional.
            li.mb-1
              i.fas.fa-atom
              p.mb-0 Si no sabe el apellido de la mujer y ella se ve joven, puede decir
                strong Miss (ʽmɪs); 
                | y si se ve de 30 años o más, se puede decir 
                strong Ma’am (maəm).  
        .col-md-5
          figure
            img(src='@/assets/curso/tema5-tab1.png', alt='Imagen decorativa')
      
      .row.py-4.py-md-5(titulo="" :icono="require('@/assets/curso/tema5-ico2-a.svg')" :icono2="require('@/assets/curso/tema5-ico2-b.svg')")
        .col-md-7
          p <em>Now referring to formal titles, these should be used with people who possess dignity, such as kings, queens, ambassadors, presidents. In that case, we use:</em>
          ul.lista-ul--color.mb-4
            li.mb-1
              i.fas.fa-atom
              p.mb-0
                italic-strong Majesty: 
                italic It is the title used to address the monarchs (the Kings and their consorts). It is used preceded by “your”.
            li.mb-1
              i.fas.fa-atom
              p.mb-0
                italic-strong Royal Highness: 
                italic It is the title used to address members of royal families, usually princes or princesses and their consorts. It is used preceded by “His” or “Her”.
            li.mb-1
              i.fas.fa-atom
              p.mb-0
                italic-strong Lord: 
                italic Use this title for male barons, viscounts, counts, and marquises, as well as for some of their sons.
            li.mb-1
              i.fas.fa-atom
              p.mb-0
                italic-strong Lady:   
                italic Used to address female companions with the rank of baroness, viscountess, countess, and marchioness, or wives of men who hold equivalent titles.
            li.mb-1
              i.fas.fa-atom
              p.mb-0
                italic-strong Excellence:   
                italic This is a title of honor given to certain high officials, such as governors, ambassadors, royalty, nobility, and Roman Catholic bishops and archbishops, (preceded by “your”).
            li.mb-1
              i.fas.fa-atom
              p.mb-0
                italic-strong Honorable:   
                italic It is used for judges, mayors, and magistrates in some countries. (Martin, 1990).
          .division-acento-contenido        
          p Ahora refiriéndose a los títulos formales, estos deben ser utilizados con personas que poseen una dignidad, como reyes, reinas, embajadores, presidentes. En ese caso se utiliza:
          ul.lista-ul--color.mb-4
            li.mb-1
              i.fas.fa-atom
              p.mb-0
                strong Majestad:   
                | Es el título utilizado para dirigirse a los monarcas (los Reyes y sus consortes). Se utiliza precedido por “Su”.
            li.mb-1
              i.fas.fa-atom
              p.mb-0
                strong Alteza Real:   
                | Es el título utilizado para dirigirse a los miembros de las familias reales, por lo general, príncipes o princesas y sus consortes. Es utilizado precedido por “Su”.
            li.mb-1
              i.fas.fa-atom
              p.mb-0
                strong Señor:    
                | Use este título para varones masculinos, vizcondes, condes y marqueses, así como para algunos de sus hijos.
            li.mb-1
              i.fas.fa-atom
              p.mb-0
                strong Dama:   
                | Se usa para dirigirse a las compañeras con el rango de baronesa, vizcondesa, condesa y marquesa, o a las esposas de hombres que tienen los títulos equivalentes.
            li.mb-1
              i.fas.fa-atom
              p.mb-0
                strong Excelencia:  
                | Este es un título de honor dado a ciertos altos funcionarios, como gobernadores, embajadores, realeza, nobleza, y obispos y arzobispos católicos romanos (precedidos por “Su”).
            li.mb-1
              i.fas.fa-atom
              p.mb-0
                strong Honorable:    
                | Se utiliza para jueces, alcaldes y magistrados en algunos países.   
        .col-md-5
          figure
            img(src='@/assets/curso/tema5-tab2.png', alt='Imagen decorativa')
      
      .row.py-4.py-md-5(titulo="" :icono="require('@/assets/curso/tema5-ico3-a.svg')" :icono2="require('@/assets/curso/tema5-ico3-b.svg')")
        .col-md-7
          p <em>Finally, there are academic titles, that are used to recognize people with high educational degrees or positions. The most used are:</em>
          ul.lista-ul--color.mb-4
            li.mb-1
              i.fas.fa-atom
              p.mb-0
                italic-strong Dr: (abbreviation for doctor)  
                italic for the holder of a doctoral degree (e.g., PhD, MD) and for medical practitioners, dentists, and veterinary surgeons.
            li.mb-1
              i.fas.fa-atom
              p.mb-0
                italic-strong Professor: 
                italic For a person who holds the academic rank of professor in a university or other institution.
            li.mb-1
              i.fas.fa-atom
              p.mb-0
                italic-strong Chancellor: 
                italic For the chancellor of a university.
            li.mb-1
              i.fas.fa-atom
              p.mb-0
                italic-strong Principal, President, Master, Warden, Dean, Regent, Director, or Chief Executive:  
                italic as appropriate for heads of colleges at the universities.
          .division-acento-contenido        
          p Por último, están los títulos académicos, que se utilizan para reconocer a personas con altos títulos o cargos educativos. Los más utilizados son:
          ul.lista-ul--color.mb-4
            li.mb-1
              i.fas.fa-atom
              p.mb-0
                strong Dr: (abreviatura de doctor)   
                | para el poseedor de un título de doctorado (por ejemplo, PhD, MD) y para médicos, dentistas y veterinarios.
            li.mb-1
              i.fas.fa-atom
              p.mb-0
                strong Profesor:  
                | Para una persona que tiene el rango académico de profesor en una universidad u otra institución.
            li.mb-1
              i.fas.fa-atom
              p.mb-0
                strong Canciller:  
                | Para el canciller de la universidad.
            li.mb-1
              i.fas.fa-atom
              p.mb-0
                strong Director, Presidente, Maestro, Alcaide, Decano, Regente, Rector, Director Ejecutivo:   
                | según corresponda, para los directivos de las universidades.  
        .col-md-5
          figure
            img(src='@/assets/curso/tema5-tab3.png', alt='Imagen decorativa')


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
                  p.mb-0.text-small Se le invita a revisar el siguiente video para complementar la información.
                .col-sm-auto
                  a.boton.color-primario(:href="('https://www.youtube.com/watch?v=4KcBQMsUAok')" target="_blank")
                    span Enlace
                    i.fas.fa-link        

</template>

<script>
import TabsD from '../components/TabsD'
export default {
  name: 'Tema5',
  components: {
    TabsD,
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
