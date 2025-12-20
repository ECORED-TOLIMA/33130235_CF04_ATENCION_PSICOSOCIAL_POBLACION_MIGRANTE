<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="fade-right")
      .titulo-principal__numero
        span 1
      h1 Fundamentos de la acción intersectorial en salud y migración
    p.mb-5(data-aos="fade-down") La atención integral de la población migrante requiere la articulación efectiva entre sectores institucionales que aporten capacidades complementarias, con el fin de garantizar respuestas oportunas, coordinadas y centradas en derechos.
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="flip-down")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/img01.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Según el Ministerio de Salud y Protección Social (2021), la movilidad humana implica desafíos en salud, protección social, inclusión socioeconómica, educación, gestión territorial y trabajo comunitario. Por ello, la coordinación intersectorial se convierte en un componente esencial para evitar la duplicidad de acciones, optimizar el uso de los recursos y garantizar el acceso oportuno a los servicios, sin barreras administrativas.
    p.mb-5(data-aos="fade-down") La articulación intersectorial permite integrar enfoques de salud pública, derechos humanos, gestión del riesgo, enfoque diferencial y participación comunitaria. Este proceso contribuye a que las entidades territoriales comprendan las dinámicas locales, identifiquen las necesidades específicas de la población migrante, retornada y de las comunidades de acogida, y adopten acciones concertadas basadas en evidencia.
    .row.justify-content-center.mb-0
      .col-lg-6.order-lg-1.order-2
        .cajon.cajon.C01.color-primario.p-4.mb-3
          p.mb-0(data-aos="fade-down") La Organización Internacional para las Migraciones (2022) señala que la gobernanza migratoria requiere flujos de información oportunos, corresponsabilidad institucional y mecanismos técnicos de coordinación que reduzcan las vulnerabilidades y fortalezcan la capacidad de respuesta estatal, facilitando la planificación conjunta y el seguimiento de las intervenciones.
        p.mb-4(data-aos="fade-down") A nivel operativo, la coordinación intersectorial se materializa a través de mesas técnicas, comités territoriales, rutas integradas de atención y dispositivos comunitarios. Estas estructuras hacen posible la articulación entre la oferta institucional, los organismos de cooperación internacional, la sociedad civil y los liderazgos comunitarios, ampliando el alcance de las intervenciones y fortaleciendo la sostenibilidad de las acciones en el territorio.
      .col-lg-4.order-lg-2.order-1.mb-3.col-md-5.col-7
        figure(data-aos="fade-up") 
          img(src='@/assets/curso/temas/tema1/img02.svg', alt='Imagen decorativa')
    separador
    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 1.1 Determinantes sociales y necesidad de articulación intersectorial
    p.mb-5(data-aos="fade-down") Los determinantes sociales de la salud corresponden a las condiciones estructurales y a los factores intermedios que influyen en el bienestar físico, mental y social de las personas y comunidades. La Organización Mundial de la Salud define estos determinantes como las circunstancias en las que las personas nacen, crecen, viven, trabajan y envejecen, las cuales están condicionadas por la distribución del poder, los recursos y las oportunidades dentro de una sociedad.
    .row.justify-content-center.mb-5
      .col-lg-10.order-lg-1.order-2
        .cajon.cajon.C01.color-primario.p-4.mb-5
          p.mb-0(data-aos="fade-down") En el caso de la población migrante, estos determinantes cobran especial relevancia debido a la ruptura de redes de apoyo, los cambios en el acceso a servicios, la exposición a riesgos y las condiciones de vulnerabilidad asociadas a la movilidad humana.
        p.mb-0.text-center(data-aos="fade-down") Entre los determinantes estructurales que influyen en la salud de la población migrante se destacan:
    .BG01.mb-5(data-aos="flip-up")
      .row.justify-content-center.align-items-center(data-aos="fade-down")
        .col-lg-4.d-none.d-lg-block
          figure(data-aos="zoom-in")
            img(src="@/assets/curso/temas/tema1/img03.png", alt="Imagen decorativa")
        .col-lg-8
          SlyderF.custom.color-acento-botones(columnas="col-lg-6 col-xl-4")
            .tarjeta.tarjeta--slyder.p-4
              .row.justify-content-center.mb-3
                .col-6.col-lg-8
                  img(src="@/assets/curso/temas/tema1/img04.svg", alt="Imagen decorativa").img100.m-auto
              p Estatus migratorio y procesos de regularización.
            .tarjeta.tarjeta--slyder.p-4
              .row.justify-content-center.mb-3
                .col-6.col-lg-8
                  img(src="@/assets/curso/temas/tema1/img05.svg", alt="Imagen decorativa").img100.m-auto
              p Disponibilidad y acceso a los servicios de salud.
            .tarjeta.tarjeta--slyder.p-4
              .row.justify-content-center.mb-3
                .col-6.col-lg-8
                  img(src="@/assets/curso/temas/tema1/img06.svg", alt="Imagen decorativa").img100.m-auto
              p Protección social y acceso a programas de apoyo.
            .tarjeta.tarjeta--slyder.p-4
              .row.justify-content-center.mb-3
                .col-6.col-lg-8
                  img(src="@/assets/curso/temas/tema1/img07.svg", alt="Imagen decorativa").img100.m-auto
              p Situación laboral y condiciones de empleo.
            .tarjeta.tarjeta--slyder.p-4
              .row.justify-content-center.mb-3
                .col-6.col-lg-8
                  img(src="@/assets/curso/temas/tema1/img08.svg", alt="Imagen decorativa").img100.m-auto
              p Condiciones de pobreza y exclusión social.
            .tarjeta.tarjeta--slyder.p-4
              .row.justify-content-center.mb-3
                .col-6.col-lg-8
                  img(src="@/assets/curso/temas/tema1/img09.svg", alt="Imagen decorativa").img100.m-auto
              p Capacidad institucional y normativa del territorio.
    p(data-aos="fade-down") Estos factores condicionan directamente el acceso a los servicios y la capacidad de respuesta de las entidades territoriales, dependiendo de la disponibilidad de recursos humanos, técnicos y financieros.
    p.mb-5(data-aos="fade-down") Asimismo, los determinantes intermedios influyen en la experiencia de integración y bienestar de la población migrante, entre ellos:
    .row.justify-content-center.mb-5
      .col-lg-10.col-12
        .row.justify-content-center.tarjeta.tarjeta--C01.align-items-center.pt-0.pb-0.mb-4
          .row.justify-content-center.align-items-center
            .col-lg-6.col-12.order-lg-2.order-2
              ol.lista-ol--cuadro.lista-ol.mb-0
                li.mb-2
                  .lista-ol--cuadro__vineta
                    span.text-bold 1
                  | Redes familiares y comunitarias.
                li.mb-2
                  .lista-ol--cuadro__vineta
                    span.text-bold 2
                  | Capital social y vínculos de apoyo.
                li.mb-2
                  .lista-ol--cuadro__vineta
                    span.text-bold 3
                  | Condiciones de vivienda.
                li.mb-2
                  .lista-ol--cuadro__vineta
                    span.text-bold 4
                  | Seguridad alimentaria.
                li.mb-2
                  .lista-ol--cuadro__vineta
                    span.text-bold 5
                  | Acceso a educación.
                li.mb-2
                  .lista-ol--cuadro__vineta
                    span.text-bold 6
                  | Entornos comunitarios seguros.
                li.mb-2
                  .lista-ol--cuadro__vineta
                    span.text-bold 7
                  | Barreras idiomáticas, estigmatización y discriminación.
            .col-lg-6.col-8.col-md-7.order-lg-1.order-1.mb-3
              figure
                img(src='@/assets/curso/temas/tema1/img10.svg', alt='Imagen decorativa')
        p(data-aos="fade-down") La ruptura de redes, la estigmatización y las barreras culturales afectan de manera significativa el bienestar emocional y social, lo que exige respuestas integrales desde distintos sectores.
        p.mb-0(data-aos="fade-down") La articulación intersectorial se convierte en una necesidad estructural, ya que ningún sector por sí solo cuenta con la capacidad técnica, operativa y normativa para responder a la complejidad de la movilidad humana. Por ejemplo:
    .row.mb-5(data-aos="flip-up")
      .col-md-6.col-lg.tarjeta--tabla.p-4
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema1/img11.svg' alt='AvatarTop')
        p.text-center.text-bold(data-aos="fade-down") El sector salud aporta atención básica, urgencias, promoción y prevención.
      .col-md-6.col-lg.tarjeta--tabla.p-4
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema1/img12.svg' alt='AvatarTop')
        p.text-center.text-bold(data-aos="fade-down") El sector educación facilita la integración escolar.
      .col-md-6.col-lg.tarjeta--tabla.p-4
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema1/img13.svg' alt='AvatarTop')
        p.text-center.text-bold(data-aos="fade-down") La protección social identifica y gestiona riesgos.
      .col-md-6.col-lg.tarjeta--tabla.p-4
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema1/img14.svg' alt='AvatarTop')
        p.text-center.text-bold(data-aos="fade-down") El sector productivo fortalece oportunidades laborales.
      .col-md-6.col-lg.tarjeta--tabla.p-4
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema1/img15.svg' alt='AvatarTop')
        p.text-center.text-bold(data-aos="fade-down") Las entidades territoriales activan rutas de atención, remisión y seguimiento.
    .row.justify-content-center.mb-5
      .col-lg-10.col-12
        p.mb-0.text-center(data-aos="fade-down") En este sentido, los determinantes sociales obligan a las instituciones a desarrollar estrategias de trabajo conjunto que permitan:
    .row.justify-content-center.mb-5
      .col-lg-10.col-12
        .row.justify-content-center
          .col-lg-6.col-12
            .row.justify-content-center
              .col-lg-auto.col-3.col-sm-2.px-0.mb-4(data-aos="flip-up")
                .cajon.cajon.C02.p-0.h-100
                  img.w-100.h-100.my-auto(src='@/assets/curso/temas/tema1/img16.svg' alt="Imagen decorativa")
              .col-lg-9.col-8.px-0.mb-4(data-aos="fade-down")
                .cajon.cajon.C01.p-3.h-100.d-flex.align-items-center
                  h5 Identificar tempranamente situaciones de vulnerabilidad.
          .col-lg-6.col-12
            .row.justify-content-center
              .col-lg-auto.col-3.col-sm-2.px-0.mb-4(data-aos="flip-up")
                .cajon.cajon.C02.p-0.h-100
                  img.w-100.h-100.my-auto(src='@/assets/curso/temas/tema1/img17.svg' alt="Imagen decorativa")
              .col-lg-9.col-8.px-0.mb-4(data-aos="fade-down")
                .cajon.cajon.C01.p-3.h-100.d-flex.align-items-center
                  h5 Activar rutas integrales de atención.
          .col-lg-6.col-12
            .row.justify-content-center
              .col-lg-auto.col-3.col-sm-2.px-0.mb-4(data-aos="flip-up")
                .cajon.cajon.C02.p-0.h-100
                  img.w-100.h-100.my-auto(src='@/assets/curso/temas/tema1/img18.svg' alt="Imagen decorativa")
              .col-lg-9.col-8.px-0.mb-4(data-aos="fade-down")
                .cajon.cajon.C01.p-3.h-100.mb-0.d-flex.align-items-center
                  h5 Definir responsabilidades sectoriales.
          .col-lg-6.col-12
            .row.justify-content-center
              .col-lg-auto.col-3.col-sm-2.px-0.mb-4(data-aos="flip-up")
                .cajon.cajon.C02.p-0.h-100
                  img.w-100.h-100.my-auto(src='@/assets/curso/temas/tema1/img19.svg' alt="Imagen decorativa")
              .col-lg-9.col-8.px-0.mb-4(data-aos="fade-down")
                .cajon.cajon.C01.p-3.h-100.d-flex.align-items-center
                  h5 Implementar acciones complementarias.
    .row.justify-content-center.mb-0
      .col-lg-10.col-12
        p.mb-0(data-aos="fade-down") La articulación intersectorial fortalece la eficiencia de la respuesta institucional y mejora la capacidad de los territorios para gestionar de manera sostenible los efectos de la migración, promoviendo el bienestar y la inclusión de la población migrante y de las comunidades de acogida.
    separador
    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 1.2 Rol del sector salud en escenarios de movilidad humana
    .bloque-texto-g.bloque-texto-g--inverso.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="flip-up")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema1/img20.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0(data-aos="fade-down") El sector salud, en el contexto de la movilidad humana, constituye un eje estratégico para garantizar la protección y el bienestar integral de las poblaciones migrantes, retornadas y comunidades de acogida. El proceso migratorio expone a las personas a múltiples riesgos asociados a condiciones inadecuadas de vivienda, barreras de acceso a los servicios de salud, dificultades idiomáticas, irregularidad migratoria, estigmatización, discriminación y ruptura de redes sociales. En este escenario, el sector salud asume un rol que trasciende la atención asistencial y se configura como un actor articulador, orientador y garante de derechos fundamentales.
    p.mb-5(data-aos="fade-down") Desde la perspectiva de la Organización Mundial de la Salud, los sistemas de salud deben establecer respuestas integradas, equitativas y culturalmente pertinentes para reducir las desigualdades asociadas a la migración. Estas respuestas se concretan en cuatro ámbitos:
    .row.justify-content-center.mb-0(data-aos="flip-down")
      .col-xl-3.col-lg-8.mb-4.mb-xl-5
        .crd.crd--grayGrad
          .bottomCircle.mb-5
            figure
              img(src="@/assets/curso/temas/tema1/img21.svg", alt="alt").img50.m-auto
          h5.text-center Garantía de acceso oportuno a los servicios de salud
      .col-xl-3.col-lg-8.mb-4.mb-xl-5
        .crd.crd--grayGrad
          .bottomCircle.mb-5
            figure
              img(src="@/assets/curso/temas/tema1/img22.svg", alt="alt").img50.m-auto
          h5.text-center Avance hacia la cobertura universal
      .col-xl-3.col-lg-8.mb-4.mb-xl-5
        .crd.crd--grayGrad
          .bottomCircle.mb-5
            figure
              img(src="@/assets/curso/temas/tema1/img23.svg", alt="alt").img50.m-auto
          h5.text-center Fortalecimiento de la vigilancia en salud pública
      .col-xl-3.col-lg-8.mb-4.mb-xl-5
        .crd.crd--grayGrad
          .bottomCircle.mb-5
            figure
              img(src="@/assets/curso/temas/tema1/img24.svg", alt="alt").img50.m-auto
          h5.text-center Reducción de brechas sociales en salud
    .row.justify-content-center.mb-5
      .col-lg-10.order-lg-1.order-2
        .cajon.cajon.C01.color-primario.p-4
          p.mb-0(data-aos="fade-down") En el contexto colombiano, el sector salud incorpora estos principios a través de la Ley Estatutaria 1751 de 2015, que reconoce la salud como un derecho fundamental de aplicación universal, sin discriminación por nacionalidad o estatus migratorio.
    p(data-aos="fade-down") Una de las funciones centrales del sector salud es garantizar el acceso efectivo a los servicios, independientemente de la situación migratoria. Instrumentos normativos como el Decreto 216 de 2021 (Estatuto Temporal de Protección para Migrantes Venezolanos) y la Circular 024 de 2020 del Ministerio de Salud y Protección Social establecen la obligación de asegurar la atención inicial de urgencias, la vacunación, el control prenatal y el acceso a programas de promoción y prevención.
    p.mb-5(data-aos="fade-down") De igual manera, el sector salud cumple un rol preventivo y protector al promover entornos seguros y saludables, mediante:
    .BG01.mb-5(data-aos="flip-up")
      .row.justify-content-center.align-items-center(data-aos="fade-down")
        .col-lg-4.d-none.d-lg-block
          figure(data-aos="zoom-in")
            img(src="@/assets/curso/temas/tema1/img25.png", alt="Imagen decorativa")
        .col-lg-8
          SlyderF.custom.color-acento-botones(columnas="col-lg-6 col-xl-4")
            .tarjeta.tarjeta--slyder.p-4
              .row.justify-content-center.mb-3
                .col-6.col-lg-8
                  img(src="@/assets/curso/temas/tema1/img26.svg", alt="Imagen decorativa").img100.m-auto
              p Estrategias de atención psicosocial.
            .tarjeta.tarjeta--slyder.p-4
              .row.justify-content-center.mb-3
                .col-6.col-lg-8
                  img(src="@/assets/curso/temas/tema1/img27.svg", alt="Imagen decorativa").img100.m-auto
              p Campañas de información y educación en salud.
            .tarjeta.tarjeta--slyder.p-4
              .row.justify-content-center.mb-3
                .col-6.col-lg-8
                  img(src="@/assets/curso/temas/tema1/img28.svg", alt="Imagen decorativa").img100.m-auto
              p Acciones comunitarias para la reducción del estigma.
            .tarjeta.tarjeta--slyder.p-4
              .row.justify-content-center.mb-3
                .col-6.col-lg-8
                  img(src="@/assets/curso/temas/tema1/img29.svg", alt="Imagen decorativa").img100.m-auto
              p Promoción de la convivencia intercultural.
    .row.justify-content-center.mb-0
      .col-lg-10.col-12
        p(data-aos="fade-down") Adicionalmente, desempeña una función pedagógica al fortalecer la alfabetización en salud de la población migrante, facilitando información clara sobre derechos, rutas de atención, afiliación al sistema y signos de alarma en salud física y mental. La Organización Internacional para las Migraciones (OIM, 2020) resalta que este proceso mejora la adherencia a los tratamientos y favorece la integración comunitaria.
        p.mb-0(data-aos="fade-down") En síntesis, el rol del sector salud en escenarios de movilidad humana es integral y multidimensional. Abarca la garantía de derechos, la vigilancia en salud pública, la atención psicosocial, la coordinación intersectorial y la promoción de entornos protectores, consolidándose como un eje estratégico para la respuesta territorial frente a las necesidades de la población migrante.
    separador
    #t_1_3.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 1.3 Actores sectoriales e intersectoriales en el territorio
    p(data-aos="fade-down") Los actores sectoriales e intersectoriales desempeñan un papel fundamental en la respuesta institucional frente a la movilidad humana. En Colombia, estos actores se organizan de acuerdo con las competencias establecidas en normas como la Ley 715 de 2001, la Ley 1751 de 2015 y la Ley 2136 de 2021 (Política Integral Migratoria), así como en los lineamientos del Sistema General de Seguridad Social en Salud. Su función es garantizar la atención integral, la coordinación operativa, la activación de rutas de atención y la implementación de estrategias de integración para la población migrante, retornada y comunidades de acogida.
    p.mb-5(data-aos="fade-down") La siguiente tabla presenta los principales actores involucrados en la respuesta territorial:
    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-12
        .titulo-sexto.color-acento-contenido
          h5 Tabla 1.
          span <em>Actores fundamentales en la atención a la población en movilidad humana</em>
        .tabla-a.color-acento-contenido
          table
            thead
              tr
                th(data-aos="fade-down")(style= "width: 20%") Sector
                th(data-aos="fade-down")(style= "width: 40%") Actor
                th(data-aos="fade-down")(style= "width: 40%") Función principal
            tbody
              tr
                td.text-bold(data-aos="fade-down")(style="background-color: #F6F6F6") Salud
                td(data-aos="fade-down")(style="background-color: #F6F6F6") Ministerio de Salud y Protección Social (MSPS)
                td(data-aos="fade-down")(style="background-color: #F6F6F6") Define lineamientos técnicos, políticas públicas y orientaciones para la atención integral, afiliación, vigilancia en salud pública y modelos de atención territorial.
              tr
                td.text-bold(data-aos="fade-down") Salud
                td(data-aos="fade-down") Secretarías Departamentales y Municipales de Salud
                td(data-aos="fade-down") Gestionan la respuesta territorial, activan rutas de atención, supervisan el aseguramiento y coordinan las Mesas de Articulación Territorial.
              tr
                td.text-bold(data-aos="fade-down")(style="background-color: #F6F6F6") Salud
                td(data-aos="fade-down")(style="background-color: #F6F6F6") Instituciones Prestadoras de Servicios de Salud (IPS)
                td(data-aos="fade-down")(style="background-color: #F6F6F6") Garantizan la prestación de servicios, atención de urgencias, vacunación, salud materna, atención psicosocial y remisiones interinstitucionales.
              tr
                td.text-bold(data-aos="fade-down") Salud
                td(data-aos="fade-down") Entidades Administradoras de Planes de Beneficios (EAPB)
                td(data-aos="fade-down") Facilitan la afiliación de población con Permiso por Protección Temporal (PPT) y garantizan la cobertura en el sistema de salud.
              tr
                td.text-bold(data-aos="fade-down")(style="background-color: #F6F6F6") Social y protección
                td(data-aos="fade-down")(style="background-color: #F6F6F6") Instituto Colombiano de Bienestar Familiar (ICBF)
                td(data-aos="fade-down")(style="background-color: #F6F6F6") Atiende a niños, niñas y adolescentes migrantes mediante acciones de protección, salud mental, nutrición y fortalecimiento de entornos protectores.
              tr
                td.text-bold(data-aos="fade-down") Social y protección
                td(data-aos="fade-down") Unidad para las Víctimas
                td(data-aos="fade-down") Activa rutas psicosociales en casos de doble afectación, vinculando migración y conflicto armado.
              tr
                td.text-bold(data-aos="fade-down")(style="background-color: #F6F6F6") Social y protección
                td(data-aos="fade-down")(style="background-color: #F6F6F6") Departamento para la Prosperidad Social (DPS)
                td(data-aos="fade-down")(style="background-color: #F6F6F6") Implementa programas de apoyo social, transferencias monetarias y estrategias de inclusión.
              tr
                td.text-bold(data-aos="fade-down") Social y protección
                td(data-aos="fade-down") Alcaldías y Gobernaciones
                td(data-aos="fade-down") Lideran la articulación territorial, convocan mesas intersectoriales y coordinan acciones institucionales.
              tr
                td.text-bold(data-aos="fade-down")(style="background-color: #F6F6F6") Educación
                td(data-aos="fade-down")(style="background-color: #F6F6F6") Ministerio de Educación Nacional (MEN)
                td(data-aos="fade-down")(style="background-color: #F6F6F6") Coordina procesos de inclusión escolar, permanencia educativa y estrategias de integración para niños, niñas y adolescentes migrantes.
              tr
                td.text-bold(data-aos="fade-down") Educación
                td(data-aos="fade-down") Instituciones educativas
                td(data-aos="fade-down") Identifican barreras de acceso, activan rutas de protección y desarrollan acciones comunitarias.
              tr
                td.text-bold(data-aos="fade-down")(style="background-color: #F6F6F6") Humanitario e internacional
                td(data-aos="fade-down")(style="background-color: #F6F6F6") Alto Comisionado de las Naciones Unidas para los Refugiados (ACNUR)
                td(data-aos="fade-down")(style="background-color: #F6F6F6") Brinda asistencia en protección, fortalecimiento institucional y apoyo en procesos de integración.
              tr
                td.text-bold(data-aos="fade-down") Humanitario e internacional
                td(data-aos="fade-down") Organización Internacional para las Migraciones (OIM)
                td(data-aos="fade-down") Coordina acciones en salud, inclusión, retornos voluntarios y fortalecimiento institucional.
              tr
                td.text-bold(data-aos="fade-down")(style="background-color: #F6F6F6") Humanitario e internacional
                td(data-aos="fade-down")(style="background-color: #F6F6F6") Fondo de las Naciones Unidas para la Infancia (UNICEF)
                td(data-aos="fade-down")(style="background-color: #F6F6F6") Desarrolla acciones en educación, protección y salud mental para la infancia migrante.
              tr
                td.text-bold(data-aos="fade-down") Humanitario e internacional
                td(data-aos="fade-down") Cruz Roja
                td(data-aos="fade-down") Apoya en primeros auxilios, acompañamiento psicosocial y reunificación familiar.
              tr
                td.text-bold(data-aos="fade-down")(style="background-color: #F6F6F6") Comunitario y social
                td(data-aos="fade-down")(style="background-color: #F6F6F6") Líderes comunitarios
                td(data-aos="fade-down")(style="background-color: #F6F6F6") Identifican riesgos, promueven la integración y fortalecen las redes comunitarias.
              tr
                td.text-bold(data-aos="fade-down") Comunitario y social
                td(data-aos="fade-down") Organizaciones comunitarias y sociales
                td(data-aos="fade-down") Promueven la participación, el diálogo intercultural y el apoyo mutuo.
              tr
                td.text-bold(data-aos="fade-down")(style="background-color: #F6F6F6") Comunitario y social
                td(data-aos="fade-down")(style="background-color: #F6F6F6") Iglesias y organizaciones religiosas
                td(data-aos="fade-down")(style="background-color: #F6F6F6") Brindan asistencia humanitaria, orientación emocional y apoyo social.
    p.mb-0(data-aos="fade-down") La participación de múltiples actores institucionales, sociales y comunitarios exige altos niveles de coordinación, claridad en la definición de roles y responsabilidades, así como mecanismos estables de articulación intersectorial. De acuerdo con los lineamientos del Ministerio de Salud y Protección Social y de la Organización Internacional para las Migraciones, uno de los principales desafíos en los territorios es la falta de integración efectiva de la información, lo que puede generar duplicidad de acciones, dispersión de esfuerzos y baja efectividad en la respuesta institucional. La ausencia de sistemas de información interoperables dificulta el seguimiento de los casos y la continuidad de los procesos de atención.
    .row.justify-content-center.BG04.align-items-center.pt-5.pb-5.mb-4
      .col-lg-11.col-12
        .row.justify-content-center
          .col-lg-9.col-12.order-lg-2.order-2
            h5.mb-4 Entre los retos más frecuentes de la articulación intersectorial se identifican:
            ol.lista-ol--cuadro.lista-ol--separador.mb-0
              li.mb-2
                .lista-ol--cuadro__vineta
                  span.text-bold 1
                | La duplicidad de acciones por falta de información compartida y ausencia de protocolos unificados.
              li.mb-2
                .lista-ol--cuadro__vineta
                  span.text-bold 2
                | Las limitaciones presupuestales que afectan la cobertura, calidad y sostenibilidad de las intervenciones.
              li.mb-2
                .lista-ol--cuadro__vineta
                  span.text-bold 3
                | Las barreras administrativas que retrasan la activación de rutas y el acceso oportuno a los servicios.
              li.mb-2
                .lista-ol--cuadro__vineta
                  span.text-bold 4
                | La fragmentación territorial, que genera respuestas desiguales entre zonas urbanas, rurales y de frontera.
              li.mb-0
                .lista-ol--cuadro__vineta
                  span.text-bold 5
                | La desigualdad en la capacidad operativa entre municipios, relacionada con la disponibilidad de talento humano, infraestructura y recursos técnicos.
          .col-lg-3.col-8.col-md-7.order-lg-1.order-1
            figure
              img(src='@/assets/curso/temas/tema1/img30.svg', alt='Imagen decorativa')
    p.mb-5(data-aos="fade-down") A pesar de estos desafíos, la articulación entre actores sectoriales e intersectoriales permite la construcción de respuestas más integrales, coordinadas y sostenibles, orientadas al bienestar de la población migrante y de las comunidades de acogida. Esta articulación contribuye a:
    .row.justify-content-center.mb-5
      .col-lg-4.col-lg.mb-5.mb-lg-0(data-aos="flip-up")
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema1/img31.svg' alt='AvatarTop')
          .tarjeta.tarjeta--C02(style= "width: 100%")
            .p-4(data-aos="fade-down")
              p.text-center La generación de rutas de atención unificadas que facilitan la orientación y el acceso a los servicios.
      .col-lg-4.col-lg.mb-5.mb-lg-0(data-aos="flip-up")
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema1/img32.svg' alt='AvatarTop')
          .tarjeta.tarjeta--C02(style= "width: 100%")
            .p-4(data-aos="fade-down")
              p.text-center La optimización de recursos técnicos, financieros y humanos mediante la planificación conjunta.
      .col-lg-4.col-lg.mb-5.mb-lg-0(data-aos="flip-up")
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema1/img33.svg' alt='AvatarTop')
          .tarjeta.tarjeta--C02(style= "width: 100%")
            .p-4(data-aos="fade-down")
              p.text-center El fortalecimiento de la capacidad de respuesta territorial a través de procesos de formación y asistencia técnica.
      .col-lg-4.col-lg.mb-5.mb-lg-0(data-aos="flip-up")
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema1/img34.svg' alt='AvatarTop')
          .tarjeta.tarjeta--C02(style= "width: 100%")
            .p-4(data-aos="fade-down")
              p.text-center La participación de la cooperación internacional como un recurso estratégico para ampliar la cobertura y calidad de las intervenciones.
      .col-lg-4.col-lg.mb-lg-0(data-aos="flip-up")
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema1/img35.svg' alt='AvatarTop')
          .tarjeta.tarjeta--C02(style= "width: 100%")
            .p-4(data-aos="fade-down")
              p.text-center La mejora del acceso efectivo a los servicios de salud, protección social, educación y apoyo psicosocial.
    p.mb-0(data-aos="fade-down") En consecuencia, la acción intersectorial se consolida como un eje fundamental para reducir la vulnerabilidad, fortalecer la protección de derechos y promover procesos sostenibles de integración social de la población en movilidad humana.
</template>

<script>
export default {
  name: 'Tema1',
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
