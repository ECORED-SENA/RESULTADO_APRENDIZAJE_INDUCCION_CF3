<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1.tracking-in-expand Introducción
    
    img(data-aos="flip-up").img-t.img-a.bg-2(src='@/assets/ilustraciones/img1.png', alt='')
    .row.justify-content-center.align-items-center.bg-1
      .col-12.p-0
        p.mt-4.px-5 La evaluación del aprendizaje está dirigida, más que a evaluar el conocimiento teórico, a evaluar la aplicación de dicho conocimiento en prácticas reales, con resultados concretos, en el proceso de formación, tanto en la etapa lectiva como en la productiva. Con este fin, el SENA asume las evidencias de aprendizaje como referentes, a partir de los cuales se pueden identificar los logros alcanzados por los alumnos.

        p.mb-4.px-5 Asimismo, se exponen las diversas opciones con las que cuentan los aprendices SENA para el desarrollo y seguimiento de su etapa productiva, en la cual los aprendices logran poner en práctica en contextos reales los conocimientos adquiridos durante su etapa de formación, permitiendo que se fortalezcan sus competencias y que su integración al mundo laboral sea exitosa.   
        .hr
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped>
.introduccion
</style>
