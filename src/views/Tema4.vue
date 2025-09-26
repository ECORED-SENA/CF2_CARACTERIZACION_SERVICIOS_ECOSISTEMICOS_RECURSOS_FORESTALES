<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 4
      h1 Servicios ecosistémicos
    
    .bloque-texto-g.bloque-texto-g--inverso.color-acento-contenido.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema4/1.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Los #servicios ecosistémicos (SSEE) son los beneficios directos e indirectos que la humanidad obtiene de la biodiversidad, resultado de la interacción entre componentes, estructuras y funciones que integran los ecosistemas. De acuerdo con la Política Nacional de Gestión Integral de la Biodiversidad y sus Servicios Ecosistémicos (Ministerio de Ambiente y Desarrollo Sostenible, 2014), estos servicios se clasifican en varias categorías. 
    
    separador
    
    #t_4_1.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 4.1 Servicios de aprovisionamiento
    
    p.mb-5 Los #[strong servicios de aprovisionamiento] corresponden a los #[strong bienes materiales] que los ecosistemas proveen para el #[strong bienestar humano] y el #[strong desarrollo económico]. Entre estos se destacan:

    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        SlyderA(tipo="b").bg-color-4.tarjeta.p-4
          .row.align-items-center.p-4.p-md-5.justify-content-around
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema4/2.png", alt="Imagen de acompañamiento")
            .col-lg-5.order-1.mb-3.mb-lg-0
              h5 Alimentos
              p Colombia, con su diversidad de climas y ecosistemas, tiene un #[strong gran potencial agropecuario]. Según el DANE, el sector de agricultura, ganadería, silvicultura y pesca creció un #[strong 7,1 %] en el primer trimestre de 2025 respecto al mismo periodo de 2024 (Ministerio de Agricultura, 2025).
          .row.align-items-center.p-4.p-md-5.justify-content-around
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema4/3.png", alt="Imagen de acompañamiento")
            .col-lg-5.order-1.mb-3.mb-lg-0
              h5 Productos forestales maderables
              p Más de #[strong 673.000 m³ de madera] proveniente de bosques naturales se comercializan legalmente cada año (Fedemaderas, 2025). Existen #[strong 28 núcleos de desarrollo forestal] y de biodiversidad distribuidos en departamentos como #[strong Caquetá, Guaviare, Meta, Putumayo, Chocó, Nariño, Norte de Santander, Antioquia, Arauca y Córdoba].
          .row.align-items-center.p-4.p-md-5.justify-content-around
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema4/4.png", alt="Imagen de acompañamiento")
            .col-lg-5.order-1.mb-3.mb-lg-0
              h5 Productos forestales no maderables
              p Con un #[strong alto potencial de uso sostenible], incluyen semillas, frutos, hojas, resinas, entre otros. Aproximadamente #[strong 700 especies] provienen de selvas subandinas y andinas, y cerca de #[strong 500 especies] de zonas secas, páramos y humedales. Se emplean en sectores como salud, farmacia, belleza, artesanías y alimentos.
          .row.align-items-center.p-4.p-md-5.justify-content-around
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema4/5.png", alt="Imagen de acompañamiento")
            .col-lg-5.order-1.mb-3.mb-lg-0
              h5 Agua
              p Colombia cuenta con #[strong una de las mayores ofertas hídricas del mundo], gracias a su amplia red fluvial y reservas subterráneas. Sin embargo, #[strong el acceso desigual] persiste, debido a factores como la #[strong vulnerabilidad social], #[strong cambio climático], #[strong expansión urbana] y #[strong ampliación de fronteras agrícolas], que amenazan la disponibilidad del recurso.
    
    p Estos recursos no solo son fundamentales para la #[strong seguridad alimentaria y energética], sino también para el #[strong desarrollo económico sostenible] y la #[strong subsistencia de comunidades locales], especialmente aquellas que dependen directamente del uso de los recursos naturales.

    separador
    
    #t_4_2.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 4.2 Servicios de regulación 
    
    p.mb-5 Los servicios de regulación son aquellos beneficios que brindan los ecosistemas sin necesidad de transformación directa, ya que actúan de manera natural sobre el equilibrio de los sistemas biofísicos. Según el Ministerio de Ambiente y Desarrollo Sostenible (2014), incluyen la regulación de ciclos biogeoquímicos (como el hidrológico y el del carbono), la calidad del aire, la regulación del clima y la prevención de enfermedades.

    TabsC.color-acento-contenido
      .py-3.py-md-4(titulo="<b>Regulación hídrica</b>")
        .row.p-4.justify-content-center.align-items-center
          .col-lg-6.mb-4.mb-lg-0.order-2
            h4 Regulación hídrica
            p.mb-0 Colombia cuenta con una amplia oferta hídrica gracias a su red de fuentes lénticas (lagos, lagunas) y lóticas (ríos, quebradas). Según el #[strong IDEAM (2022)], el país presenta un volumen de escorrentía de #[strong 1963 km³/año], con un rendimiento promedio de #[strong 56,2 l/s/km²], superando ampliamente el promedio mundial #[strong (10 l/s/km²)]. Sin embargo, la tala de bosques, la expansión agrícola y el comercio ilegal de madera han deteriorado muchos ecosistemas hídricos. Se requieren acciones urgentes para una #[strong gobernanza del agua] más efectiva e inclusiva.
          .col-lg-5.order-1.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/tema4/6.png', alt='Texto que describa la imagen')
      .py-3.py-lg-4(titulo="<b>Regulación del clima</b>")
        .row.p-4.justify-content-center.align-items-center
          .col-lg-6.mb-4.mb-lg-0.order-2
            h4 Regulación del clima
            p.mb-0 Los #[strong ecosistemas boscosos], especialmente en la #[strong Amazonía y el Pacífico], contribuyen a la #[strong absorción de CO₂], ayudando en la #[strong mitigación y adaptación al cambio climático]. Además, estos bosques regulan el régimen de lluvias y la temperatura a nivel local y regional.
          .col-lg-5.order-1.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/tema4/7.png', alt='Texto que describa la imagen')
      .py-3.py-lg-4(titulo="<b>Calidad del aire</b>")
        .row.p-4.justify-content-center.align-items-center
          .col-lg-6.mb-4.mb-lg-0.order-2
            h4 Calidad del aire
            p.mb-0 Los bosques filtran contaminantes, generan oxígeno y retienen partículas suspendidas. La #[strong pérdida de cobertura forestal] por incendios u otras causas reduce esta capacidad reguladora, deteriorando la #[strong calidad del aire] y aumentando los riesgos para la salud humana y ambiental.
          .col-lg-5.order-1.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/tema4/8.png', alt='Texto que describa la imagen')
    
    separador
    
    #t_4_3.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 4.3 Servicios de soporte
    
    p.mb-5 Los #[strong servicios de soporte] son los #[strong procesos ecológicos fundamentales] que permiten el funcionamiento de los ecosistemas y la existencia de los demás servicios ecosistémicos (Ministerio de Ambiente y Desarrollo Sostenible, 2014, p. 34). Sin estos procesos básicos, no sería posible el aprovisionamiento, la regulación ni los servicios culturales.

     .bg-full-width.bg-fondo-slider
      .p-4.p-md-5
        SlyderA(tipo="b").bg-color-4.tarjeta.p-4
          .row.align-items-center.p-4.p-md-5.justify-content-around
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema4/9.png", alt="Imagen de acompañamiento")
            .col-lg-5.order-1.mb-3.mb-lg-0
              h5 Formación y conservación del suelo
              p La vegetación y las buenas prácticas agrícolas permiten #[strong mantener la fertilidad del suelo], previniendo procesos erosivos que pueden deteriorar otros servicios ecosistémicos como la producción de alimentos y la regulación hídrica. El uso adecuado del suelo, evitando la sobreexplotación y protegiendo las coberturas vegetales, favorece la estabilidad de los ecosistemas.
          .row.align-items-center.p-4.p-md-5.justify-content-around
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema4/10.png", alt="Imagen de acompañamiento")
            .col-lg-5.order-1.mb-3.mb-lg-0
              h5 Hábitat para la biodiversidad
              p Los #[strong ecosistemas boscosos] proporcionan #[strong espacios esenciales para el desarrollo de diversas especies], funcionando como refugio, fuente de alimento y lugar de reproducción. Además, permiten el flujo genético entre poblaciones, sostienen las cadenas alimenticias y garantizan la #[strong diversidad genética] necesaria para la resiliencia ecológica. Su conservación es fundamental para mantener el equilibrio de los ecosistemas y el bienestar de las comunidades humanas que dependen de ellos.
    
    separador
    
    #t_4_4.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 4.4 Servicios culturales

    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema4/11.png')})`}"
      )(data-aos="zoom-in")
      .bloque-texto-g__texto.p-4
        p.mb-0 Los servicios culturales son aquellos beneficios #[strong no materiales] que se obtienen de los ecosistemas. Estos incluyen el enriquecimiento espiritual, la belleza paisajística, los aspectos artísticos y religiosos, la recreación, así como las experiencias estéticas (Ministerio de Ambiente y Desarrollo Sostenible, 2014, p. 35).
    
    p.mb-5 En el caso de Colombia, país #[strong multicultural y pluriétnico], estos servicios tienen una relación estrecha con el #[strong desarrollo cultural étnico]. Están profundamente vinculados con los #[strong conocimientos ancestrales] y diversos aspectos #[strong socioculturales] relacionados con la #[strong conservación de la biodiversidad]. Además, se conectan con prácticas tradicionales como la #[strong agricultura] y el uso de #[strong productos silvestres o recursos forestales no maderables], que reflejan formas sostenibles de interacción con el entorno natural.

    .row.mb-5
      .col-lg-6.mb-3.mb-gl-0
        figure(data-aos="flip-up")
          img(src='@/assets/curso/tema4/12.png', alt='Texto descriptivo 1')
      .col-lg-6.mb-3.mb-gl-0
        figure(data-aos="flip-down")
          img(src='@/assets/curso/tema4/13.png', alt='Texto descriptivo 1')

    

</template>

<script>
export default {
  name: 'Tema4',
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
