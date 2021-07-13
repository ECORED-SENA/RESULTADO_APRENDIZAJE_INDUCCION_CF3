<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
      .titulo-principal__numero
        span 1
      h1 Procesos de evaluación SENA	
    .row.justify-content-center.align-items-center       
      .col-lg-7
        .cajon.color-acento-botones.p-4
          p.mb-0 La evaluación diagnóstica se desarrolla durante el inicio del proceso pedagógico y evalúa los conocimientos previos del aprendiz, las aptitudes que este tiene, sus expectativas hacia el programa de formación y su particularidad al aprender. 

        p.mt-4 Una primera etapa se da durante la admisión del aprendiz al programa, y la segunda, durante la etapa de inducción, en la cual el instructor orienta el proceso que llevará a cabo con cada uno de sus aprendices durante el tiempo de formación.

        p La evaluación formativa se desarrolla durante todo el proceso pedagógico. Entre sus características está la evaluación de etapas, basada siempre en una retroalimentación transformativa. Se incorpora al proceso de enseñanza-aprendizaje como una parte dinámica del mismo y permite mejorar o reorientar el proceso mediante la toma de medidas de carácter inmediato.

        p La evaluación sumativa se sitúa puntualmente al final del proceso pedagógico, cuando se requiere evaluar los resultados obtenidos. Su finalidad nunca debe ser medir un producto final, sino una serie de procesos que debieron ser graduales.  

      .col-lg-5(data-aos="zoom-in")
        img.img-t.img-a(src='@/assets/ilustraciones/img2.png', alt='')


    p.text-center.mt-5 #[b En el proceso de evaluación del aprendizaje en el SENA intervienen 3 elementos que permiten complementar el proceso. Estos son: ]

    .row.justify-content-center.align-items-center.mt-3      
      .col-lg-4(data-aos="zoom-in")
        img.img-t.img-a(src='@/assets/ilustraciones/img3.svg', alt='')      
      .col-lg-8
        .hr-dotted.my-4      
        .list
            .list__item
                .list__item__icon
                    img(src="@/assets/ilustraciones/v1.svg", alt="").img-icon 
            .list__txt 
                p.mb-0.m-top #[b Los criterios de evaluación]: constituyen dominios, logros u objetivos que se propone alcancen los aprendices en las diferentes etapas del proceso. Estos criterios surgen de la estructura curricular del programa.       
        .hr-dotted.my-4      
        .list
            .list__item
                .list__item__icon
                    img(src="@/assets/ilustraciones/v1.svg", alt="").img-icon 
            .list__txt 
                p.m-top #[b Las técnicas de evaluación]: integran las formas o maneras sistematizadas que emplea el instructor para recoger la información pertinente que debe dar claridad sobre los avances logrados por sus aprendices.
                p.mb-0 Entre los ejemplos de técnicas de evaluación utilizadas en el SENA están: la observación, los talleres teóricos y las pruebas prácticas.
        .hr-dotted.my-4      
        .list
            .list__item
                .list__item__icon
                    img(src="@/assets/ilustraciones/v1.svg", alt="").img-icon 
            .list__txt 
                p.mb-0.m-top #[b Los instrumentos de evaluación]: componen las herramientas y medios donde se plasman los saberes, haceres y actitudes demostrados por los estudiantes en el proceso formativo. Así como las técnicas de evaluación están en íntima relación con los criterios, los instrumentos están a su vez en relación directa con las técnicas.
        .hr-dotted.mt-4  

    .row.justify-content-center.align-items-center.mt-5       
      .col-lg-12
        .cajon.color-acento-contenido.p-4
          p.mb-0 Las fichas de observación y las listas de chequeo hacen operativa la técnica de observación; los cuestionarios de preguntas abiertas o cerradas están en relación con los talleres teóricos; y las guías operativas, con las pruebas prácticas.  

    h4.mt-5 Evidencias de aprendizaje 
    p Son los elementos que dan cuenta del aprendizaje que van logrando los aprendices. Estas evidencias podrán ser de conocimiento, de proceso o de producto.  A continuación, se describe cada uno de los mismos:

    .tarjeta--container.row.mt-5
      .col-md.tarjeta.color-primario.bg-tarjeta-1.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure(data-aos="zoom-in")
              img.img-2(src='@/assets/ilustraciones/img4.svg', alt='Texto que describa la imagen')
          
        h3.text-white.text-center Evidencias de conocimiento
        p.text-center Son aquellas que expresan el dominio cognitivo del aprendiz, es decir, el manejo que tiene de conceptos, definiciones, teorías, leyes, etc., que fundamentan su saber general en una temática generada.

      .col-md.tarjeta.color-acento-contenido.bg-tarjeta-2.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure(data-aos="zoom-in")
              img.img-1(src='@/assets/ilustraciones/img5.svg', alt='Texto que describa la imagen')
          
        h3.text-white.text-center Evidencias de proceso
        p.text-center Es la verificación de las técnicas, procedimientos y pasos; el uso de equipos herramientas y materiales en la aplicación de conceptos o en la ejecución de procedimientos.

      .col-md.tarjeta.color-primario.bg-tarjeta-1.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure(data-aos="zoom-in")
              img.img-2(src='@/assets/ilustraciones/img6.svg', alt='Texto que describa la imagen')
          
        h3.text-white.text-center  Evidencias de producto
        p.text-center Implica la entrega de resultados acabados, solicitados con anterioridad por el instructor y estipulados en el currículo de formación. 

    p.text-center.mt-5 #[b Estos resultados deben reflejar los criterios y estándares de calidad para ser considerados aceptables.]

</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped></style>
