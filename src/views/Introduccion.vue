<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    figure(data-aos="fade-right")
      img(src='@/assets/template/tema-0-1.png', alt='Texto que describa la imagen')
    p.mt-5(data-aos="fade-down") Para el proceso de implementación de una estrategia de gestión de la seguridad en una organización, se sugiere hacer uso y aplicación de la norma ISO/IEC 27001:2013, ya que esta norma brinda los lineamientos e instrucciones para su establecimiento. Además de presentar los fundamentos y aspectos más relevantes para su implementación, ofrece bajo su anexo A, un esquema de controles de seguridad, los cuales buscan abordar los aspectos más importantes para su adopción en el aseguramiento de los activos de información, mediante el establecimiento de los objetivos de seguridad.
    .row.mt-5
      .col-12.col-lg-10(data-aos="fade-right")
        .cajon.color-acento-contenido.p-4.mb-4.mb-lg-0
          p Le invitamos a hacer estudio de este componente formativo, activando todos los recursos didácticos que aquí se presentan, visitando los materiales complementarios que se le sugieren, analizando cada uno de los aspectos conceptuales y prácticos que se mostrarán y que darán línea al fortalecimiento de sus habilidades en la elaboración y aplicación de la estrategia de seguridad de información y ciberseguridad para su organización o empresa. 
          p.mt-2 #[strong ¡Adelante!]
      .col-4.col-lg-2.offset-4.offset-lg-0(data-aos="fade-left")
        figure
          img(src='@/assets/template/tema-0-2.svg', alt='Texto que describa la imagen').floating 

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
    mostrarIndicador: true,
    modal1: false,
    modal2: false,
  }),
}
</script>

<style lang="sass" scoped>
.introduccion
</style>
