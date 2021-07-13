<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
      .titulo-principal__numero
        span 3
      h1 Trámites de gestión administrativa
    p Es necesario que el aprendiz reconozca los siguientes trámites que en cualquier momento puede solicitar.  Para cada uno de los casos, el interesado debe elevar una solicitud formal a través de oficio radicado en el centro de formación y registrado en el sistema de gestión de formación.   A continuación, se listan los siguientes:
    .row.justify-content-center.align-items-center.mt-5
      .col-10(data-aos="flip-up")    
        LineaTiempoD.color-primario
          .row.justify-content-center.align-items-center(numero="1" titulo="Traslado")
            .col-md-8.mb-4.mb-md-0
              p.text-small  Se realiza cuando el aprendiz requiere cambio de jornada, de centro de formación, en el mismo programa o en otro que corresponda a la misma red o línea tecnológica.
              p.text-small Para solicitarlo, el interesado debe haber adelantado, como mínimo, el primer trimestre del proceso de formación del programa, y la correspondiente autorización está supeditada a la disponibilidad de cupo que exista en el programa para el cual requiere traslado; además, debe encontrarse a paz y salvo con el centro de formación.
              p.text-small El número de veces del traslado debe estar supeditado al análisis del comité de evaluación y seguimiento del centro de formación. 
              p.text-small Cuando el aprendiz se encuentre sancionado con condicionamiento de matrícula, no se le autorizará traslado ni aplazamiento del proceso de formación.          
            .col-md-4
              img.swing(src='@/assets/ilustraciones/img9.svg', alt='Traslado')

          .row.justify-content-center.align-items-center(numero="2" titulo="Aplazamiento")
            .col-md-8.mb-4.mb-md-0
              p.text-small Es la solicitud para desvincularse temporalmente del programa de formación en el que se encuentra matriculado, por las siguientes causas: incapacidad médica, licencia de maternidad, servicio militar, problemas de seguridad o calamidad doméstica, debidamente demostradas con los respectivos soportes legales.
              p.text-small El aplazamiento será autorizado por el Comité de Evaluación y Seguimiento del centro de formación a través de acto administrativo, por un tiempo máximo de seis (6) meses calendario continuos o discontinuos, de acuerdo con el tiempo de duración del programa, contados a partir de su notificación o respectiva respuesta a la solicitud.
              p.text-small Cuando se trate de aplazamiento por prestación de servicio militar o incapacidad, el Comité podrá autorizarlo por un tiempo superior a los seis meses mientras permanezca en esta situación.          
            .col-md-4
              img.swing(src='@/assets/ilustraciones/img10.svg', alt='Aplazamiento')

          .row.justify-content-center.align-items-center(numero="3" titulo="Reingreso")
            .col-md-8.mb-4.mb-md-0
              p.text-small.text-small Es la solicitud para reanudar su proceso de formación en el programa donde solicitó aplazamiento, y la fecha límite para que el aprendiz reingrese será la indicada en el acto administrativo respectivo. 
              p.text-small.text-small El reingreso está supeditado a que el programa se encuentre en ejecución y a la disponibilidad de cupo. De no existir cupo en el programa en el cual el aprendiz solicitó aplazamiento, el reingreso podrá efectuarse cuando exista disponibilidad de este; en todo caso, se informará por escrito al aprendiz la fecha de reintegro o su imposibilidad.
              p.text-small.text-small Si el programa al que solicita el reingreso no se encuentra vigente en el momento de la solicitud, el Comité de Evaluación y Seguimiento procederá a: *Verificar que el programa vigente corresponda a la misma red, modalidad de formación o línea tecnológica.
              p.text-small.text-small *Analizar cada una de las competencias y resultados de los dos programas para establecer los que le faltan al aprendiz para que continúe en el proceso de formación.        
            .col-md-4
              img.swing(src='@/assets/ilustraciones/img11.svg', alt='Reingreso')

          .row.justify-content-center.align-items-center(numero="4" titulo="Retiro voluntario")
            .col-md-8.mb-4.mb-md-0
              p.text-small  Es la petición para retirarse definitivamente del programa de formación. Implica que el aprendiz no pueda participar en procesos de ingreso a la institución en programas de formación titulada dentro de los seis (6) meses siguientes, contados a partir del registro de la novedad.         
            .col-md-4
              img.swing(src='@/assets/ilustraciones/img12.svg', alt='Retiro voluntario')                            
</template>

<script>
export default {
  name: 'Tema3',
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
