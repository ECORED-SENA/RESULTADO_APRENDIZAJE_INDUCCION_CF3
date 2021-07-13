<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
      .titulo-principal__numero
        span 2
      h1.tracking-in-expand Plan de mejoramiento
    p Todos cometemos errores y, gracias a estos, nuestra vida es más grata debido a que esa experiencia nos impulsa a corregir nuestras acciones. El SENA no es ajeno a las oportunidades, por eso, desde el Reglamento del Aprendiz, se contempla esta posibilidad, que aplica tanto al ámbito presencial como virtual y que busca reprogramar al estudiante en actividades complementarias de formación, sin cometer atropellos o estar cargado de subjetividades.

    p Se contemplan dos tipos de planes de mejoramiento:    
    h4.mt-5.tracking-in-expand Académico
    .row.justify-content-center.align-items-center.mt-4      
      .col-lg-8
        p Se trata de una medida adoptada para definir acciones de formación, previo agotamiento de estrategias pedagógicas del instructor e iniciativas del aprendiz.  

        p Es un documento que consigna tareas concertadas entre el aprendiz y el instructor, que se formula durante la ejecución del programa de formación para garantizar el logro de los resultados de aprendizaje.

        p El instructor deberá considerar el cambio de estrategias formativas, puesto que si las utilizadas en un principio no facilitaron del todo el aprendizaje, entonces hay que modificarlas por otras que le den al aprendiz la sensación de novedad, motivación, expectativa y le induzcan a realizarlas, es decir, que se mantienen los resultados deseables, pero se cambian las estrategias y las actividades de formación.

        p No está de más recordar que este es uno de los aspectos delicados en un proceso de formación, pues de él depende una promoción, un reconocimiento o una certificación. Por lo tanto, el instructor debe:      
      .col-lg-4(data-aos="zoom-in")
        img.img-t.img-a(src='@/assets/ilustraciones/img7.svg', alt='') 

    .row.justify-content-center.align-items-center.mt-3      
      .col-lg-10
        .hr-dotted.my-4  
        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta
              span 1
            | Identificar los resultados de aprendizaje que no han sido alcanzados por el aprendiz.
        .hr-dotted.my-4  
        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta
              span 2
            | Establecer las evidencias de aprendizaje que se utilizarán para evaluar el logro del plan.
        .hr-dotted.my-4  
        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta
              span 3
            | Poseer los soportes que identifiquen la formación, el seguimiento, las evaluaciones y los productos recibidos del aprendiz para aportarlos cuando sea necesario a quienes realizan los controles a las ejecuciones de los planes de mejoramiento en un centro de formación.
        .hr-dotted.my-4  
    h4.mt-5.tracking-in-expand Disciplinario
    .row.justify-content-center.align-items-center.mt-3      
      .col-lg-4(data-aos="zoom-in")
        img.img-t.img-a.my-3(src='@/assets/ilustraciones/img8.svg', alt='')          
      .col-lg-8
        p Es una medida adoptada para definir acciones de carácter comportamental, actitudinal o social, para propiciar en el aprendiz cambios en su conducta cuando se le ha impuesto sanción disciplinaria consistente en llamado de atención escrito o condicionamiento de matrícula. 

        p Este plan debe ser firmado por el aprendiz, deberá contemplar la falta cometida y las evidencias de cambio que se esperan a partir de la concertación respectiva. 

        p Será responsabilidad del instructor, o del coordinador que haya designado el subdirector de centro en el acto sancionatorio, participar en la definición de este mecanismo, evaluar el avance y el logro de los resultados comportamentales definidos.

</template>

<script>
export default {
  name: 'Tema2',
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
