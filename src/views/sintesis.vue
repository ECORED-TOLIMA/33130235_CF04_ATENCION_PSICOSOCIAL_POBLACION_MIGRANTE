<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p Este componente formativo aborda la estrategia de acompañamiento psicosocial para población migrante, presentando sus fundamentos conceptuales, principios éticos y actores clave que participan en la intervención. Se exploran las etapas y fases del acompañamiento, así como las herramientas metodológicas y la coordinación interinstitucional necesarias para su implementación efectiva en contextos de movilidad humana. Además, se analiza el marco normativo que respalda la estrategia, incluyendo políticas nacionales e internacionales, lineamientos del Ministerio de Salud y Protección Social, y protocolos técnicos vigentes, con el fin de brindar a los aprendices las bases teóricas, prácticas y legales para desarrollar intervenciones psicosociales integrales y sostenibles.
    .row.justify-content-center
      .col-12.mb-5.bgs.p-4.brad
        figure
          img(src="@/assets/curso/temas/sintesis.svg", alt="En la síntesis se describen los fundamentos de la acción intersectorial, los actores involucrados, los mecanismos de coordinación territorial y los lineamientos técnicos que orientan las intervenciones en salud pública para la atención de población migrante y comunidades de acogida.")
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/bullets/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis
</template>

<script>
export default {
  name: 'Sintesis',
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

<style lang="sass"></style>
