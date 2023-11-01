<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 4
      h1 Técnicas de planificación
    .row.mt-5
      .col-7(data-aos="fade-right")
        .row
          .col-4
            figure
              img(src="@/assets/template/tema-4-1.svg", alt="Texto que describa la imagen").floating
          .col-8
            p El proceso de planificación para la implementación de la estrategia de seguridad debe abarcar una revisión y verificación del informe de análisis de riesgos que permita determinar, en primer lugar, los activos de información que se desean proteger en la organización, así como las amenazas a las cuales están expuestos; este ejercicio conlleva al establecimiento de los objetivos de seguridad con los cuales se busca garantizar una mejora considerable de los niveles de seguridad de los activos en la organización.
        p.mt-5 Estos son algunos elementos claves, que han de tenerse en cuenta en el proceso de la planificación:
      .col-5.align-self-center(data-aos="fade-left")
        figure
          img(src="@/assets/template/tema-4-2.png", alt="Texto que describa la imagen")
    .row.mt-5
      .col-10.offset-1
        LineaTiempoD.color-acento-botones(data-aos="fade-right")
          .row(numero="1" titulo="Activo de información").mb-
            .col-2.mt-3
              figure
                img(src="@/assets/template/tema-4-3.svg", alt="Texto que describa la imagen").w-75.margin-0-auto
            .col-10.mt-3
              p Un activo de información de acuerdo a la norma ISO/IEC 27001:2012 es “algo que una organización valora y por lo tanto debe proteger”.

          .row(numero="2" titulo="Objetivo de seguridad")
            .col-2.mt-3
              figure
                img(src="@/assets/template/tema-4-4.svg", alt="Texto que describa la imagen").w-75.margin-0-auto
            .col-10.mt-3
              p Son objetivos que se plantean a partir de los resultados de la evaluación de riesgos y reflejan la medida en la que se alcanzan los niveles de protección de los activos de información, para determinar la eficacia de los controles implementados.
          .row(numero="3" titulo="Registro")
            .col-2.mt-3
              figure
                img(src="@/assets/template/tema-4-5.svg", alt="Texto que describa la imagen").w-75.margin-0-auto
            .col-10.mt-3
              p Son evidencias o anotaciones relacionadas con el desarrollo y ejecución de un control, de acuerdo a lo propuesto.  
          .row(numero="4" titulo="Recurso")
            .col-2.mt-3
              figure
                img(src="@/assets/template/tema-4-6.svg", alt="Texto que describa la imagen").w-75.margin-0-auto
            .col-10.mt-3
              p Corresponde a los elementos o insumos necesarios para la implementación de un control y se convierte en un aspecto fundamental en el ejercicio de establecer las acciones a implementar.
          .row(numero="5" titulo="Métrica")
            .col-2.mt-3
              figure
                img(src="@/assets/template/tema-4-7.svg", alt="Texto que describa la imagen").w-75.margin-0-auto
            .col-10.mt-3
              p Las métricas son instrumentos que permiten verificar el nivel de cumplimiento de un control de seguridad de acuerdo a lo esperado y propuesto en la estrategia de seguridad.
    .titulo-segundo.mt-5
      #t_4_1.h2 4.1 La planificación y los objetivos
    .row.mt-5
      .col-12.col-lg-7.align-self-center
        .row(data-aos="fade-right")
          .col-3
            figure
              img(src="@/assets/template/tema-4-8.svg", alt="Texto que describa la imagen").floating
          .col-9
            p La planificación de la estrategia de seguridad se debe realizar mediante la construcción de los objetivos de seguridad, estos se deben proponer a partir del análisis de riesgos, realizado a los activos de información y establecer las acciones que se deben adelantar para tratar los riesgos de seguridad. Con los objetivos se busca garantizar los pilares de la información.
        p.mt-5(data-aos="fade-right") Para el establecimiento de los objetivos de seguridad es importante tener presente aspectos como:
        ul.lista-ul--separador.mt-4(data-aos="fade-right")
          li 
            i.fas.fa-angle-right
            | Los recursos que se necesitan para realizar la implementación.
          li 
            i.fas.fa-angle-right
            | La persona, área o dependencia responsable del cumplimiento del objetivo.
          li 
            i.fas.fa-angle-right
            | El método de evaluación, con el fin de identificar si el objetivo se está cumpliendo.
          li 
            i.fas.fa-angle-right
            p Además, debe tener presente que todo el ejercicio de la construcción y ejecución del objetivo de control debe estar documentado, así como:    
        ul.lista-ul.pl-5(data-aos="fade-right")
          li 
            i.lista-ul__vineta
            | Definir cada objetivo y su finalidad.
          li 
            i.lista-ul__vineta
            | Las evaluaciones y seguimiento a la ejecución y verificación del control verificando que este se cumpla.
      .col-4.col-lg-5(data-aos="fade-left")
        figure
          img(src="@/assets/template/tema-4-9.png", alt="Texto que describa la imagen")
    .titulo-segundo.mt-5
      #t_4_2.h2 4.2  Características de validación
    .row.mt-5(data-aos="fade-right")
      .col-2
        figure
          img(src="@/assets/template/tema-4-10.svg", alt="Texto que describa la imagen").floating
      .col-10
        p La planificación de la estrategia de seguridad se debe realizar mediante la construcción de los objetivos de seguridad, estos se deben proponer a partir del análisis de riesgos, realizado a los activos de información y establecer las acciones que se deben adelantar para tratar los riesgos de seguridad. Con los objetivos se busca garantizar los pilares de la información.
    figure.mt-5(data-aos="fade-down")
      img(src="@/assets/template/tema-4-11.png", alt="Texto que describa la imagen")
    p.mt-5(data-aos="fade-right") En consecuencia, con la norma ISO/IEC 27001:2013 en su numeral 6.2, los objetivos de seguridad deben presentar las siguientes características:
    ul.lista-ul.mt-5(data-aos="fade-right")
      li 
        i.fas.fa-angle-right
        | Estar alineadas a la política de seguridad de la información.
      li 
        i.fas.fa-angle-right
        | Se deben poder medir.
      li 
        i.fas.fa-angle-right
        | Tener presente el contexto de la estrategia de seguridad, así como el resultado del ejercicio de valoración de riesgos.
      li 
        i.fas.fa-angle-right
        | Estos deben ser informados a todos los interesados.
      li 
        i.fas.fa-angle-right
        | Deben ser evaluados y actualizados de acuerdo a las necesidades.
    .row.mt-5
      .col-10.offset-1
        LineaTiempoD.color-acento-botones(data-aos="fade-right")
          .row(numero="1" titulo="Importante")
            .col-2.mt-3
              figure
                img(src="@/assets/template/tema-4-12.svg", alt="Texto que describa la imagen").w-75.margin-0-auto
            .col-10.mt-3
              p Se debe conservar la información documentada sobre los objetivos de la seguridad de la información.
          .row(numero="2" titulo="Tenga presente ")
            .col-2.mt-3
              figure
                img(src="@/assets/template/tema-4-13.svg", alt="Texto que describa la imagen").w-75.margin-0-auto
            .col-10.mt-3
              p En el momento de realizar la planificación para garantizar el alcance de los objetivos propuestos, en relaciona con la seguridad de la información, se debe tener presente:
              ul.lista-ul.mt-5
                li 
                  i.fas.fa-angle-right
                  | Acciones a desarrollar
                li 
                  i.fas.fa-angle-right
                  | Recursos necesarios
                li 
                  i.fas.fa-angle-right
                  | Persona, área o dependencia responsable
                li 
                  i.fas.fa-angle-right
                  | Tiempo necesario para culminar
                li 
                  i.fas.fa-angle-right
                  | Método de evaluación
          .row(numero="3" titulo="¡Atención!")
            .col-2.mt-3
              figure
                img(src="@/assets/template/tema-4-14.svg", alt="Texto que describa la imagen").w-75.margin-0-auto
            .col-10.mt-3
              p La información documentada deberá ser conservada para su revisión en procesos de auditoria, tanto internas como externas, para cumplimiento y verificación.

</template>

<script>
export default {
  name: 'Tema4',
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
