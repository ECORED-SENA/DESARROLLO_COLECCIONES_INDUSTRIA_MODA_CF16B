<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal(data-aos="fade-right")
      .titulo-principal__numero
        span 2
      h1 Costuras para ropa deportiva
  
    p(data-aos="fade-down") En la confección de ropa en general, las costuras, que es el entrelazamiento de dos o más telas, que han de ser unidas por una o varias secuencias de puntadas, se clasifican por su tipo (planas, solapadas, bondeadas, ribeteadas) y cuál es su posición en la prenda final (costura trasera central, tiro de entrepierna, costura lateral). Estas tienen un acabado que previene el deshilado de la tela sobrehilando el interior de las prendas; son utilizadas en el ensamble de los productos con propiedades físicas similares a las del material cosido. El tipo de puntada y el hilo utilizado variará de acuerdo a cada aplicación en la prenda; por lo tanto, es importante estar familiarizado con diferentes #[b tipos de puntada], sus aplicaciones y variaciones disponibles para elegir la opción que esté más acorde a sus necesidades de costura en las prendas de ropa deportiva. 
    .row.justify-content-center.align-items-center
      .col-lg-10
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mt-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/ilustraciones/img2.png')})`}"
          )    
          .bloque-texto-g__texto.p-4(data-aos="fade-right")
            p Las costuras son clasificadas de acuerdo al tipo/número de componentes utilizados. Existen ocho tipos de costuras definidas de acuerdo a las normas ISO 4916:1991; sin embargo, aquí solo se explicarán algunas de ellas. Las propiedades de una costura dependen de 3 atributos:  
            .row.justify-content-center.align-items-center
              .col-lg-12            
                .list.mt-3.ml-bloque
                    .list__item
                        .list__item__number
                            span 1.
                    .list__txt 
                        span La estructura de la costura.
                .list.ml-bloque.mt-2
                    .list__item
                        .list__item__number
                            span 2.
                    .list__txt 
                        span El tejido.
                .list.ml-bloque.mt-2
                    .list__item
                        .list__item__number
                            span 3.
                    .list__txt 
                        span El tipo de puntada y pespunte.          


        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mt-5.text-flex
          .bloque-texto-g__img.m-left(
            :style="{'background-image': `url(${require('@/assets/ilustraciones/img3.png')})`}"
          )    
          .bloque-texto-g__texto.p-4(data-aos="fade-left")
            p También existe una clasificación acorde a su función principal, la cual se divide en:

            ul.lista-ul--color
              li.mt-3 
                i.lista-ul__vineta
                | Costuras de construcción.
              li 
                i.lista-ul__vineta
                | Terminaciones y acabado.
              li 
                i.lista-ul__vineta
                | Detalles.

    p.mt-5.text-center(data-aos="fade-down") A continuación, se observan las instrucciones para cuatro tipos de costuras utilizados en la elaboración de ropa deportiva.

    TabsB.color-primario.mb-5.mt-5(data-aos="flip-up") 
      .py-4.py-md-5(titulo="Costura plana (básica abierta)" :icono="require('@/assets/ilustraciones/img4.svg')")
        .row.justify-content-center.align-items-center
          .col-lg-11
            p Se cosen dos piezas con los derechos de la tela enfrentados con una línea simple dejando un margen de 1 cm de costura. Es una costura de unión de telas donde se remata al inicio y al final. Esta se hace en máquina plana de una y dos agujas.
            .row.justify-content-center.align-items-center.mt-5
              .col-lg-8
                .BorTit #[b Figura 1] Costura plana             
                img.img-t.img-a.my-3(data-aos="zoom-in")(src='@/assets/ilustraciones/img8.svg', alt='')   
                figcaption #[b Nota]. Tomado de A. (2017).      
      .py-4.py-md-5(titulo="Costura interior (en el borde)" :icono="require('@/assets/ilustraciones/img5.svg')")
        .row.justify-content-center.align-items-center
          .col-lg-11
            p Es la línea de pespunte visto que se hace cerca del borde de la costura. Es decorativa y funcional, fortalece la costura y mantiene en su sitio entretelas o forros. Normalmente se hacen con puntadas más largas que las de la costura. También puede coserse en los dos bordes abiertos, o solo en uno cerrado y montado hacia un lado, dependiendo del diseño.
            .row.justify-content-center.align-items-center.mt-5
              .col-lg-12
                .BorTit #[b Figura 2] Costura interior
                img.img-t.img-a.my-3(data-aos="zoom-in")(src='@/assets/ilustraciones/img9.svg', alt='')   
                figcaption #[b Nota]. Tomado de A. (2017).               
      .py-4.py-md-5(titulo="Costura curva" :icono="require('@/assets/ilustraciones/img6.svg')")
        .row.justify-content-center.align-items-center
          .col-lg-11
            p Las costuras curvas tienen dos partes: una sección curva cóncava y un inserto convexo (más pequeño). Antes de coser, se debe ir creando aplomos regulares entre ambas piezas para adaptar las dos formas.

            p.mb-5 #[b Los pasos para realizar estas costuras son lo siguientes:]

            ol.lista-ol--cuadro
              li 
                .lista-ol--cuadro__vineta
                  span 1
                p Colocar la pieza cóncava en la máquina con el derecho arriba.
              li 
                .lista-ol--cuadro__vineta
                  span 2
                p Poner encima la pieza convexa (pequeña) con el derecho hacia abajo, casar las líneas de costura con ayuda de los alfileres y empezar a coser.
              li 
                .lista-ol--cuadro__vineta
                  span 3
                p Cuando las secciones curvadas empiecen a divergir, se debe hacer que la sección cóncava siga a la otra, embebiendo el tejido, pero manteniendo plana esta sección inferior. 
                  font(color='#BF3976') Reducir el largo de las puntadas los ayudará a controlar mejor la curva y conseguir un acabado más limpio.
              li 
                .lista-ol--cuadro__vineta
                  span 4
                p En las costuras curvas se debe ir reduciendo (recortando) progresivamente el margen de costura. 
                  font(color='#339CE9') Piquetear con la punta de las tijeras (haciendo pequeñas muescas) el margen de costura para evitar abultamientos y que la costura quede lo más plana posible.         

            .row.justify-content-center.align-items-center.mt-5
              .col-lg-12
                .BorTit #[b Figura 3] Costura curva           
                img.img-t.img-a.my-3(data-aos="zoom-in")(src='@/assets/ilustraciones/img10.svg', alt='')   
                figcaption #[b Nota]. Tomado de A. (2017).               
      .py-4.py-md-5(titulo="Costura ribeteada" :icono="require('@/assets/ilustraciones/img7.svg')")
        .row.justify-content-center.align-items-center
          .col-lg-11
            p Este tipo de costura se diferencia por su acabado. Los márgenes de costura sin remallar se encierran con una cinta, bies, o sesgo que puede ser del mismo tejido o de un material que contraste.
            .row.justify-content-center.align-items-center.mt-5
              .col-lg-8
                .BorTit #[b Figura 4] Costura ribeteada
                img.img-t.img-a.my-3(data-aos="zoom-in")(src='@/assets/ilustraciones/img11.svg', alt='')   
                figcaption #[b Nota]. Tomado de A. (2017).                                       
</template>

<script>
export default {
  name: 'Tema2',
  components: {},
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

<style lang="sass" scoped></style>
