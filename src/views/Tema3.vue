<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 3
      h1 Alcance de los controles de seguridad
    .row.mt-5(data-aos="fade-right")
      .col-2
        figure
          img(src="@/assets/template/tema-3-1.svg", alt="Texto que describa la imagen").floating
      .col-10
        p En el ejercicio para la determinación de los controles que se desean aplicar, es importante determinar el alcance de su implementación, es decir, la efectividad e impacto que puedan llegar a tener sobre los procesos, procedimientos, logro de objetivos y toda otra particularidad de las operaciones de la organización. 
    figure.mt-5(data-aos="fade-left")
      img(src="@/assets/template/tema-3-2.png", alt="Texto que describa la imagen")
    .row.mt-5
      .col-10.col-lg-8.offset-1.offset-lg-2
        .cajon.color-secundario.bg-naranja-claro.p-4(data-aos="fade-right")
          .row
            .col-4.col-lg-3.offset-4.offset-lg-0
              figure
                img(src="@/assets/template/tema-3-3.svg", alt="Texto que describa la imagen")
            .col-12.col-lg-9.align-self-center
              p En otros términos, el alcance de la implementación de los controles, está directamente relacionado con el análisis de riesgos realizados a los activos de información, que busca mitigar dichos riesgos y evitar cualquier nivel de impacto negativo.
    p.my-5(data-aos="fade-right") Diríjase al recurso que aparece a continuación; allí encontrará información amplia e importantísima para el estudio del alcance de los controles de seguridad. Información que necesita para cumplir con los objetivos de este componente formativo. #[strong ¡Adelante!] 
    figure.mb-5
      .video(data-aos="fade-down")
        iframe(width="560" height="315" src="https://www.youtube.com/embed/z_lVBV98AZQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    .row.mt-5
      .col-10.offset-1
        .tarjeta.color-primario.p-3(data-aos="fade-right")
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-2
              img(src="@/assets/template/tema-3-4.svg").w-50.margin-0-auto
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-1 Controles: orientaciones de la norma 
                  p.text-small Para afianzar sus conocimientos en Controles de seguridad, sugeridos por la norma, diríjase a Sistema de bibliotecas del SENA, #[a.color-naranja http://biblioteca.sena.edu.co/.] En el menú “Consulta bibliográfica” seleccione #[strong “Bases de datos”] y encuentre en #[strong “Base de datos ICONTEC”] la norma #[strong.color-naranja ISO/IEC 27001:2013, Anexo A.]  
                .col-sm-auto
                  a.boton.color-secundario(href="http://biblioteca.sena.edu.co/" target="_blank")
                    span Ver
                    i.fas.fa-link


</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    mostrarIndicador: true,
    modal1: false,
    modal2: false,
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
