<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal(data-aos="fade-right")
      .titulo-principal__numero
        span 3
      h1 Ejercicios bolsillos de sudadera
    .row.justify-content-center.align-items-stretch 
      .col-lg-6.row-padding-right(data-aos="fade-down")
        p Los bolsillos utilizados en la confección del pantalón de sudadera van desde los de parche hasta los de cierre.
        p Los bolsillos de parche son aquellos que se pegan sobre la pieza. Este tipo de bolsillo va doblado por su contorno (excepto en la boca) y pegado a la prenda generalmente con puntada sencilla (plana) o con 2 agujas, por lo que usualmente se les deja 1 cm de márgenes de costura. En la boca de bolsillo habrá que revisar cómo se propone en el diseño, las hay fileteadas y dobladas (solo la margen de doblado), hay dobladilladas (margen de doblado y de dobladillo), sesgadas o ribeteadas (no llevan margen), por lo tanto, según el diseño se deben asignar las márgenes de costura.
        .row.justify-content-center.align-items-center.mt-5
          .col-lg-8
            .BorTit #[b Figura 5] Bolsillo de parche delantero           
            img.img-t.img-a.my-3(data-aos="zoom-in")(src='@/assets/ilustraciones/img12.png', alt='')   
      
      .col-lg-1.d-none.d-lg-block.hr-dotted.mx-0
      .col-lg-5(data-aos="fade-down")
        p Los bolsillos de ribete, como su nombre lo indica, son aquellos que se caracterizan por ser internos y se accede a ellos por medio de una abertura en la prenda que, generalmente, está ribeteada, por ello su nombre. Los hay sin pestaña (solo la caja o abertura), con una pestaña o dos pestañas, algunos se confeccionan con tapa la cual puede ser externa, o estar pegada al interior del bolsillo y salir por medio de la abertura o ribete, también los hay con cremallera.
        .row.justify-content-center.align-items-stretch.mt-5
          .col-lg-5
            .BorTit #[b Figura 6] Bolsillo de ribete posterior
            img.img-t.img-a.my-3(data-aos="zoom-in")(src='@/assets/ilustraciones/img13.png', alt='')

          .col-lg-7
            .BorTit #[b Figura 7] Bolsillo ribete
            img.img-t.img-a.my-3(data-aos="zoom-in")(src='@/assets/ilustraciones/img14.png', alt='') 
            .row.justify-content-center.align-items-center       
              .col-lg-12.cajon.color-primario.px-1
                .row.justify-content-center.align-items-center       
                  .col-lg-8
                      p.my-3 Para realizar este tipo de operación se hace necesario cerrar las costuras laterales respetando las aberturas para los bolsillos. Separar los márgenes de costura con la plancha. Observemos los siguientes videos para ampliar la información.  

    .row.justify-content-center.align-items-stretch.mt-2
      .col-lg-4.border-row.text-center.my-3(data-aos="fade-left")
        .card-row.p-4.boton-row
          h4.text-white Video 1 
          p.text-white How to sew a pocket.2 sewing course 

        a.boton--sm.color-acento-contenido.text-white(href="https://www.youtube.com/watch?app=desktop&v=on2kcoGPR3Q&feature=youtu.be" target="_blank" type="application/pdf")
          span.my-1.mx-1 Ver video
          i.fas.fa-video
      .col-lg-4.border-row.text-center.my-3(data-aos="zoom-in")
        .card-row.p-4.boton-row
          h4.text-white Video 2
          p.text-white Bolsillos laterales con cierre 

        a.boton--sm.color-acento-contenido.text-white(href="https://www.youtube.com/watch?app=desktop&v=SHncFKVXt-4&feature=youtu.be" target="_blank" type="application/pdf" @mouseover="mostrarIndicador = false")
          span.my-1.mx-1 Ver video
          i.fas.fa-video
          .indicador--click(v-if="mostrarIndicador")          
      .col-lg-4.border-row.text-center.my-3(data-aos="fade-right")
        .card-row.p-4.boton-row
          h4.text-white Video 3 
          p.text-white Bolsillos invisibles de costado 

        a.boton--sm.color-acento-contenido.text-white(href="https://www.youtube.com/watch?app=desktop&v=2C9X0SKJ-nA&feature=youtu.be" target="_blank" type="application/pdf")
          span.my-1.mx-1 Ver video
          i.fas.fa-video   

    p.mt-4(data-aos="fade-down") Los bolsillos delanteros de los pantalones sudadera se presentan en diferentes formas y tamaños, con bocas curvas, rectas, diagonales, ribeteadas, con cremallera, en fin, como la temporada, la ocasión de uso o el diseño lo requieran.   

    .row.justify-content-center.align-items-stretch.mt-4
      .col-lg-4.border-row.my-3  
        .BorTit #[b Figura 8] Bolsillo de ribete lateral delantero
        img.img-t.img-a.my-3(data-aos="fade-left")(src='@/assets/ilustraciones/img15.png', alt='')    
      .col-lg-4.border-row.my-3  
        .BorTit #[b Figura 9] Bolsillo de cierre delantero
        img.img-t.img-a.my-3(data-aos="zoom-in")(src='@/assets/ilustraciones/img16.png', alt='')      
      .col-lg-4.border-row.my-3  
        .BorTit #[b Figura 10] Bolsillo tipo americano con falso      
        img.img-t.img-a.my-3(data-aos="fade-right")(src='@/assets/ilustraciones/img17.png', alt='')

    p.mt-4.text-center(data-aos="fade-down") #[b A continuación, se muestra otra forma de realizar la confección del bolsillo delantero del pantalón sudadera.]

    .tarjeta.tarjeta--gris.p-4.mt-5(data-aos="flip-up")
      LineaTiempoC.color-primario
        .row.justify-content-center.align-items-stretch(titulo="Paso 1")
          .col-lg-5.mb-4.mb-md-0
            p Se unen el delantero y el posterior de la sudadera encarando derechos y se deja la abertura del bolsillo libre sin costura para luego unirlo a él.
        
          .col-lg-5
            .BorTit #[b Figura 11] Unión de piezas
            figure.mt-3
              img(src='@/assets/ilustraciones/img18.png', alt='Texto que describa la imagen')
              figcaption.mt-2 Nota. Tomado de García (s.f.)
        
        .row.justify-content-center.align-items-stretch(titulo="Paso 2")
          .col-lg-5.mb-4.mb-md-0
            p Pegar las hojas de bolsillo desde dentro a los márgenes de costura de las aberturas de bolsillo, encarando los derechos y aplicarlos con un pespunte, exactamente a lo largo de las líneas de costura marcada.
        
          .col-lg-5
            .BorTit #[b Figura 12] Hojas de bolsillo
            figure.mt-3
              img(src='@/assets/ilustraciones/img19.png', alt='Texto que describa la imagen')
              figcaption.mt-2 Nota. Tomado de García (s.f.)
        
        .row.justify-content-center.align-items-stretch(titulo="Paso 3")
          .col-lg-8
            p Por encima y por debajo de las aberturas de bolsillo aplicar las hojas de bolsillo pespunteando justo al lado de la costura.

            .BorTit #[b Figura 13] Unión de hojas de bolsillo
            figure.mt-3
              img(src='@/assets/ilustraciones/img20.png', alt='Texto que describa la imagen')
              figcaption.mt-2 Nota. Tomado de García (s.f.)
        
        .row.justify-content-center.align-items-stretch(titulo="Paso 4")
          .col-lg-5.mb-4.mb-md-0
            p Planchar las hojas de bolsillo hacia adelante y unirlos, superpuestos, con un pespunte.
        
          .col-lg-5
            .BorTit #[b Figura 14] Planchado de hojas de bolsillo
            figure.mt-3
              img(src='@/assets/ilustraciones/img21.png', alt='Texto que describa la imagen')
              figcaption.mt-2 Nota. Tomado de García (s.f.)
        
        .row.justify-content-center.align-items-stretch(titulo="Paso 5")
          .col-lg-10
            p Pespuntear las bolsas de bolsillo de forro a los cantos de las aberturas de las piezas de pantalón delanteras.

            .BorTit #[b Figura 15] Pespunte
            figure.mt-3
              img(src='@/assets/ilustraciones/img22.png', alt='Texto que describa la imagen')
              figcaption.mt-2 Nota. Tomado de García (s.f.)
        
        .row.justify-content-center.align-items-stretch(titulo="Paso 6")
          .col-lg-10
            p Pespuntear la boca del bolsillo colocando el forro de la parte trasera hacia el delantero.

            .BorTit #[b Figura 16] Pespunte de bolsillo 
            figure.mt-3
              img(src='@/assets/ilustraciones/img23.png', alt='Texto que describa la imagen')
              figcaption.mt-2 Nota. Tomado de García (s.f.)
        
        .row.justify-content-center.align-items-stretch(titulo="Paso 7")
          .col-lg-10
            p En los extremos de las aberturas de bolsillo pespuntear unos puntos tupidos de zigzag en sentido transversal.

            .BorTit #[b Figura 17] Remates bolsillo
            figure.mt-3
              img(src='@/assets/ilustraciones/img24.png', alt='Texto que describa la imagen')
              figcaption.mt-2 Nota. Tomado de García (s.f.)                                                                                    

</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    mostrarIndicador: true,
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
