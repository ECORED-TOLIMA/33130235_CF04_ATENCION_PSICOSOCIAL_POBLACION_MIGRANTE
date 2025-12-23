<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    p(data-aos="fade-down") Este componente presenta los elementos esenciales para comprender cómo se organiza la acción intersectorial en salud frente a las dinámicas de movilidad humana. La información integra los determinantes sociales, el papel del sector salud, la articulación entre actores territoriales y las capacidades institucionales necesarias para garantizar respuestas oportunas, integrales y culturalmente pertinentes. También se abordan las estrategias de coordinación, las intervenciones colectivas e individuales, las situaciones de interés en salud pública y los protocolos vigentes que orientan la gestión territorial.
    p.mb-5(data-aos="fade-down") Para comprender la importancia del contenido y los temas abordados, se recomienda acceder al siguiente video.
    .row.justify-content-center.align-items-center           
      .col-lg-12
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/fzabNC6CEBA?si=J4lHV4qfA0mceUZK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
