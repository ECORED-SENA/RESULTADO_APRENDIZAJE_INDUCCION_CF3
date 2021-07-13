<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
      .titulo-principal__numero
        span 4
      h1.tracking-in-expand Deserciones
    .row.justify-content-center.align-items-center
      .col-lg-5(data-aos="zoom-in")
        img.img-t.img-a(src='@/assets/ilustraciones/img13.svg', alt='')       
      .col-lg-7
        p Según el Reglamento del Aprendiz, el estudiante, como gestor principal de su proceso de formación, debe participar de manera activa y oportuna en las diferentes actividades, presenciales y/o virtuales, que conforman la ruta de aprendizaje.

        p.tracking-in-expand #[b De acuerdo con el documento, las siguientes causales generan deserción:]
        .hr-dotted.my-4
        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta
              span a
            | Cuando el aprendiz injustificadamente no se presenta por tres (3) días consecutivos al centro o empresa en su proceso formativo (aplica para aprendices de formación presencial).
        .hr-dotted.my-4  
        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta
              span b
            | Cuando, al terminar el periodo de aplazamiento aprobado por el SENA, el aprendiz no reingresa al programa de formación.
        .hr-dotted.my-4  
        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta
              span c
            | Cuando transcurridos dos (2) años contados a partir de la fecha de terminación de la etapa lectiva del programa, el aprendiz no ha presentado la evidencia de la realización de la etapa productiva.
        .hr-dotted.my-4     

    .row.justify-content-center.align-items-center.mt-5       
      .col-lg-12
        .cajon.color-acento-contenido.p-4
          p.mb-0 Cuando el aprendiz se encuentre incurso en alguna de estas situaciones, el instructor, o el funcionario responsable del seguimiento respectivo, reportará inmediatamente el caso al coordinador académico.               

    .row.justify-content-center.align-items-center.mt-5
      .col-lg-8
        p Este último, a su vez, enviará una comunicación al aprendiz a la dirección domiciliaria registrada en el sistema de gestión de información requiriéndole para que justifique plenamente el incumplimiento, aportando los soportes respectivos dentro de los cinco (5) días hábiles siguientes al envío.

        p Si el aprendiz no da respuesta dentro del término establecido o no aporta las evidencias que justifiquen plenamente el incumplimiento, el subdirector de centro suscribirá el acto académico que declara la deserción en el proceso y ordena la respectiva cancelación de matrícula, acto administrativo debidamente notificado al aprendiz, para que dentro de los términos de ley presente el recurso de reposición ante el subdirector de centro.

        p Una vez esté en firme la decisión, deberá ser registrada la novedad en el sistema de gestión académica.  La cancelación de la matrícula implica que el aprendiz no pueda participar en procesos de ingreso a la institución en programas de formación titulada dentro de los seis (6) meses siguientes, contados a partir del registro de la novedad en el sistema de gestión de la formación.      
      .col-lg-4(data-aos="zoom-in")
        img.img-t.img-a(src='@/assets/ilustraciones/img14.svg', alt='')       

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
