<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero(data-aos="fade-right")
        span 3
      h1 Lineamientos técnicos y operativos para la acción intersectorial
    .bloque-texto-g.bloque-texto-g--inverso.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="flip-up")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema3/img01.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0(data-aos="fade-down") La acción intersectorial constituye uno de los pilares para la gestión territorial en salud y para la atención integral de la población migrante, retornada y de acogida. Estos lineamientos permiten articular instituciones, definir responsabilidades y orientar intervenciones que garanticen el cumplimiento del marco normativo nacional e internacional. Según el Ministerio de Salud y Protección Social, la articulación sectorial se fundamenta en principios de oportunidad, integralidad y complementariedad, fortaleciendo la capacidad institucional para responder de manera efectiva a las necesidades del territorio.
    p.mb-5(data-aos="fade-down") Para hacerlo más claro, se destacan los elementos esenciales que guían esta acción intersectorial:
    .row.justify-content-center.mb-5(data-aos="flip-down")
      .col-lg-5.col-12.col-lg.m-2
        .row
          .col-12.px-0
            figure(data-aos="fade-up")
              img(src='@/assets/curso/temas/tema3/img02.png', style="width: 100%" ,alt='Imagen decorativa').m-auto
          .col-12.bg-c1.h-100
            .p-4
              h4 Vigilancia en salud pública
              p.mb-0 Incluye la identificación de eventos de interés epidemiológico, el análisis de riesgos y la activación de rutas de respuesta acordes con las dinámicas de movilidad humana.
      .col-lg-5.col-12.col-lg.m-2
        .row
          .col-12.px-0
            figure(data-aos="fade-up")
              img(src='@/assets/curso/temas/tema3/img03.png', style="width: 100%" ,alt='Imagen decorativa').m-auto
          .col-12.bg-c1.h-100
            .p-4
              h4 Intervenciones colectivas e individuales
              p.mb-0 Se orientan por protocolos unificados y rutas de atención que garantizan oportunidad, continuidad y pertinencia cultural.
              br
      .col-lg-5.col-12.col-lg.m-2
        .row
          .col-12.px-0
            figure(data-aos="fade-up")
              img(src='@/assets/curso/temas/tema3/img04.png', style="width: 100%" ,alt='Imagen decorativa').m-auto
          .col-12.bg-c1.h-100
            .p-4
              h4 Coordinación entre sectores e instituciones
              p.mb-0 Involucra secretarías territoriales, autoridades migratorias, cooperación internacional, EPS, IPS y gobiernos locales para asegurar acciones coherentes y complementarias.
      .col-lg-5.col-12.col-lg.m-2
        .row
          .col-12.px-0
            figure(data-aos="fade-up")
              img(src='@/assets/curso/temas/tema3/img05.png', style="width: 100%" ,alt='Imagen decorativa').m-auto
          .col-12.bg-c1.h-100
            .p-4
              h4 Enfoques diferenciales y de derechos
              p.mb-0 Incorporan variables como género, edad, condición migratoria, discapacidad o pertenencia étnica, asegurando intervenciones más justas y pertinentes.}
    .row.justify-content-center.mb-0(data-aos="flip-down")
      .col-lg-10.col-12
        p(data-aos="fade-down") La Organización Panamericana de la Salud (OPS) resalta la importancia de adaptar los procesos de vigilancia, atención y respuesta a las particularidades de la movilidad humana, integrando mecanismos de coordinación técnica y operativa con actores nacionales y territoriales.
        p.mb-0(data-aos="fade-down") En conjunto, estos lineamientos proporcionan un marco sólido para orientar la gestión territorial, armonizar esfuerzos entre sectores y garantizar una respuesta efectiva, oportuna y coherente frente a los retos que plantea la movilidad humana en el país.
    separador
    #t_3_1.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 3.1 Líneas de acción de la vigilancia en salud pública
    p(data-aos="fade-down") La vigilancia en salud pública constituye una herramienta central para identificar, analizar y actuar frente a los eventos que afectan la salud colectiva. De acuerdo con el Decreto 780 de 2016 y los lineamientos del Instituto Nacional de Salud (INS, 2023), la vigilancia implica la recolección sistemática, el análisis oportuno, la interpretación y la difusión de información epidemiológica para orientar acciones de prevención, control y mitigación de riesgos.
    p.mb-5(data-aos="fade-down") En contextos de movilidad humana, estas acciones deben integrar variables como nacionalidad, condición migratoria, trayectorias de desplazamiento, barreras de acceso, determinantes sociales y condiciones del entorno territorial. Las principales líneas de acción aplicables a población migrante, retornada y comunidades de acogida incluyen:
    .desktop
      .row.mb-5
        .col-6.col-md-3.mb-4.mb-xl-0
          .tarjeta.tarjeta-slide.arriba.color-secundario(@mouseover="indicadorTarjetaSlide = false")
            .indicador--hover(v-if="indicadorTarjetaSlide")
            .tarjeta-slide__contenedor
              .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/temas/tema3/img06.png')})`}")
              .tarjeta-slide__contenido.p-auto.p-xl-5
                h4 Vigilancia rutinaria
                p.mb-0 Seguimiento continuo a los Eventos de Interés en Salud Pública (EISP), incluyendo enfermedades transmisibles, patologías crónicas, salud mental, violencias, salud materno-perinatal y vacunación. Esta línea permite identificar cambios en el comportamiento epidemiológico y ajustar respuestas en tiempo real.
        .col-6.col-md-3.mb-4.mb-xl-0
          .tarjeta.tarjeta-slide.arriba.color-secundario(@mouseover="indicadorTarjetaSlide = false")
            .tarjeta-slide__contenedor
              .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/temas/tema3/img07.png')})`}")
              .tarjeta-slide__contenido.p-auto.p-xl-5
                h4 Vigilancia centinela
                p.mb-0 Implementación de puntos estratégicos en zonas fronterizas, corredores migratorios y territorios con alta movilidad. Su propósito es detectar tendencias, alertas tempranas y circulación de agentes infecciosos en grupos altamente móviles.
        .col-6.col-md-3.mb-4.mb-xl-0
          .tarjeta.tarjeta-slide.arriba.color-secundario(@mouseover="indicadorTarjetaSlide = false")
            .tarjeta-slide__contenedor
              .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/temas/tema3/img08.png')})`}")
              .tarjeta-slide__contenido.p-auto.p-xl-5
                h4 Vigilancia comunitaria
                p.mb-0 Participación de líderes comunitarios, gestores interculturales y redes de apoyo migrante para identificar señales tempranas de riesgo, brotes inusuales o barreras de acceso. Es especialmente útil en asentamientos informales, zonas periféricas y territorios sin presencia institucional permanente.
        .col-6.col-md-3.mb-4.mb-xl-0
          .tarjeta.tarjeta-slide.arriba.color-secundario(@mouseover="indicadorTarjetaSlide = false")
            .tarjeta-slide__contenedor
              .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/temas/tema3/img09.png')})`}")
              .tarjeta-slide__contenido.p-auto.p-xl-5
                h4 Análisis de riesgo territorial
                p.mb-0 Integración de datos migratorios, información epidemiológica, determinantes sociales y condiciones geográficas para orientar decisiones intersectoriales. Esta línea permite priorizar intervenciones, asignar recursos y anticipar escenarios de riesgo (INS, 2023).
    .movil
      .row.justify-content-center.align-items-center.mb-5
        .col-md-10.col-12
          .tarjeta.tarjeta--BG07.p-4
            figure.mb-3
              img(src='@/assets/curso/temas/tema3/img10.png', alt='Imagen decorativa')
            h4 Vigilancia rutinaria
            p.mb-0 Seguimiento continuo a los Eventos de Interés en Salud Pública (EISP), incluyendo enfermedades transmisibles, patologías crónicas, salud mental, violencias, salud materno-perinatal y vacunación. Esta línea permite identificar cambios en el comportamiento epidemiológico y ajustar respuestas en tiempo real.
      .row.justify-content-center.align-items-center.mb-5
        .col-md-10.col-12
          .tarjeta.tarjeta--BG07.p-4
            figure.mb-3
              img(src='@/assets/curso/temas/tema3/img11.png', alt='Imagen decorativa')
            h4 Vigilancia centinela
            p.mb-0 Implementación de puntos estratégicos en zonas fronterizas, corredores migratorios y territorios con alta movilidad. Su propósito es detectar tendencias, alertas tempranas y circulación de agentes infecciosos en grupos altamente móviles.
      .row.justify-content-center.align-items-center.mb-5
        .col-md-10.col-12
          .tarjeta.tarjeta--BG07.p-4
            figure.mb-3
              img(src='@/assets/curso/temas/tema3/img12.png', alt='Imagen decorativa')
            h4 Vigilancia comunitaria
            p.mb-0 Participación de líderes comunitarios, gestores interculturales y redes de apoyo migrante para identificar señales tempranas de riesgo, brotes inusuales o barreras de acceso. Es especialmente útil en asentamientos informales, zonas periféricas y territorios sin presencia institucional permanente.
      .row.justify-content-center.align-items-center.mb-5
        .col-md-10.col-12
          .tarjeta.tarjeta--BG07.p-4
            figure.mb-3
              img(src='@/assets/curso/temas/tema3/img13.png', alt='Imagen decorativa')
            h4 Análisis de riesgo territorial
            p.mb-0 Integración de datos migratorios, información epidemiológica, determinantes sociales y condiciones geográficas para orientar decisiones intersectoriales. Esta línea permite priorizar intervenciones, asignar recursos y anticipar escenarios de riesgo (INS, 2023).
    .row.justify-content-center
      .col-lg-10.col-12
        p.mb-0(data-aos="fade-down") El fortalecimiento de la vigilancia para población migrante requiere coordinación permanente con Migración Colombia, entes territoriales, EPS, IPS y cooperación internacional, quienes aportan información sobre flujos migratorios, asentamientos, grupos vulnerables y nuevas dinámicas de desplazamiento. Esta articulación mejora la capacidad de respuesta local, facilita la activación temprana de acciones, reduce brechas de acceso y permite desarrollar intervenciones más oportunas, pertinentes y culturalmente adaptadas.
    separador
    #t_3_2.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 3.2 Intervenciones colectivas e individuales en salud
    p.mb-5(data-aos="fade-down") Las intervenciones colectivas e individuales establecen el marco operativo de la respuesta en salud dirigida a la población migrante, retornada y comunidades de acogida. De acuerdo con la Resolución 518 de 2015 y la Resolución 3280 de 2018, estas intervenciones se organizan bajo el enfoque de gestión del riesgo e integran acciones de promoción, prevención, atención, seguimiento y protección de derechos.
    .row.align-items-center.mb-5(data-aos="flip-down")
      .col-auto.pe-0(style="z-index:2")
        figure
          img(src='@/assets/curso/temas/ico.svg', style="width: 55px" ,alt='').m-auto
      .col-lg-auto.col-9.titulo01(style="z-index:1")
        .p-2
          h3.mb-0.ms-3 a) Intervenciones colectivas
    p.mb-0(data-aos="fade-down") Se implementan en grupos, comunidades o territorios y buscan transformar determinantes sociales, fortalecer capacidades locales y mejorar la respuesta institucional. Dentro de las acciones más relevantes se incluyen:
    .row.justify-content-center.BG08.pt-5.pb-5
      .row.justify-content-center
        .col-12
          .row.justify-content-center.align-items-center
            .col-lg-9.col-12.order-lg-2.order-2
              ol.lista-ol--cuadro.lista-ol--separador.mb-0
                li
                  .lista-ol--cuadro__vineta
                    span.text-bold 1
                  | Jornadas de educación y alfabetización en salud (acceso al sistema, autocuidado, derechos y deberes).
                li
                  .lista-ol--cuadro__vineta
                    span.text-bold 2
                  | Acciones extramurales y brigadas integrales en asentamientos, zonas rurales dispersas y pasos fronterizos.
                li
                  .lista-ol--cuadro__vineta
                    span.text-bold 3
                  | Fortalecimiento de redes de apoyo comunitario, incluyendo líderes migrantes y gestores interculturales.
                li
                  .lista-ol--cuadro__vineta
                    span.text-bold 4
                  | Programas comunitarios en salud mental, con enfoque psicosocial y estrategias de primer apoyo emocional.
                li
                  .lista-ol--cuadro__vineta
                    span.text-bold 5
                  | Diagnósticos participativos y mapeos comunitarios para identificar riesgos, barreras de acceso y necesidades prioritarias.
                li
                  .lista-ol--cuadro__vineta
                    span.text-bold 6
                  | Promoción de convivencia, cohesión social e integración comunitaria, incluyendo actividades culturales y pedagógicas.
                li
                  .lista-ol--cuadro__vineta
                    span.text-bold 7
                  | Intersectorialidad territorial, articulando salud, protección social, educación, migración y cooperación internacional.
            .col-lg-3.col-8.col-md-7.order-lg-1.order-1
              figure
                img(src='@/assets/curso/temas/tema3/img14.svg', alt='Imagen decorativa')
    .row.justify-content-center.mb-5
      .col-lg-10.col-12
        p.mb-0(data-aos="fade-down") Estas acciones permiten abordar problemáticas comunes como el desconocimiento del sistema de salud, las barreras lingüísticas, la discriminación y la desconfianza institucional, factores señalados como críticos por la OPS.
    .row.align-items-center.mb-5(data-aos="flip-down")
      .col-auto.pe-0(style="z-index:2")
        figure
          img(src='@/assets/curso/temas/ico.svg', style="width: 55px" ,alt='').m-auto
      .col-lg-auto.col-9.titulo01(style="z-index:1")
        .p-2
          h3.mb-0.ms-3 b) Intervenciones individuales
    p.mb-5(data-aos="fade-down") Se orientan a la atención directa de personas y familias, priorizando la oportunidad, la continuidad del cuidado y la garantía de derechos. Estas incluyen:
    .row.justify-content-center.mb-4
      .col-lg-6.col-12
        .row.justify-content-center
          .col-lg-2.col-3.col-sm-2.px-0.mb-4(data-aos="flip-up")
            .cajon.cajon.C02.p-0.h-100
              img.w-100.h-100.my-auto(src='@/assets/curso/temas/tema3/img15.svg' alt="Imagen decorativa")
          .col-lg-9.col-8.px-0.mb-4(data-aos="fade-down")
            .cajon.cajon.C01.p-3.h-100.d-flex.align-items-center
              p Valoración clínica, psicosocial y de riesgo, especialmente en gestantes, menores de edad, sobrevivientes de violencia y personas con enfermedades crónicas.
      .col-lg-6.col-12
        .row.justify-content-center
          .col-lg-2.col-3.col-sm-2.px-0.mb-4(data-aos="flip-up")
            .cajon.cajon.C02.p-0.h-100
              img.w-100.h-100.my-auto(src='@/assets/curso/temas/tema3/img16.svg' alt="Imagen decorativa")
          .col-lg-9.col-8.px-0.mb-4(data-aos="fade-down")
            .cajon.cajon.C01.p-3.h-100.d-flex.align-items-center
              p Acompañamiento emocional y primeros auxilios psicológicos ante situaciones de crisis o trayectorias migratorias traumáticas.
      .col-lg-6.col-12
        .row.justify-content-center
          .col-lg-2.col-3.col-sm-2.px-0.mb-4(data-aos="flip-up")
            .cajon.cajon.C02.p-0.h-100
              img.w-100.h-100.my-auto(src='@/assets/curso/temas/tema3/img17.svg' alt="Imagen decorativa")
          .col-lg-9.col-8.px-0.mb-4(data-aos="fade-down")
            .cajon.cajon.C01.p-3.h-100.d-flex.align-items-center
              p Activación de rutas de atención en urgencias, salud materna, vacunación, violencia, salud mental y enfermedades transmisibles.
      .col-lg-6.col-12
        .row.justify-content-center
          .col-lg-2.col-3.col-sm-2.px-0.mb-4(data-aos="flip-up")
            .cajon.cajon.C02.p-0.h-100
              img.w-100.h-100.my-auto(src='@/assets/curso/temas/tema3/img18.svg' alt="Imagen decorativa")
          .col-lg-9.col-8.px-0.mb-4(data-aos="fade-down")
            .cajon.cajon.C01.p-3.h-100.d-flex.align-items-center
              p Seguimiento de casos priorizados, articulado con EPS, IPS, equipos extramurales y actores comunitarios.
      .col-lg-6.col-12
        .row.justify-content-center
          .col-lg-2.col-3.col-sm-2.px-0.mb-4(data-aos="flip-up")
            .cajon.cajon.C02.p-0.h-100
              img.w-100.h-100.my-auto(src='@/assets/curso/temas/tema3/img19.svg' alt="Imagen decorativa")
          .col-lg-9.col-8.px-0.mb-4(data-aos="fade-down")
            .cajon.cajon.C01.p-3.h-100.d-flex.align-items-center
              p Remisiones especializadas y contrarreferencias, garantizando continuidad del cuidado y reducción de barreras administrativas.
      .col-lg-6.col-12
        .row.justify-content-center
          .col-lg-2.col-3.col-sm-2.px-0.mb-4(data-aos="flip-up")
            .cajon.cajon.C02.p-0.h-100
              img.w-100.h-100.my-auto(src='@/assets/curso/temas/tema3/img15.svg' alt="Imagen decorativa")
          .col-lg-9.col-8.px-0.mb-4(data-aos="fade-down")
            .cajon.cajon.C01.p-3.h-100.d-flex.align-items-center
              p Acciones de protección de derechos, incluyendo orientación jurídica básica, canalización a programas sociales y acceso a afiliación cuando aplique.
    p.mb-5(data-aos="fade-down") El enfoque diferencial, establecido en normativas como la Ley 1098 de 2006 (infancia), Ley 1257 de 2008 (violencias contra la mujer) y Ley 1616 de 2013 (salud mental), es de aplicación obligatoria en la ejecución de las intervenciones. Este enfoque garantiza:
    .row.justify-content-center.mb-5
      .col-lg-4.col-lg.mb-5.mb-lg-0(data-aos="flip-up")
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema3/img21.svg' alt='AvatarTop')
          .tarjeta.tarjeta--C02(style= "width: 100%")
            .p-4(data-aos="fade-down")
              p.text-center Atención ajustada a edad, género, orientación sexual e identidad de género.
      .col-lg-4.col-lg.mb-5.mb-lg-0(data-aos="flip-up")
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema3/img22.svg' alt='AvatarTop')
          .tarjeta.tarjeta--C02(style= "width: 100%")
            .p-4(data-aos="fade-down")
              p.text-center Reconocimiento de pertenencia étnica y prácticas culturales.
      .col-lg-4.col-lg.mb-5.mb-lg-0(data-aos="flip-up")
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema3/img23.svg' alt='AvatarTop')
          .tarjeta.tarjeta--C02(style= "width: 100%")
            .p-4(data-aos="fade-down")
              p.text-center Adaptaciones para personas con discapacidad o condiciones especiales de vulnerabilidad.
    .row.justify-content-center.mb-5
      .col-lg-10.col-12
        p.mb-0.text-center(data-aos="fade-down") En el caso de la población migrante, las intervenciones deben incorporar:
    .row.mb-0(data-aos="flip-up")
      .col-md-6.col-lg.tarjeta--tabla.p-4
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema3/img24.svg' alt='AvatarTop')
        p.text-center(data-aos="fade-down") Mediación intercultural y apoyo de intérpretes o gestores bilingües.
      .col-md-6.col-lg.tarjeta--tabla.p-4
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema3/img25.svg' alt='AvatarTop')
        p.text-center(data-aos="fade-down") Adaptación cultural de mensajes de salud y materiales educativos multilingües.
      .col-md-6.col-lg.tarjeta--tabla.p-4
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema3/img26.svg' alt='AvatarTop')
        p.text-center(data-aos="fade-down") Consideración de trayectorias migratorias, que pueden incluir duelos, rupturas familiares, violencia o precariedad económica.
      .col-md-6.col-lg.tarjeta--tabla.p-4
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema3/img27.svg' alt='AvatarTop')
        p.text-center(data-aos="fade-down") Revisión de determinantes sociales, como irregularidad migratoria, hacinamiento, pobreza o informalidad laboral.
    separador
    #t_3_3.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 3.3 Situaciones de interés en salud pública relacionadas con migrantes
    p.mb-5(data-aos="fade-down") Las Situaciones de Interés en Salud Pública (SISP) corresponden a eventos, condiciones o riesgos que afectan de manera significativa la salud colectiva y requieren vigilancia reforzada, análisis permanente y acciones de respuesta inmediata. De acuerdo con el Instituto Nacional de Salud (INS, 2023) y la OPS, en los contextos de movilidad humana estas situaciones pueden intensificarse debido a condiciones de vulnerabilidad social, irregularidad migratoria, barreras de acceso y dificultades en la continuidad del cuidado. Entre las SISP más relevantes en población migrante se encuentran:
    .tarjeta.tarjeta--BG09.p-4.mb-5
      LineaTiempoC.color-acento-botones(text-small)(data-aos="flip-up")
        .row.py-5.px-4(titulo="a.")
          .col-lg-5.mb-4.mb-md-0.order-lg-2.order-2
            h4 Enfermedades transmisibles
            p Tuberculosis, infección por VIH, sífilis gestacional y congénita, hepatitis virales, enfermedades prevenibles por vacunas, COVID-19 y otras infecciones respiratorias agudas.
          .col-lg-7.order-lg-1.order-1.mb-lg-0.mb-4
            figure
              img(src='@/assets/curso/temas/tema3/img28.jpg', alt='Imagen decorativa')
        .row.py-5.px-4(titulo="b.")
          .col-lg-5.mb-4.mb-md-0.order-lg-2.order-2
            h4 Salud mental
            p Afectaciones emocionales relacionadas con el proceso migratorio, duelo migratorio, ansiedad, depresión, estrés postraumático, consumo de sustancias y riesgo suicida.
          .col-lg-7.order-lg-1.order-1.mb-lg-0.mb-4
            figure
              img(src='@/assets/curso/temas/tema3/img29.jpg', alt='Imagen decorativa')
        .row.py-5.px-4(titul5="c.")
          .col-lg-5.mb-4.mb-md-0.order-lg-2.order-2
            h4 Violencias
            p Violencia basada en género, explotación laboral, trata de personas, violencia intrafamiliar y violencias sexuales, en concordancia con la Ley 1257 de 2008 y la Ley 1719 de 2014.
          .col-lg-7.order-lg-1.order-1.mb-lg-0.mb-4
            figure
              img(src='@/assets/curso/temas/tema3/img30.jpg', alt='Imagen decorativa')
        .row.py-5.px-4(titulo="d.")
          .col-lg-5.mb-4.mb-md-0.order-lg-2.order-2
            h4 Salud materno-perinatal
            p Inicio tardío del control prenatal, riesgo obstétrico en gestantes sin aseguramiento, dificultades en acceso a parto seguro y baja adherencia a controles postnatales.
          .col-lg-7.order-lg-1.order-1.mb-lg-0.mb-4
            figure
              img(src='@/assets/curso/temas/tema3/img31.jpg', alt='Imagen decorativa')
        .row.py-5.px-4(titul5="e.")
          .col-lg-5.mb-4.mb-md-0.order-lg-2.order-2
            h4 Enfermedades crónicas no transmisibles (ECNT)
            p Hipertensión, diabetes, enfermedades cardiometabólicas y descompensaciones clínicas por falta de acceso a tratamiento, interrupción del cuidado o desabastecimiento de medicamentos.
          .col-lg-7.order-lg-1.order-1.mb-lg-0.mb-4
            figure
              img(src='@/assets/curso/temas/tema3/img32.jpg', alt='Imagen decorativa')
        .row.py-5.px-4(titulo="f.")
          .col-lg-5.mb-4.mb-md-0.order-lg-2.order-2
            h4 Condiciones asociadas a determinantes sociales
            p Desnutrición, inseguridad alimentaria, hacinamiento, insalubridad, exposición a riesgos ambientales y trabajos de alto riesgo.
          .col-lg-7.order-lg-1.order-1.mb-lg-0.mb-4
            figure
              img(src='@/assets/curso/temas/tema3/img33.jpg', alt='Imagen decorativa')
    p.mb-0(data-aos="fade-down") El análisis de las SISP permite orientar decisiones intersectoriales, priorizar recursos y diseñar intervenciones diferenciales para los grupos en mayor vulnerabilidad. Su abordaje requiere una respuesta articulada con entidades como el ICBF, comisarías de familia, sector educativo, vivienda, primera infancia, autoridades migratorias y cooperación internacional. Esta coordinación facilita la activación de rutas integrales de atención, la garantía de derechos y la mitigación oportuna de riesgos, fortaleciendo la capacidad territorial para responder a las dinámicas de la movilidad humana.
    separador
    #t_3_4.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 3.4 Protocolos, rutas y guías técnicas vigentes
    p.mb-5(data-aos="fade-down") Los protocolos, rutas y guías técnicas establecen los procedimientos necesarios para garantizar una atención oportuna, integral y coordinada en los territorios. Estos instrumentos orientan la respuesta institucional frente a la población migrante, retornada y de acogida, definiendo responsabilidades, flujos de atención y mecanismos de articulación. Uno de los elementos centrales es el conocimiento de la ruta de atención en salud para migrantes y retornados, la cual incluye:
    .BG01.mb-5(data-aos="flip-up")
      .row.justify-content-center.align-items-center(data-aos="fade-down")
        .col-lg-4.d-none.d-lg-block
          figure(data-aos="zoom-in")
            img(src="@/assets/curso/temas/tema3/img34.png", alt="Imagen decorativa")
        .col-lg-8
          SlyderF.custom.color-acento-botones(columnas="col-lg-6 col-xl-4")
            .tarjeta.tarjeta--slyder.p-4
              .row.justify-content-center.mb-3
                .col-6.col-lg-8
                  img(src="@/assets/curso/temas/tema3/img35.svg", alt="Imagen decorativa").img100.m-auto
              p Orientación inicial sobre derechos en salud, rutas de acceso y oferta disponible en el territorio.
            .tarjeta.tarjeta--slyder.p-4
              .row.justify-content-center.mb-3
                .col-6.col-lg-8
                  img(src="@/assets/curso/temas/tema3/img36.svg", alt="Imagen decorativa").img100.m-auto
              p Afiliación cuando aplica, incluyendo titulares de ESTP, Permiso por Protección Temporal (PPT) y personas nacionalizadas.
            .tarjeta.tarjeta--slyder.p-4
              .row.justify-content-center.mb-3
                .col-6.col-lg-8
                  img(src="@/assets/curso/temas/tema3/img37.svg", alt="Imagen decorativa").img100.m-auto
              p Atención de urgencias sin restricción, conforme a la Ley Estatutaria 1751 de 2015 y el Decreto 780 de 2016.
            .tarjeta.tarjeta--slyder.p-4
              .row.justify-content-center.mb-3
                .col-6.col-lg-8
                  img(src="@/assets/curso/temas/tema3/img38.svg", alt="Imagen decorativa").img100.m-auto
              p Seguimiento territorial, articulado entre EPS, IPS y entidades locales de salud.
            .tarjeta.tarjeta--slyder.p-4
              .row.justify-content-center.mb-3
                .col-6.col-lg-8
                  img(src="@/assets/curso/temas/tema3/img39.svg", alt="Imagen decorativa").img100.m-auto
              p Remisión y contrarreferencia según la necesidad clínica o psicosocial.
    p(data-aos="fade-down") En materia de salud mental, la Ley 1616 de 2013, la Resolución 4886 de 2018 (Política Nacional de Salud Mental) y la Ley 2460 de 2025 establecen los lineamientos técnicos y normativos para la identificación, atención, acompañamiento y seguimiento de necesidades emocionales. La Ley 2460 de 2025, vigente desde el 16 de junio de 2025, redefine la salud mental como un derecho fundamental, elimina la remisión obligatoria para acceder a psicología clínica, refuerza la atención comunitaria e impulsa estrategias de prevención del consumo de sustancias y del suicidio. Estos lineamientos se sustentan en principios de dignidad humana, enfoque de derechos, interculturalidad y atención integral.
    p.mb-5(data-aos="fade-down") En el contexto migratorio, estas directrices permiten organizar respuestas institucionales culturalmente pertinentes y sensibles a las trayectorias migratorias. Para ello, se priorizan intervenciones como:
    .row.mb-5(data-aos="flip-up")
      .col-md-6.col-lg.tarjeta--tabla.p-4
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema3/img40.svg' alt='AvatarTop')
        p.text-center(data-aos="fade-down") Atención psicosocial
      .col-md-6.col-lg.tarjeta--tabla.p-4
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema3/img41.svg' alt='AvatarTop')
        p.text-center(data-aos="fade-down") Intervención en crisis
      .col-md-6.col-lg.tarjeta--tabla.p-4
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema3/img42.svg' alt='AvatarTop')
        p.text-center(data-aos="fade-down") Acompañamiento emocional
      .col-md-6.col-lg.tarjeta--tabla.p-4
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema3/img43.svg' alt='AvatarTop')
        p.text-center(data-aos="fade-down") Activación de rutas de protección
      .col-md-6.col-lg.tarjeta--tabla.p-4
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema3/img44.svg' alt='AvatarTop')
        p.text-center(data-aos="fade-down") Rutas intersectoriales coordinadas
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="flip-down")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema3/img45.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Las rutas intersectoriales articulan acciones entre salud, educación, protección social, justicia, bienestar familiar y cooperación internacional, garantizando respuestas integrales frente a riesgos que afectan a personas en movilidad humana. Desde la Resolución 521 de 2020 y el Decreto 780 de 2016, se establece la obligación de asegurar acceso efectivo a servicios sin importar el estatus migratorio, promover la continuidad del cuidado y unificar criterios operativos entre instituciones, evitando duplicación de esfuerzos y fortaleciendo la gobernanza territorial.
    .row.justify-content-center.mb-0
      .col-lg-10.col-12
        p.mb-0(data-aos="fade-down") Los diferentes instrumentos estructurados como protocolos, flujogramas, rutas de atención, mecanismos de coordinación y guías técnicas, permiten que la atención territorial sea homogénea, basada en evidencia y alineada con el marco normativo nacional e internacional. De esta manera, se garantiza que la respuesta institucional sea técnica, coherente y adaptada a los riesgos diferenciados presentes en escenarios de movilidad humana.
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
