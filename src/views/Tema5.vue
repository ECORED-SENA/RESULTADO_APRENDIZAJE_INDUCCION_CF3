<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
      .titulo-principal__numero
        span 5
      h1.tracking-in-expand Alternativas de selección etapa productiva 
    p Al finalizar la etapa lectiva, es importante que usted tenga conocimiento sobre el desarrollo de la etapa productiva. Este es el periodo en el cual podrá resolver problemas reales del sector empresarial, aplicar los conocimientos, habilidades y destrezas pertinentes a las competencias del programa de formación, asumiendo metodologías de autogestión. 
    p.text-center.tracking-in-expand #[b Conozca a continuación las diferentes alternativas que puede elegir para realizar en su etapa productiva.] 

    .row.justify-content-center.align-items-center.mt-5
      .col-10(data-aos="flip-up")  
        TabsA.color-acento-botones.mb-5
          .tarjeta.bg-nav.p-5(titulo="Contrato de aprendizaje")
            .row.justify-content-center.align-items-center
              .col-lg-8
                h4 Contrato de aprendizaje
                p.mb-0 Desempeño, a través del Contrato de Aprendizaje, en una de las diferentes empresas obligadas y/o voluntarias, incluida el SENA. La constancia de cumplimiento a satisfacción es expedida por la empresa respectiva.
              .col-lg-4
                img.my-3.yoyo.img-t.img-a(src='@/assets/ilustraciones/img15.svg', alt='Contrato de aprendizaje')       

          .tarjeta.bg-nav.p-5(titulo="Vinculación laboral")
            .row.justify-content-center.align-items-center
              .col-lg-8
                h4 Vinculación laboral
                p.mb-0 Desempeño a través de vinculación laboral o contractual en actividades relacionadas con el programa de formación de conformidad con la normativa dispuesta para contratos de aprendizaje. La constancia de cumplimiento a satisfacción es expedida por la empresa respectiva.
              .col-lg-4
                img.my-3.yoyo.img-3.img-t.img-a(src='@/assets/ilustraciones/img16.svg', alt='Vinculación laboral')  

          .tarjeta.bg-nav.p-5(titulo="Participación en proyectos")
            .row.justify-content-center.align-items-center
              .col-lg-8
                h4 Participación en proyectos productivos
                p.mb-0 Participación en un proyecto productivo, o en SENA – Empresa, o en SENA proveedor SENA. Estos posibilitan la simulación de entornos productivos reales y la aplicación de conocimientos, habilidades y destrezas pertinentes para las competencias del programa, para cumplir con el objetivo de la etapa productiva, donde se concierta sobre las condiciones de estadía, esto es, pago de algún auxilio económico o en especie.  La constancia de cumplimiento a satisfacción la expide el subdirector de centro respectivo. 
              .col-lg-4
                img.my-3.yoyo.img-3.img-t.img-a(src='@/assets/ilustraciones/img17.svg', alt='Participación en proyectos productivos')  

          .tarjeta.bg-nav.p-5(titulo="Apoyo a entidades estatales")
            .row.justify-content-center.align-items-center
              .col-lg-8
                h4 Apoyo a entidades estatales, ONG y S.A.L
                p.mb-0 De apoyo a una institución estatal nacional, territorial, o a una ONG, o a una entidad sin ánimo de lucro, para el desempeño de actividades prácticas asociadas a su programa de formación o el desarrollo de un proyecto productivo en un ambiente de formación facilitado por esta institución, donde el aprendiz hace su propia concertación con la institución sobre las condiciones de estadía. La constancia de cumplimiento a satisfacción de la pasantía la expide el directivo o responsable del proceso del aprendiz en la institución.
              .col-lg-4
                img.my-3.yoyo.img-3.img-t.img-a(src='@/assets/ilustraciones/img18.svg', alt='Apoyo a entidades estatales, ONG y S.A.L')  

          .tarjeta.bg-nav.p-5(titulo="Monitoría")
            .row.justify-content-center.align-items-center
              .col-lg-8
                h4 Monitoría
                p.mb-0 Los aprendices seleccionados apoyan los procesos de formación con actividades complementarias. Debe ser en especialidades tecnológicamente afines a su programa de formación en un centro SENA particular. La constancia de cumplimiento a satisfacción de las actividades de monitoría la expide el subdirector de Centro de acuerdo con las horas asignadas por resolución.
              .col-lg-4
                img.my-3.yoyo.img-3.img-t.img-a(src='@/assets/ilustraciones/img19.svg', alt='Monitoría')  

          .tarjeta.bg-nav.p-5(titulo="Pasantías")
            .row.justify-content-center.align-items-center
              .col-lg-8
                h4 Pasantías
                p.mb-0 Entre las cuales se contempla la asesoría a PYMES como alternativa de etapa productiva.
              .col-lg-4
                img.my-3.yoyo.img-3.img-t.img-a(src='@/assets/ilustraciones/img20.svg', alt='Pasantías')                            

        p.mt-5 #[b Una vez que tenga claro cuál alternativa es más conveniente y que haya comprobado que cumple con los requisitos, el aprendiz debe:]

        .hr-dotted.my-4      
        .list
            .list__item
                .list__item__icon
                    img(src="@/assets/ilustraciones/v1.svg", alt="").img-icon 
            .list__txt 
                p.mb-0.m-top Solicitar a la coordinación de su centro de formación el aval y registro de la alternativa.      
        .hr-dotted.my-4      
        .list
            .list__item
                .list__item__icon
                    img(src="@/assets/ilustraciones/v1.svg", alt="").img-icon 
            .list__txt 
                p.m-top.mb-0 Comunicar todos los datos personales, ficha, fecha de inicio y fin del desarrollo de la etapa productiva, datos de la empresa donde va a desarrollarla, con el fin de que le sea concedido el aval y así poder iniciar la etapa productiva.
        .hr-dotted.my-4            
</template>

<script>
export default {
  name: 'Tema5',
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
