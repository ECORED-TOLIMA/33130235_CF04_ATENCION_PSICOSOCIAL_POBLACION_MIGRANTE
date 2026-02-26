<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="fade-right")
      .titulo-principal__numero
        span 2
      h1 Coordinación sectorial e intersectorial para la atención de la población migrante
    figure.mb-5(data-aos="flip-up") 
      img(src="@/assets/curso/temas/tema2/img01.png", alt="Imagen decorativa")
    p.mb-4(data-aos="fade-down") La movilidad humana plantea desafíos que superan la capacidad de respuesta de un solo sector, dado que involucra dimensiones sanitarias, sociales, educativas, económicas y comunitarias que requieren intervenciones integrales, continuas y sostenibles. De acuerdo con la Política Integral Migratoria establecida en la Ley 2136 de 2021, la atención a la población migrante debe estructurarse a partir de acciones coordinadas entre sectores, niveles de gobierno y actores territoriales, garantizando el acceso efectivo a servicios, la protección de derechos y la gestión oportuna de los riesgos en salud y protección social.
    .row.justify-content-center.mb-4.align-items-center
      .col-lg-8.order-lg-2.order-2
        .cajon.cajon.C03.color-secundario.p-4.mb-4
          p.mb-0(data-aos="fade-down") En este contexto, organismos internacionales como la Organización Internacional para las Migraciones (OIM) y ACNUR han señalado que la articulación intersectorial es indispensable para atender de manera integral las necesidades de las personas en situación de movilidad humana, bajo principios de dignidad, protección, enfoque diferencial, interculturalidad y participación comunitaria (OIM y ACNUR). La coordinación sectorial e intersectorial se consolida, así, como un eje estratégico para garantizar la protección efectiva, el acceso a servicios esenciales y la atención adecuada de las necesidades de la población migrante, retornada y de las comunidades de acogida. Estos procesos permiten articular recursos, capacidades técnicas y competencias institucionales para enfrentar las situaciones complejas derivadas del tránsito, asentamiento temporal o permanencia en los territorios.
        p.mb-0(data-aos="fade-down") Asimismo, se desarrollan los fundamentos operativos y estratégicos de la articulación intersectorial en salud, abordando el funcionamiento de las Mesas de Articulación Territorial como espacios formales de coordinación. La Resolución 521 de 2020 establece lineamientos para la organización territorial y la coordinación con sectores como educación, protección social, justicia, gestión del riesgo y cooperación internacional, con el fin de garantizar respuestas oportunas, pertinentes y culturalmente adecuadas para la población migrante (Ministerio de Salud y Protección Social, 2020).
      .col-lg-4.order-lg-1.order-1.mb-3.col-md-5.col-7
        figure(data-aos="fade-up") 
          img(src='@/assets/curso/temas/tema2/img02.svg', alt='Imagen decorativa')
    p.mb-0(data-aos="fade-down") La identificación de capacidades institucionales, el análisis de las brechas de atención de las personas sin aseguramiento y la incorporación de enfoques de participación social orientan la toma de decisiones en los territorios. De igual manera, se establece cómo los diferentes sectores convergen en la planeación, ejecución, monitoreo y evaluación de acciones, fortaleciendo la gobernanza local y la capacidad de respuesta institucional frente a las dinámicas de la movilidad humana.
    separador
    #t_2_1.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 2.1 Mesas de Articulación Territorial en Salud
    .bloque-texto-g.bloque-texto-g--inverso.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="flip-up")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema2/img03.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0(data-aos="fade-down") Las Mesas de Articulación Territorial en Salud (MATS) representan un mecanismo clave para la gestión articulada de la respuesta institucional frente a la movilidad humana. Su creación se fundamenta en los lineamientos del Ministerio de Salud y Protección Social, la Política Integral Migratoria establecida en la Ley 2136 de 2021 y los principios del Sistema General de Seguridad Social en Salud consagrados en la Ley 1751 de 2015. Estos espacios permiten integrar información, capacidades y decisiones entre diversos sectores para garantizar una atención integral, oportuna y pertinente.
    p.mb-5(data-aos="fade-down") Las Mesas de Articulación Territorial en Salud están conformadas por actores estratégicos del orden territorial e institucional, tales como:
    .row.justify-content-center.mb-0
      .col-lg-10.col-12.order-lg-2.order-2
        .row.justify-content-center.align-items-center
          .col-lg-4.col-8.col-md-7.order-lg-1.order-1.mb-3
            figure
              img(src='@/assets/curso/temas/tema2/img04.png', alt='Imagen decorativa')
          .col-lg-8.col-12.order-lg-2.order-2
            .tarjeta.tarjeta--C01.p-4.mb-5.pb-4.pt-4
              .row.justify-content-center.align-items-center
                ul.lista-ul--color.mb-0(data-aos="fade-down")
                  li.mb-1
                    i.fas.fa-cog
                    p.mb-0 Secretaría de Salud (liderazgo técnico).
                  li.mb-1
                    i.fas.fa-cog
                    p.mb-0 Oficina de Gestión Social.
                  li.mb-1
                    i.fas.fa-cog
                    p.mb-0 Secretaría de Educación.
                  li.mb-1
                    i.fas.fa-cog
                    p.mb-0 Secretaría de Gobierno.
                  li.mb-1
                    i.fas.fa-cog
                    p.mb-0 Instituto Colombiano de Bienestar Familiar (ICBF).
                  li.mb-1
                    i.fas.fa-cog
                    p.mb-0 Unidad para la Atención y Reparación Integral a las Víctimas.
                  li.mb-1
                    i.fas.fa-cog
                    p.mb-0 Migración Colombia.
                  li.mb-1
                    i.fas.fa-cog
                    p.mb-0 Defensoría del Pueblo.
                  li.mb-1
                    i.fas.fa-cog
                    p.mb-0 Centro Regulador de Urgencias, Emergencias y Desastres (CRUE).
                  li.mb-1
                    i.fas.fa-cog
                    p.mb-0 Instituciones Prestadoras de Servicios de Salud (IPS) públicas y privadas.
                  li.mb-1
                    i.fas.fa-cog
                    p.mb-0 Organismos de cooperación internacional.
                  li.mb-0
                    i.fas.fa-cog
                    p.mb-0 Organizaciones comunitarias y liderazgos de población migrante.
    .row.justify-content-center.mb-4.align-items-center
      .col-lg-10
        .cajon.cajon.C03.color-secundario.p-4.mb-4
          p.mb-0(data-aos="fade-down") El propósito principal de las MATS es coordinar, articular y orientar las acciones operativas del territorio para responder a las necesidades en salud de la población migrante y retornada, promoviendo un enfoque de derechos y reduciendo las brechas de acceso derivadas del estatus migratorio, la vulnerabilidad socioeconómica y las barreras administrativas.
    .row.justify-content-center.mb-5.align-items-center
      .col-lg-10
        p.mb-0.text-center(data-aos="fade-down") Entre las funciones esenciales de las Mesas de Articulación Territorial en Salud se encuentran:
    .row.justify-content-center.align-items-center.mb-5(data-aos="flip-up")
      SlyderF.color-acento-botones(columnas="col-lg-6 col-xl-4")
        .tarjeta.tarjeta--BG05.p-4
          .row.justify-content-center.mb-3
            .col-lg-7.col-sm-4.col-7
              img(src='@/assets/curso/temas/tema2/img05.svg' alt='AvatarTop')
          p Analizar la situación de salud con base en información epidemiológica, demográfica y social del territorio.
        .tarjeta.tarjeta--BG05.p-4
          .row.justify-content-center.mb-3
            .col-lg-7.col-sm-4.col-7
              img(src='@/assets/curso/temas/tema2/img06.svg' alt='AvatarTop')
          p Definir prioridades de atención a partir de alertas tempranas, eventos emergentes y brechas críticas.
        .tarjeta.tarjeta--BG05.p-4
          .row.justify-content-center.mb-3
            .col-lg-7.col-sm-4.col-7
              img(src='@/assets/curso/temas/tema2/img07.svg' alt='AvatarTop')
          p Unificar rutas de atención, clarificando responsabilidades entre IPS, EAPB, entes territoriales y actores de cooperación internacional.
        .tarjeta.tarjeta--BG05.p-4
          .row.justify-content-center.mb-3
            .col-lg-7.col-sm-4.col-7
              img(src='@/assets/curso/temas/tema2/img08.svg' alt='AvatarTop')
          p Coordinar acciones intersectoriales entre salud, educación, protección social, vivienda, migración, justicia y actores humanitarios.
        .tarjeta.tarjeta--BG05.p-4
          .row.justify-content-center.mb-3
            .col-lg-7.col-sm-4.col-7
              img(src='@/assets/curso/temas/tema2/img09.svg' alt='AvatarTop')
          p Promover la participación comunitaria mediante la inclusión de líderes migrantes y organizaciones territoriales.
        .tarjeta.tarjeta--BG05.p-4
          .row.justify-content-center.mb-3
            .col-lg-7.col-sm-4.col-7
              img(src='@/assets/curso/temas/tema2/img10.svg' alt='AvatarTop')
          p Gestionar recursos institucionales y de cooperación destinados a la atención de la movilidad humana.
        .tarjeta.tarjeta--BG05.p-4
          .row.justify-content-center.mb-3
            .col-lg-7.col-sm-4.col-7
              img(src='@/assets/curso/temas/tema2/img11.svg' alt='AvatarTop')
          p Realizar seguimiento a la implementación de lineamientos, protocolos y acuerdos operativos.
    .row.justify-content-center.mb-0.align-items-center
      .col-lg-10
        p.mb-0(data-aos="fade-down") La composición multisectorial de las MATS permite construir una comprensión integral del contexto territorial, fortaleciendo la capacidad de respuesta institucional. La evidencia disponible indica que la coordinación intersectorial mejora la eficiencia, amplía la cobertura y acelera la atención oportuna de la población migrante.
    separador
    #t_2_2.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 2.2 Capacidades institucionales y territoriales para la atención en salud a la población migrante
    p.mb-5(data-aos="fade-down") Las capacidades institucionales y territoriales corresponden al conjunto de recursos, procesos y condiciones que permiten a los entes del sector salud y a otros sectores garantizar la atención integral de la población migrante, retornada y de acogida. Estas capacidades abarcan infraestructura, gestión administrativa, coordinación intersectorial, talento humano, redes comunitarias y mecanismos de articulación territorial.
    .row.justify-content-center.align-items-center.mb-0(data-aos="flip-up")
      .col-lg-10.col-12.mb-md-0.order-lg-2.order-2.mb-lg-0
        LineaTiempoD.color-acento-botones.especial
          .row(numero="1" titulo="Capacidades estructurales")
            .col-12.mb-4.mb-md-0
              p Según el Ministerio de Salud y Protección Social, estas capacidades son determinantes para asegurar la respuesta inicial en los territorios:
              .tarjeta.tarjeta--blanca.p-4.mb-0
                ul.lista-ul--color.mb-0(data-aos="fade-down")
                  li.mb-0
                    i.lista-ul__vineta
                    p.mb-0 Infraestructura física disponible (hospitales, puestos de salud, centros de atención extramural).
                  li.mb-0
                    i.lista-ul__vineta
                    p.mb-0 Sistemas de información en salud, como SIVIGILA, RUAF, SISMUESTRAS y tableros territoriales de análisis.
                  li.mb-0
                    i.lista-ul__vineta
                    p.mb-0 Redes de prestadores y servicios habilitados según la normatividad vigente.
                  li.mb-4
                    i.lista-ul__vineta
                    p.mb-0 Capacidad instalada en urgencias, vacunación, salud materna, salud mental y atención a población sin aseguramiento.
                p.mb-0 Los municipios con baja infraestructura o zonas rurales dispersas tienden a enfrentar mayores barreras en atención oportuna, vigilancia epidemiológica y continuidad del cuidado.
              figure
                img(src='@/assets/curso/temas/tema2/img12.jpg', alt='Imagen decorativa')
          .row(numero="2" titulo="Capacidades organizacionales y técnicas")
            .col-12.mb-4.mb-md-0
              p Estas capacidades fortalecen la articulación sectorial e intersectorial:
              .tarjeta.tarjeta--blanca.p-4.mb-0
                ul.lista-ul--color.mb-0(data-aos="fade-down")
                  li.mb-0
                    i.lista-ul__vineta
                    p.mb-0 Existencia de Planes Territoriales de Salud con componentes específicos de movilidad humana.
                  li.mb-0
                    i.lista-ul__vineta
                    p.mb-0 Protocolos unificados para atención de personas migrantes, retornadas y refugiadas.
                  li.mb-0
                    i.lista-ul__vineta
                    p.mb-0 Funcionamiento de Mesas de Articulación Territorial en Salud (MATS).
                  li.mb-0
                    i.lista-ul__vineta
                    p.mb-0 Equipos técnicos formados en enfoque diferencial, atención psicosocial, interculturalidad y normativa migratoria.
                  li.mb-4
                    i.lista-ul__vineta
                    p.mb-0 Gestión administrativa y financiera que facilita coordinación entre EAPB, IPS, entes territoriales y cooperación internacional.
                p La Organización Internacional para las Migraciones (2020) señala que la formación del talento humano es clave para garantizar intervenciones culturalmente pertinentes y alineadas con estándares nacionales e internacionales.
              figure
                img(src='@/assets/curso/temas/tema2/img13.jpg', alt='Imagen decorativa')
          .row(numero="3" titulo="Capacidades operativas y comunitarias")
            .col-12.mb-4.mb-md-0
              p Estas capacidades permiten ampliar la cobertura y reducir las brechas de acceso:
              .tarjeta.tarjeta--blanca.p-4.mb-0
                ul.lista-ul--color.mb-0(data-aos="fade-down")
                  li.mb-0
                    i.lista-ul__vineta
                    p.mb-0 Acciones extramurales y brigadas integrales en zonas urbanas, rurales y de frontera.
                  li.mb-0
                    i.lista-ul__vineta
                    p.mb-0 Movilización territorial mediante líderes comunitarios, gestores interculturales y redes de apoyo migrante.
                  li.mb-0
                    i.lista-ul__vineta
                    p.mb-0 Coordinación efectiva entre secretarías, EPS, IPS, cooperación internacional y organizaciones sociales.
                  li.mb-0
                    i.lista-ul__vineta
                    p.mb-0 Sistemas de referencia y contrareferencia que permitan atención continua.
                  li.mb-4
                    i.lista-ul__vineta
                    p.mb-0 Participación social a través de organizaciones comunitarias, veedurías y liderazgos migrantes.
                p El fortalecimiento de estas capacidades es esencial para mejorar la eficiencia operativa, garantizar acceso equitativo y cumplir los compromisos de la Política Integral Migratoria (Ley 2136 de 2021) y los estándares de la OPS.
              figure
                img(src='@/assets/curso/temas/tema2/img14.jpg', alt='Imagen decorativa')
    separador
    #t_2_3.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 2.3 Comunidades sin aseguramiento en salud y acciones de respuesta
    p(data-aos="fade-down") La presencia de comunidades sin aseguramiento en salud constituye un desafío estructural para los territorios, especialmente en zonas con alta concentración de población migrante y retornada. La falta de afiliación al Sistema General de Seguridad Social en Salud (SGSSS) se relaciona con movilidad constante, irregularidad migratoria, desconocimiento de los procedimientos de afiliación, barreras idiomáticas y diferencias culturales. Según el Ministerio de Salud y Protección Social, esta situación incrementa el riesgo de no recibir atención oportuna, limita la continuidad del cuidado y profundiza las brechas de acceso entre comunidades receptoras y población en movilidad humana.
    p.mb-5(data-aos="fade-down") Las acciones de respuesta deben alinearse con la Ley Estatutaria 1751 de 2015, la Ley 2136 de 2021 y el Decreto 064 de 2020, que garantizan la atención inicial en salud independientemente del estatus migratorio y orientan la afiliación progresiva de quienes permanecen en el territorio. En concordancia con las orientaciones de la OPS, los entes territoriales deben fortalecer estrategias como:
    .row.justify-content-center.mb-4
      .col-lg-4.col-12
        .row.justify-content-center
          .col-lg-auto.col-3.col-sm-2.px-0.mb-4(data-aos="flip-up")
            .cajon.cajon.C02.p-0.h-100
              img.w-100.h-100.my-auto(src='@/assets/curso/temas/tema2/img15.svg' alt="Imagen decorativa")
          .col-lg-8.col-8.px-0.mb-4(data-aos="fade-down")
            .cajon.cajon.C01.p-3.h-100.d-flex.align-items-center
              p Jornadas de afiliación y registro de población migrante.
      .col-lg-4.col-12
        .row.justify-content-center
          .col-lg-auto.col-3.col-sm-2.px-0.mb-4(data-aos="flip-up")
            .cajon.cajon.C02.p-0.h-100
              img.w-100.h-100.my-auto(src='@/assets/curso/temas/tema2/img16.svg' alt="Imagen decorativa")
          .col-lg-8.col-8.px-0.mb-4(data-aos="fade-down")
            .cajon.cajon.C01.p-3.h-100.d-flex.align-items-center
              p Puntos de orientación en salud y articulación con Migración Colombia.
      .col-lg-4.col-12
        .row.justify-content-center
          .col-lg-auto.col-3.col-sm-2.px-0.mb-4(data-aos="flip-up")
            .cajon.cajon.C02.p-0.h-100
              img.w-100.h-100.my-auto(src='@/assets/curso/temas/tema2/img17.svg' alt="Imagen decorativa")
          .col-lg-8.col-8.px-0.mb-4(data-aos="fade-down")
            .cajon.cajon.C01.p-3.h-100.d-flex.align-items-center
              p Gestores interculturales para facilitar información y acompañamiento.
      .col-lg-4.col-12
        .row.justify-content-center
          .col-lg-auto.col-3.col-sm-2.px-0.mb-4(data-aos="flip-up")
            .cajon.cajon.C02.p-0.h-100
              img.w-100.h-100.my-auto(src='@/assets/curso/temas/tema2/img18.svg' alt="Imagen decorativa")
          .col-lg-8.col-8.px-0.mb-4(data-aos="fade-down")
            .cajon.cajon.C01.p-3.h-100.d-flex.align-items-center
              p Brigadas extramurales en zonas urbanas, rurales y de frontera.
      .col-lg-4.col-12
        .row.justify-content-center
          .col-lg-auto.col-3.col-sm-2.px-0.mb-4(data-aos="flip-up")
            .cajon.cajon.C02.p-0.h-100
              img.w-100.h-100.my-auto(src='@/assets/curso/temas/tema2/img19.svg' alt="Imagen decorativa")
          .col-lg-8.col-8.px-0.mb-4(data-aos="fade-down")
            .cajon.cajon.C01.p-3.h-100.d-flex.align-items-center
              p Coordinación con EPS receptoras para garantizar continuidad de servicios.
      .col-lg-4.col-12
        .row.justify-content-center
          .col-lg-auto.col-3.col-sm-2.px-0.mb-4(data-aos="flip-up")
            .cajon.cajon.C02.p-0.h-100
              img.w-100.h-100.my-auto(src='@/assets/curso/temas/tema2/img20.svg' alt="Imagen decorativa")
          .col-lg-8.col-8.px-0.mb-4(data-aos="fade-down")
            .cajon.cajon.C01.p-3.h-100.d-flex.align-items-center
              p Activación de rutas de urgencias, atención materna, vacunación, tamizajes y apoyo psicosocial.
    p.mb-5(data-aos="fade-down") Adicionalmente, el abordaje de comunidades sin aseguramiento requiere estrategias colectivas que fortalezcan la confianza institucional y promuevan la integración social. Según la OIM, acciones como:
    .row.mb-5(data-aos="flip-up")
      .col-md-6.col-lg.tarjeta--tabla.p-4
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema2/img21.svg' alt='AvatarTop')
        p.text-center.text-bold(data-aos="fade-down") Sensibilización comunitaria y educación sobre derechos en salud.
      .col-md-6.col-lg.tarjeta--tabla.p-4
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema2/img22.svg' alt='AvatarTop')
        p.text-center.text-bold(data-aos="fade-down") Entrega de instructivos multilingües y materiales pedagógicos accesibles.
      .col-md-6.col-lg.tarjeta--tabla.p-4
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema2/img23.svg' alt='AvatarTop')
        p.text-center.text-bold(data-aos="fade-down") Acompañamiento de líderes comunitarios y redes de apoyo migrante.
      .col-md-6.col-lg.tarjeta--tabla.p-4
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema2/img24.svg' alt='AvatarTop')
        p.text-center.text-bold(data-aos="fade-down") Articulación con sectores como educación, protección social, registraduría, gobiernos locales y cooperación internacional.
    .row.justify-content-center.mb-0
      .col-lg-10.col-12
        p.mb-0(data-aos="fade-down") Estas acciones favorecen el acceso oportuno, aumentan la probabilidad de afiliación y permiten una respuesta integral frente a las necesidades de la población migrante. En conjunto, contribuyen a disminuir desigualdades y garantizar el ejercicio pleno del derecho a la salud en contextos de movilidad humana.
    separador
    #t_2_4.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 2.4 Participación social y enfoques diferenciales
    p.mb-5(data-aos="fade-down") La participación social constituye un eje fundamental para fortalecer la salud pública y la atención dirigida a población migrante, retornada y de acogida. Para facilitar su comprensión, a continuación, se presentan sus ideas clave:
    .tarjeta.tarjeta--BG06.p-md-5.p-4.mb-5(data-aos="flip-up")
      SlyderA(tipo="b")
        .row.justify-content-center.p-4
          .col-lg-7.order-lg-1.order-2
            h4 Participación social
            ul.lista-ul.mb-0(data-aos="fade-down")
              li
                i.lista-ul__vineta
                p.mb-0 Facilita que las comunidades influyan en la identificación de necesidades, la planeación territorial y la evaluación de las respuestas institucionales (Ministerio de Salud y Protección Social).
              li
                i.lista-ul__vineta
                p.mb-0 Promueve el reconocimiento mutuo entre comunidades, especialmente en contextos de movilidad humana, reduciendo tensiones y favoreciendo procesos de integración.
              li.mb-0
                i.lista-ul__vineta
                p.mb-0 Se materializa en espacios como Mesas de Participación Social, comités comunitarios y veedurías ciudadanas, los cuales fortalecen la corresponsabilidad, la transparencia y la confianza comunitaria.
          .col-lg-5.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            figure
              img(src='@/assets/curso/temas/tema2/img25.jpg', alt='Imagen decorativa')
        .row.justify-content-center.p-4
          .col-lg-7.order-lg-1.order-2
            h4 Enfoque diferencial
            ul.lista-ul.mb-0(data-aos="fade-down")
              li
                i.lista-ul__vineta
                p.mb-0 Permite que las intervenciones se ajusten a las características de grupos como mujeres, niños, personas mayores, población LGBTIQ+, grupos étnicos, víctimas del conflicto armado y personas con discapacidad.
              li
                i.lista-ul__vineta
                p.mb-0 La Política de Participación Social en Salud (Resolución 2063 de 2017) orienta acciones para reconocer desigualdades históricas y responder a necesidades particulares.
              li.mb-0
                i.lista-ul__vineta
                p.mb-0 En el caso de población migrante, este enfoque facilita la adaptación cultural, la comunicación intercultural y la valoración de trayectorias migratorias diversas.
          .col-lg-5.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            figure
              img(src='@/assets/curso/temas/tema2/img26.jpg', alt='Imagen decorativa')
        .row.justify-content-center.p-4
          .col-lg-7.order-lg-1.order-2
            h4 Derechos, interculturalidad y participación
            ul.lista-ul.mb-0(data-aos="fade-down")
              li
                i.lista-ul__vineta
                p.mb-0 Los enfoques de derechos e interculturalidad garantizan una atención digna, respetuosa y alineada con estándares internacionales.
              li
                i.lista-ul__vineta
                p.mb-0 La ACNUR (2023) destaca que los procesos participativos permiten visibilizar riesgos, identificar barreras de acceso y priorizar acciones con base en experiencias reales.
              li.mb-0
                i.lista-ul__vineta
                p.mb-0 La inclusión de líderes migrantes, organizaciones comunitarias y actores territoriales contribuye a fortalecer capacidades locales y a consolidar intervenciones más pertinentes, sostenibles y coherentes con la realidad sociocultural.
          .col-lg-5.col-10.order-lg-2.order-1.mb-lg-0.mb-4
            figure
              img(src='@/assets/curso/temas/tema2/img27.jpg', alt='Imagen decorativa')
    .row.justify-content-center.mb-0
      .col-lg-10.col-12
        p.mb-0(data-aos="fade-down") En conjunto, la participación social y los enfoques diferenciales consolidan una respuesta más humana, coherente y contextualizada frente a los retos de la movilidad humana. Estos elementos no solo fortalecen la articulación entre instituciones y comunidades, sino que también aseguran que las acciones en salud se construyan desde la diversidad, la corresponsabilidad y el respeto por las trayectorias de vida de las personas migrantes, retornadas y de acogida. De esta manera, se promueven intervenciones más inclusivas, sostenibles y centradas en las necesidades reales de los territorios.


</template>

<script>
export default {
  name: 'Tema2',
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
