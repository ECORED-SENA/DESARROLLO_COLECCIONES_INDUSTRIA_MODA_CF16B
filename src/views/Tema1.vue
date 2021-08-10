<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal(data-aos="fade-right")
      .titulo-principal__numero
        span 1
      h1 Introducción al mundo de la ropa deportiva
    
    figure.mb-5(data-aos="zoom-in")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    p(data-aos="fade-down") Para la elaboración de prendas de vestir deportivas, las máquinas planas de confección deben estar dotadas con la capacidad de adaptación de mecanismos y funciones especializadas para el tipo de tejido, ya que esta línea de producción se caracteriza por el tejido de punto licrado y de gran elongación, requiriendo de maquinaria apta para su desarrollo entre las que encontramos plana, fileteadora, resortadora, flaximer y pegadoras de elásticos, así como guía y aditamentos que ayudan a la calidad y buen ajuste de estas.

    p(data-aos="fade-down") La ropa deportiva ha cambiado bastante a través de la historia. Aunque la vestimenta haya ido transformándose a medida que la gente desarrollaba nuevas actividades, sólo hasta hace poco tiempo, las telas y los estilos han cambiado para ofrecer confort a las personas que hacen ejercicios y deportes. 

    p(data-aos="fade-down") En la antigüedad, la gente se ejercitaba con sus ropas de calle. Los atletas profesionales, como los que intervenían en las olimpíadas, competían desnudos, presumiblemente porque la ropa limitaba la ejecución de los movimientos que exigía cada disciplina deportiva. Los militares, por su parte, entrenaban en sus uniformes para que la situación se asemejara lo más posible a las posiciones de combate. Era muy raro que las mujeres hicieran deportes de competición; y si lo hacían, usaban versiones más pequeñas de la ropa de los hombres, sin tener en cuenta la horma adecuada a la silueta femenina.


    .row.justify-content-center.align-items-center.mt-5       
      .col-lg-12.cajon.color-primario.p-4
        .row.justify-content-center.align-items-center       
          .col-lg-8(data-aos="fade-right")
              p.mb-0 No fue hasta finales del siglo XIX y principios del XX que surgió en la sociedad un segmento poblacional que tomaría parte en los deportes por el gusto que sentía por ellos. La primera de las olimpíadas modernas de 1896 incluyó a muchos atletas de clase alta que usaban ropas rudimentarias (similares a los overoles) o un pantalón corto y una camiseta para los deportes de cancha; para el tenis se requería una vestimenta más formal, con los "blancos de tenis" de rigor, las mujeres, por su parte, usaban vestidos de tenis mientras que los hombres usaban pantalones y camisas, y hasta un #[i jersey], como se acostumbraba. Las mujeres debían ser modestas cuando usaban un traje de baño, se debían cubrir totalmente cuando estaban en la playa; los trajes que usaban no habían sido diseñados para usar en natación competitiva. Usaban una vestimenta que las confinaba para hacer cualquier actividad que fuera más extenuante que el #[i badmington] y las caminatas.               
          .col-lg-4
            img.img-t.img-a(data-aos="zoom-in")(src='@/assets/ilustraciones/img1.svg', alt='')               

    .row.justify-content-center.align-items-stretch.mt-5       
      .col-lg-6(data-aos="fade-left")
        .bloque-texto-d.color-acento-contenido.p-4
          .bloque-texto-d__texto.mb-2
            i.fas.fa-quote-left
            h3.text-regular El cambio de costumbres resultó en un cambio de estilos. Cuando antes era impensable que las mujeres usaran un <em>maillot</em>. En las olimpíadas del 2008, los equipos de voleibol playa compitieron, en su mayoría, con bikinis. De la misma manera, cuando durante casi todo el siglo XX ni siquiera se amagaba a aparecer en la calle con buzos o pantalones cortos, hoy son una vista común. Hoy, la moda de la ropa deportiva sigue cambiando. Esta ropa se ha convertido en una forma casual de vestir para mucha gente; hasta para los adultos mayores a los que les gusta la comodidad de los trajes de abrigo y de los buzos. Continúa la evolución de nuevas telas y estilos para la ropa deportiva.
            i.fas.fa-quote-right
          .bloque-texto-d__autor 
            .h5.mb-0 Brestovansky, 2017.

      .col-lg-6(data-aos="fade-right")
        .bloque-texto-d.color-acento-contenido.p-4
          .bloque-texto-d__texto.mb-2
            i.fas.fa-quote-left
            h3.text-regular Para definir mejor el textil inteligente, que se ha venido desarrollando en los últimos años, se puede decir que son aquellos que cambian su origen y alteran ciertos de sus atributos con ayuda de instrumentos electrónicos. Para poder llegar a los resultados que se quieren se tiene que trabajar en conjunto con la biotecnología, la nanotecnología o la microelectrónica.
            i.fas.fa-quote-right
          .bloque-texto-d__autor 
            .h5.mb-0 Pari, C. C. R., 2017.



</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped>
.introduccion
</style>
