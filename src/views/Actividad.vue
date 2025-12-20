<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(icono="far fa-question-circle" titulo="Actividad didáctica")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5
  
      #Actividad                
        <Actividad :cuestionario="cuestionario"/>
  
  </template>

<script>
export default {
  name: 'ActividadDidactica',
  data: () => ({
    cuestionario: {
      tema: 'tema_actividad_didactica',
      titulo: 'Cuestionario',
      introduccion:
        '<b>Objetivo</b>: Evaluar la comprensión de los participantes sobre los fundamentos de la acción intersectorial en salud y migración, los determinantes sociales, la coordinación sectorial e intersectorial, las capacidades territoriales, la participación social, y los lineamientos técnicos y operativos que orientan la atención en salud a la población migrante, retornada y de acogida.',
      barajarPreguntas: true,
      preguntas: [
        {
          id: 1,
          texto:
            'La articulación intersectorial fortalece la capacidad territorial para responder a las necesidades de la población migrante.',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Verdadero', esCorrecta: true },
            { id: 'b', texto: 'Falso', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión clara de los conceptos esenciales relacionados con la atención en salud a población migrante, la acción intersectorial, los determinantes sociales y los lineamientos técnicos que orientan la respuesta territorial.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 2,
          texto:
            'Las Mesas de Articulación Territorial en Salud (MATS) representan un mecanismo clave para la gestión articulada de la respuesta institucional frente a la movilidad humana.',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Verdadero', esCorrecta: true },
            { id: 'b', texto: 'Falso', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión clara de los conceptos esenciales relacionados con la atención en salud a población migrante, la acción intersectorial, los determinantes sociales y los lineamientos técnicos que orientan la respuesta territorial.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 3,
          texto:
            'Las intervenciones colectivas en salud pública no buscan transformar determinantes sociales en los territorios.',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Verdadero', esCorrecta: false },
            { id: 'b', texto: 'Falso', esCorrecta: true },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión clara de los conceptos esenciales relacionados con la atención en salud a población migrante, la acción intersectorial, los determinantes sociales y los lineamientos técnicos que orientan la respuesta territorial.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 4,
          texto:
            'La vigilancia centinela se aplica especialmente en zonas fronterizas o corredores migratorios.',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Verdadero', esCorrecta: true },
            { id: 'b', texto: 'Falso', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión clara de los conceptos esenciales relacionados con la atención en salud a población migrante, la acción intersectorial, los determinantes sociales y los lineamientos técnicos que orientan la respuesta territorial.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 5,
          texto:
            'Las situaciones de interés en salud pública no incluyen riesgos materno-perinatales.',
          imagen: require('@/assets/actividad/imagen5.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Verdadero', esCorrecta: false },
            { id: 'b', texto: 'Falso', esCorrecta: true },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión clara de los conceptos esenciales relacionados con la atención en salud a población migrante, la acción intersectorial, los determinantes sociales y los lineamientos técnicos que orientan la respuesta territorial.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },

        {
          id: 6,
          texto:
            'La atención de urgencias para población migrante depende de su situación migratoria.',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Verdadero', esCorrecta: false },
            { id: 'b', texto: 'Falso', esCorrecta: true },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión clara de los conceptos esenciales relacionados con la atención en salud a población migrante, la acción intersectorial, los determinantes sociales y los lineamientos técnicos que orientan la respuesta territorial.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 7,
          texto:
            'El enfoque diferencial orienta intervenciones ajustadas a edad, género y diversidad cultural.',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Verdadero', esCorrecta: true },
            { id: 'b', texto: 'Falso', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión clara de los conceptos esenciales relacionados con la atención en salud a población migrante, la acción intersectorial, los determinantes sociales y los lineamientos técnicos que orientan la respuesta territorial.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 8,
          texto:
            'La OPS señala que la desconfianza institucional puede afectar el acceso a servicios en migrantes.',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Verdadero', esCorrecta: true },
            { id: 'b', texto: 'Falso', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión clara de los conceptos esenciales relacionados con la atención en salud a población migrante, la acción intersectorial, los determinantes sociales y los lineamientos técnicos que orientan la respuesta territorial.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 9,
          texto:
            'Las rutas de atención en salud para migrantes y retornados no incluyen procesos de orientación inicial.',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Verdadero', esCorrecta: false },
            { id: 'b', texto: 'Falso', esCorrecta: true },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión clara de los conceptos esenciales relacionados con la atención en salud a población migrante, la acción intersectorial, los determinantes sociales y los lineamientos técnicos que orientan la respuesta territorial.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 10,
          texto:
            'Los protocolos, rutas y guías técnicas establecen los procedimientos necesarios para garantizar una atención oportuna, integral y coordinada en los territorios.',
          imagen: require('@/assets/actividad/imagen5.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Verdadero', esCorrecta: true },
            { id: 'b', texto: 'Falso', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión clara de los conceptos esenciales relacionados con la atención en salud a población migrante, la acción intersectorial, los determinantes sociales y los lineamientos técnicos que orientan la respuesta territorial.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },

        {
          id: 11,
          texto:
            'El sector ______ aporta atención básica, urgencias, promoción y prevención.',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Educación', esCorrecta: false },
            { id: 'b', texto: 'Salud', esCorrecta: true },
            { id: 'c', texto: 'Recreativo', esCorrecta: false },
            { id: 'd', texto: 'Industrial', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión clara de los conceptos esenciales relacionados con la atención en salud a población migrante, la acción intersectorial, los determinantes sociales y los lineamientos técnicos que orientan la respuesta territorial.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 12,
          texto:
            'Las ________ territoriales activan rutas de atención, remisión y seguimiento.',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Congregaciones', esCorrecta: false },
            { id: 'b', texto: 'Zonas', esCorrecta: false },
            { id: 'c', texto: 'Entidades', esCorrecta: true },
            { id: 'd', texto: 'Partes', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión clara de los conceptos esenciales relacionados con la atención en salud a población migrante, la acción intersectorial, los determinantes sociales y los lineamientos técnicos que orientan la respuesta territorial.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 13,
          texto: 'Ley Estatutaria 1751 de _______.',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: '2015', esCorrecta: true },
            { id: 'b', texto: '2025', esCorrecta: false },
            { id: 'c', texto: '2005', esCorrecta: false },
            { id: 'd', texto: '1995', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión clara de los conceptos esenciales relacionados con la atención en salud a población migrante, la acción intersectorial, los determinantes sociales y los lineamientos técnicos que orientan la respuesta territorial.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 14,
          texto:
            'La ausencia de sistemas de ________ interoperables dificulta el seguimiento de los casos y la continuidad de los procesos de atención.',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Electricidad', esCorrecta: false },
            { id: 'b', texto: 'Circulación', esCorrecta: false },
            { id: 'c', texto: 'Viales', esCorrecta: false },
            { id: 'd', texto: 'Información', esCorrecta: true },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión clara de los conceptos esenciales relacionados con la atención en salud a población migrante, la acción intersectorial, los determinantes sociales y los lineamientos técnicos que orientan la respuesta territorial.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 15,
          texto:
            'La generación de ______ de atención unificadas que facilitan la orientación y el acceso a los servicios.',
          imagen: require('@/assets/actividad/imagen5.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Rutas', esCorrecta: true },
            { id: 'b', texto: 'Sillas', esCorrecta: false },
            { id: 'c', texto: 'Vacunas', esCorrecta: false },
            { id: 'd', texto: 'Medicamentos', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión clara de los conceptos esenciales relacionados con la atención en salud a población migrante, la acción intersectorial, los determinantes sociales y los lineamientos técnicos que orientan la respuesta territorial.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },

        {
          id: 16,
          texto: '¿Qué significa la sigla MATS?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Medios Artísticos de Transformación y Seguridad',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Mesas de Articulación Territorial en Salud',
              esCorrecta: true,
            },
            { id: 'c', texto: 'Matemáticas', esCorrecta: false },
            { id: 'd', texto: 'No significa nada', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión clara de los conceptos esenciales relacionados con la atención en salud a población migrante, la acción intersectorial, los determinantes sociales y los lineamientos técnicos que orientan la respuesta territorial.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 17,
          texto: 'La participación social constituye un eje fundamental para:',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto:
                'Fortalecer la salud pública y la atención dirigida a población migrante, retornada y de acogida',
              esCorrecta: true,
            },
            {
              id: 'b',
              texto: 'Crear grupos aislados y sin compromiso',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'No aceptar a la población migrante',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Crear una orquesta sinfónica',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión clara de los conceptos esenciales relacionados con la atención en salud a población migrante, la acción intersectorial, los determinantes sociales y los lineamientos técnicos que orientan la respuesta territorial.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 18,
          texto:
            'Es considerada como una situación de interés en salud pública relacionada con migrantes:',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Trámite TTP', esCorrecta: false },
            { id: 'b', texto: 'Estrés postraumático', esCorrecta: true },
            { id: 'c', texto: 'Inscripción escolar', esCorrecta: false },
            { id: 'd', texto: 'Orientación jurídica', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión clara de los conceptos esenciales relacionados con la atención en salud a población migrante, la acción intersectorial, los determinantes sociales y los lineamientos técnicos que orientan la respuesta territorial.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 19,
          texto:
            'Uno de los elementos centrales es el conocimiento de la ruta de atención en salud para migrantes y retornados, la cual incluye:',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Inscripción a las escuelas deportivas',
              esCorrecta: false,
            },
            { id: 'b', texto: 'Reunión con la comunidad', esCorrecta: false },
            {
              id: 'c',
              texto:
                'Remisión y contrarreferencia según la necesidad clínica o psicosocial',
              esCorrecta: true,
            },
            { id: 'd', texto: 'Vinculación laboral', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión clara de los conceptos esenciales relacionados con la atención en salud a población migrante, la acción intersectorial, los determinantes sociales y los lineamientos técnicos que orientan la respuesta territorial.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 20,
          texto:
            '¿Qué sector es considerado como clave para la articulación territorial?',
          imagen: require('@/assets/actividad/imagen5.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Cultura', esCorrecta: false },
            { id: 'b', texto: 'Transporte', esCorrecta: false },
            { id: 'c', texto: 'Educación', esCorrecta: true },
            { id: 'd', texto: 'Deporte', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia una comprensión clara de los conceptos esenciales relacionados con la atención en salud a población migrante, la acción intersectorial, los determinantes sociales y los lineamientos técnicos que orientan la respuesta territorial.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
      ],
      mensaje_final_aprobado:
        'Ha superado la actividad y demuestra sólidos conocimientos sobre el componente formativo.',
      mensaje_final_reprobado:
        'No ha superado la actividad. Le recomendamos volver a revisar el componente formativo e intentar nuevamente la actividad didáctica.',
    },
  }),
}
</script>
