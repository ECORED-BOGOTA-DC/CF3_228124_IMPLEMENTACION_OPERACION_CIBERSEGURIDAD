<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 1
      h1 	 Determinar el contexto
    .row.mt-5(data-aos="fade-right")
      .col-2
        figure
          img(src="@/assets/template/tema-1-1.svg", alt="Texto que describa la imagen").floating
      .col-10
        p En el ejercicio de implementación de estrategias de seguridad en las organizaciones, es conveniente conocer el contexto sobre el cual se realizarán las acciones que buscan el aseguramiento de los activos de información.
        p.mt-4 Este proceso permite:
    .row.mt-5(data-aos="fade-left")
       .col-6.col-lg-3.px-4
        .row.px-2.rounded-20.borde-morado.bg-morado-claro.text-center.h-100.zoom-in
          .col-12.px-1
            figure.pt-4
              img(src="@/assets/template/tema-1-2.svg", alt="Texto que describa la imagen").w-75.margin-0-auto
            .h3.mt-3 Estimar
            p.mt-3.mb-4 Valorar los activos
       .col-6.col-lg-3.px-4
        .row.px-2.rounded-20.borde-naranja.bg-naranja-claro.text-center.h-100.zoom-in
          .col-12.px-1
            figure.pt-4
              img(src="@/assets/template/tema-1-3.svg", alt="Texto que describa la imagen").w-75.margin-0-auto
            .h3.mt-3 Valuar
            p.mt-3.mb-4 Establecer el valor del riesgo presente
       .col-6.col-lg-3.px-4
        .row.px-2.rounded-20.borde-morado.bg-morado-claro.text-center.h-100.zoom-in
          .col-12.px-1
            figure.pt-4
              img(src="@/assets/template/tema-1-4.svg", alt="Texto que describa la imagen").w-75.margin-0-auto
            .h3.mt-3 Dimensionar
            p.mt-3.mb-4 Dimensionar los controles a utilizar
       .col-6.col-lg-3.px-4
        .row.px-2.rounded-20.borde-naranja.bg-naranja-claro.text-center.h-100.zoom-in
          .col-12.px-1
            figure.pt-4
              img(src="@/assets/template/tema-1-5.svg", alt="Texto que describa la imagen").w-75.margin-0-auto
            .h3.mt-3 Identificar 
            p.mt-3.mb-4 Fijar los recursos y tiempo necesario para su implementación
    Separador
    .titulo-segundo.mt-5
      #t_1_1.h2 1.1 Algunos conceptos y estándares orientadores
    figure(data-aos="fade-right")
      img(src="@/assets/template/tema-1-6.png", alt="Texto que describa la imagen")
    .row.mt-5
      .col-2(data-aos="fade-right")
        figure
          img(src="@/assets/template/tema-1-7.png", alt="Texto que describa la imagen").floating
      .col-6(data-aos="fade-left")
        p El estándar #[strong ISO/IEC 27001:2013] presenta directrices para implementar SGSI en una organización. Esta se encuentra estructurada bajo el ciclo PHVA (planear, hacer, verificar, actuar) que permite llevar a cabo el proceso de implementación; en dicho ciclo se encuentra la fase de planeación, la cual cuenta con un elemento fundamental como es el análisis de riesgos, que permite reconocer el nivel de seguridad previo de los activos de información en una organización.
      .col-4.align-self-center
        figure
          img(src="@/assets/template/tema-1-8.png", alt="Texto que describa la imagen").px-3
    .row.mt-5(data-aos="fade-right")
      .col-10.col-lg-8.offset-1.offset-lg-2
        .cajon.color-secundario.bg-naranja-claro.p-4
          p A partir de este análisis, se propone un plan de trabajo que involucra la determinación del plan de acción a desarrollar con el objetivo de reducir el riesgo en la organización.
      
      .col-10.col-lg-8.offset-1.offset-lg-2.mt-4
        .cajon.color-secundario.bg-naranja-mas-claro.p-4.mb-4
          p Esta norma cuenta con el Anexo A en el cual se definen los Objetivos de Control y Controles de Referencia que permite identificar los controles de seguridad a implementar en la organización y esta se establece mediante el documento denominado Declaración de Aplicabilidad.
    p.mt-5(data-aos="fade-down") A continuación, se presentan algunos conceptos importantes a tener en cuenta en el ejercicio de la determinación del plan de trabajo para la implementación de la ciberseguridad.
    TabsC.color-primario.mb-5(data-aos="fade-left")
      .py-3.py-md-4(titulo="Dominio de seguridad")
        .row
          p.mt-4 Se trata de la categoría o las categorías de seguridad que abordan los principales dominios a tener presentes en el establecimiento de la seguridad. La norma, actualmente, se encuentra estructurada por 14 dominios que representan los niveles de seguridad como son: operativos, lógicos, físicos y legales. Adicionalmente, estos niveles de seguridad, también se pueden identificar desde el ámbito estratégico y operativo.
          .col-8.offset-2
            .titulo-sexto.color-acento-contenido.mt-4.mb-0
              p.mb-0 #[b Figura 1]. Dominios de seguridad de la norma ISO/IEC 27001:2013
          .col-12.text-center
            .h3.mt-4.mb-0 Dominios de la Norma ISO/IEC 27001:2013
          figure.px-4
            img(src="@/assets/template/tema-1-9.png", alt="Texto que describa la imagen")
            figcaption.mt-4 Nota: Adaptada de ISO/IEC 27001:2013 – Anexo A
      .py-3.py-md-4(titulo="Objetivo de control")
        .row
          .col-4.col-lg-5.offset-4.offset-lg-0
            figure
              img(src="@/assets/template/tema-1-10.svg", alt="Texto que describa la imagen").w-75.margin-0-auto
          .col-12.col-lg-7.align-self-center
            p.mt-4 Cada uno de los dominios de seguridad que presenta la norma ISO/IEC 27001:2013, descritos anteriormente, se encuentra dividido en categorías. Estas categorías se denominan #[strong objetivos de control], los cuales establecen las intenciones y metas principales, de cada control de seguridad que será implementado y operado.
      
      .py-3.py-md-4(titulo="Control")
        .row
          .col-4.col-lg-5.offset-4.offset-lg-0
            figure
              img(src="@/assets/template/tema-1-11.svg", alt="Texto que describa la imagen").w-75.margin-0-auto
          .col-12.col-lg-7.align-self-center
            p.mt-4 En este ámbito, y en relación con lo explicado hasta este punto, el control o los controles, son aquellas #[strong acciones que se deben implementar] bajo un proceso o procedimiento que garantice el alcance de los objetivos o metas de seguridad que haya fijado la organización o empresa.
    Separador
    .titulo-segundo.mt-5
      #t_1_2.h2 1.2  Objetivos de control y su estructura
    p.mt-5(data-aos="fade-right") La estructura de los objetivos de control tiene tres segmentos: el dominio, que abarca al objetivo y los controles; en segundo lugar, está el objetivo, que obedece a la intención o meta de la organización según en relación con el dominio y, por último, el control o controles, que se establecen a partir del objetivo que los implica y del dominio que los contiene.
    .row.mt-5(data-aos="fade-down")
      .col-8.offset-2
        .titulo-sexto.color-acento-contenido.mt-4.mb-0
          p.mb-0 #[b Figura 2]. Ejemplo de la estructura de un control
    .row.justify-content-center.mt-5(data-aos="fade-left")
      .col-md-8.col-lg-4.px-4.mb-4.mb-lg-0
        .row.px-2.rounded-20.borde-morado.bg-morado-claro.text-center.h-100.zoom-in
          .col-12.px-1
            figure.pt-4
              img(src="@/assets/template/tema-1-12.svg", alt="Texto que describa la imagen").w-50.margin-0-auto
            .h3.mt-3 Dominio
            .h4 Ejemplo:
            ul.lista-ul.mt-3
              li 
                i.fas.fa-angle-right
                | A5 - Política de seguridad.
      .col-md-8.col-lg-4.px-4.mb-4.mb-lg-0
        .row.px-2.rounded-20.borde-naranja.bg-naranja-claro.text-center.h-100.zoom-in
          .col-12.px-1
            figure.pt-4
              img(src="@/assets/template/tema-1-13.svg", alt="Texto que describa la imagen").w-50.margin-0-auto
            .h3.mt-3 Objetivo de control
            .h4 Ejemplo:
            ul.lista-ul.mt-3
              li 
                i.fas.fa-angle-right
                | Política de seguridad de la información.
      .col-md-8.col-lg-4.px-4
        .row.px-2.rounded-20.borde-morado.bg-morado-claro.h-100.zoom-in
          .col-12.px-1
            figure.pt-4
              img(src="@/assets/template/tema-1-14.svg", alt="Texto que describa la imagen").w-50.margin-0-auto
            .h3.mt-3.text-center Controles
            .h4.text-center Ejemplo:
            ul.lista-ul.mt-3
              li 
                i.fas.fa-angle-right
                | Documento de política de seguridad de la información.
              li.mb-5 
                i.fas.fa-angle-right
                | Revisión de la política de seguridad de la información.
      figcaption.mt-4 Nota: Adaptada de ISO/IEC 27001:2013 – Anexo A

</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    overFlag: '',
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
  methods: {
    chBg(id) {
      this.overFlag = id
    },
    chBgTransparent() {
      this.overFlag = ''
    },
  },
}
</script>

<style lang="sass" scoped></style>
