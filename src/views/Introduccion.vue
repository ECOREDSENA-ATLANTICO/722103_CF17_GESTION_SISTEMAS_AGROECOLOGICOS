<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .row.justify-content-center.align-items-center.mb-3
      .row.justify-content-center.align-items-center
        .col-lg-10
          .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="fade-right")
            .bloque-texto-g__img(
              :style="{'background-image': `url(${require('@/assets/curso/portada/img-intro.png')})`}"
            )
            .bloque-texto-g__texto.p-4
              p.mb-0 La reproducción es la base para mantener una economía animal perfecta. En virtud del estro y los ciclos reproductores prolongados, la fertilidad alterada conduce a pérdidas de tiempo considerables durante los cuales la producción se reduce o cesa por completo. En el siguiente vídeo, podrá conocer más a este respecto: 


      .col-lg-12

        figure.mt-5(data-aos="fade-right")
          .video
            <iframe width="560" height="315" src="https://www.youtube.com/embed/UgmFdUgf5E8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


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
