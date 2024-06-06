<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Inseminación artificial en especies animales

    p.mb-5 La inseminación artificial (IA) es el proceso de recolectar espermatozoides de un animal macho y depositarlos manualmente en el tracto reproductivo de una hembra. La inseminación artificial se usa comúnmente en lugar del apareamiento natural, debido a los beneficios que se pueden obtener. Estos beneficios incluyen mayor seguridad en los animales y el productor, más eficiencia de producción y mejor genética.   

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-10
        .img-fnd-flot3.mb-3
          img.b-img3(src='@/assets/curso/temas/tema4/img-1.png' alt='Background Image')
          .fl-box3
            p.mb-0 Es un instrumento vital para el mejoramiento genético, en el cual, mediante una pistola de inseminar, se introduce semen dentro del aparato genital de la hembra en celo o manejada bajo protocolos hormonales; se utiliza para disminuir los tiempos y ser más productivos.         

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8 
        p En este proceso, el semen se insemina en la hembra colocando una porción de este en forma recolectada o diluida en el cuello uterino o el útero, mediante métodos mecánicos y en las condiciones más higiénicas. Sus experimentos demostraron que el poder fertilizante reside en los espermatozoides y no en la porción líquida del semen.
        p La inseminación artificial no es simplemente un método novedoso para lograr la fecundación en las hembras. Es una poderosa herramienta empleada principalmente para la mejora del ganado. En la inseminación artificial, el germoplasma de los toros de calidad superior se puede utilizar de manera efectiva en diferentes lugares. Mediante la adopción de la inseminación artificial, habría una reducción considerable de las enfermedades genitales y no genitales en el ganado de la granja.

      .col-lg-4
        figure
          img(src='@/assets/curso/temas/tema4/img-2.svg', alt='Texto que describa la imagen')
    
    
    Separador
    #4_1.titulo-segundo.color-acento-contenido
      h2 4.1	Elementos necesarios para la Inseminación Artificial (IA)
    p 
    p 



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

<style lang="sass"></style>
