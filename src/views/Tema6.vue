<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
      .titulo-principal__numero
        span 6
      h1.tracking-in-expand Seguimiento al desarrollo de la etapa productiva 

    .row.justify-content-center.align-items-center       
      .col-lg-8
        .cajon.color-acento-botones.p-4      
          p Después de cumplir con el periodo de la etapa lectiva, el aprendiz pasa a la etapa productiva, la cual tiene una duración de 864 horas (6 meses) para los programas técnicos y tecnológicos.
          p.mb-0 Cuando el aprendiz ejecuta una alternativa y no ha cumplido con el tiempo, puede complementar con otra alternativa el tiempo faltante. Esto implica previamente realizar el proceso de informar al centro que realizará la etapa productiva para la asignación del instructor de seguimiento. 
      .col-lg-4(data-aos="zoom-in")
        img.img-t.img-a(src='@/assets/ilustraciones/img21.png', alt='')
    h4.mt-5.tracking-in-expand Documentación del desarrollo de la etapa productiva
    .row.justify-content-center.align-items-center.mt-5     
      .col-lg-3(data-aos="zoom-in")
        img.img-t.img-a(src='@/assets/ilustraciones/img22.svg', alt='')
      .col-lg-9
        p Una vez se informa de la alternativa y tiene el aval del coordinador académico, el SENA – Centro de formación le asigna un instructor de seguimiento con el que se establecerán los formatos y evidencias que el aprendiz debe presentar de acuerdo con el plan de trabajo acordado. Estos son: 
        .list
            .list__item
                .list__item__icon
                    img(src="@/assets/ilustraciones/v1.svg", alt="").img-icon 
            .list__txt 
                p.mb-0.m-top Formato 023 planeación, seguimiento, evaluación diligenciada por el ente coformador, aprendiz e instructor de seguimiento.
        .list.mt-4
            .list__item
                .list__item__icon
                    img(src="@/assets/ilustraciones/v1.svg", alt="").img-icon 
            .list__txt 
                p.mb-0.m-top Diligenciamiento y entrega de bitácoras quincenales por el aprendiz.   

    .row.justify-content-center.align-items-center.mt-5       
      .col-lg-12
        .cajon.color-acento-contenido.p-4
          p El instructor técnico delegado para acompañar esta etapa debe revisar diariamente el foro destinado para la etapa productiva y debe responder a las inquietudes de los aprendices en el tiempo estimado.

          p.mb-0 En este espacio los aprendices podrán intercambiar experiencias e información relevante para su proceso de formación.
    h4.mt-5 Registro de los formatos de seguimiento
    p El instructor debe registrar en los formatos de seguimiento los avances del proceso formativo de cada uno de los aprendices, de acuerdo con lo establecido en el procedimiento de ejecución de la formación.
    h4.mt-5 Conferencias web
    p De acuerdo con la planeación realizada con el coordinador académico del centro de formación, debe realizarse como mínimo una conferencia web mensual con el instructor técnico y los aprendices. Al igual que en las demás sesiones sincrónicas, las grabaciones de estas conferencias web deberán estar disponibles en el LMS. 

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
