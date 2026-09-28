# Problem Brief

## Decisión del problema

### Problema elegido

> El problema ganador en una frase, sin mencionar blockchain, y quién lo propuso.

La información sobre la composición nutricional de los alimentos carece de estructura, y es difícil de verificar o rastrear en su historial de procedencia.

**Propuesto por:** Yuen Fey Alvarez Porras (seleccionado por consenso tras evaluar las propuestas individuales).

### Por qué elegimos este

> Qué inclinó al equipo por este problema frente a los demás, según los criterios de la Sesión 1.

El equipo eligió este problema porque presenta una necesidad clara de mantener información confiable entre múltiples actores que participan en la generación, validación y consumo de datos nutricionales. Instituciones de salud, laboratorios, productores de alimentos, organismos reguladores y consumidores necesitan acceder a información consistente y verificable, pero actualmente cada actor administra sus propios registros.

Además, los datos nutricionales tienen impacto directo en decisiones relacionadas con la salud pública, la investigación científica y la formulación de dietas especializadas. Por esta razón, resulta fundamental garantizar la integridad del historial de modificaciones y la trazabilidad de la información.
 
El problema cumple con los criterios analizados en la Sesión 1, especialmente la necesidad de compartir un registro común entre organizaciones que no confían plenamente entre sí y la importancia de conservar un historial inalterable de los datos registrados.

### Propuestas descartadas

> Cada propuesta considerada, quién la propuso y el motivo del descarte.

| Propuesta | Proponente | Motivo del descarte |
|------------|------------|---------------------|
| Sistema de custodia de pagos para trabajadores independientes y clientes mediante contratos inteligentes | Nicolás Alvarino Laguna | Aunque resuelve un problema real de confianza entre partes, el equipo consideró que existen múltiples soluciones centralizadas ampliamente adoptadas y que el problema nutricional ofrece un impacto social más amplio y una necesidad más evidente de trazabilidad histórica. |
| Registro compartido de gastos y reembolsos entre herederos durante una sucesión familiar (Legacy) | Santiago Mesa | Cumple los criterios de histórico inalterable y registro compartido, pero involucra a pocas partes (una familia) que en la mayoría de casos sí confían entre sí, y su alcance es más acotado que el del problema nutricional, que afecta a múltiples organizaciones independientes. |
| Custodia del depósito de garantía en contratos de arrendamiento para evitar retenciones y deducciones arbitrarias | Juliana Lugo | Elimina un intermediario que concentra la confianza, pero la disputa de fondo (el estado del inmueble al entregarlo) sigue dependiendo de una evaluación subjetiva fuera de la cadena, y el flujo se parece al de custodia de pagos ya considerado. |
| Verificación en tiempo real de la cartera que las fintechs asignan a sus fondeadores | Carlos Arturo Bermudez Rios | Presenta un caso sólido de partes que no confían entre sí, pero exige integrar sistemas financieros y datos sensibles de deudores, con una complejidad regulatoria alta para el alcance del programa. |

### Cómo tomamos la decisión

> Cómo llegó el equipo al acuerdo: votación, consenso tras debate u otro.

La decisión se tomó mediante una discusión grupal seguida de consenso. Cada integrante presentó su propuesta individual y se evaluó utilizando los criterios definidos durante la Sesión 1: existencia de múltiples actores independientes, necesidad de compartir información confiable, importancia de la inmutabilidad del historial y potencial eliminación de intermediarios de confianza.
 
Después de comparar las alternativas, el equipo concluyó que el problema relacionado con la trazabilidad de la información nutricional presentaba una justificación más sólida para el uso de tecnologías de registro distribuido y un mayor potencial de impacto social.

---

## Problem Brief

### Encabezado

> Nombre del proyecto y una frase que describa el problema. Extensión: breve.

### NutriTrust
 
Plataforma para garantizar la trazabilidad, autenticidad y verificabilidad de la información nutricional de los alimentos a lo largo de toda su cadena de generación y validación.

### Equipo y roles

> Integrantes con su usuario de GitHub, rol asumido por cada persona, responsable de las entregas y canal de coordinación interna. Extensión: breve.

| Integrante              | GitHub                | Rol                                 |
|-------------------------|-----------------------|-------------------------------------|
| Nicolás Alvarino Laguna | nicolasalvarino-l     | Analista de negocio y documentación |
| Yuen Fey Alvarez Porras | Yuenfey               | Investigación y validación          |
| Santiago Mesa           | mesas01               | Smart Contract Developer            |
| Juliana Lugo            | Julilugo09            | Full Stack Developer                |
| Carlos Bermudez Rios    | Cearjeyou             | Ingeniero                           |

**Responsable de entregables:** Nicolás Alvarino Laguna
 
**Canal de coordinación:** GitHub, Discord, Whatsapp y reuniones virtuales del equipo.

### Problema y evidencia

> Enunciado del problema en una frase, sin mencionar blockchain. Contexto, frecuencia y alcance. Evidencia mínima de que el problema existe: observación directa, experiencia propia, conversaciones o fuentes consultadas, con enlace o cita cuando aplique. Extensión: 150–300 palabras.

La información nutricional de los alimentos suele encontrarse distribuida entre múltiples fuentes con distintos niveles de calidad, actualización y validación. Como consecuencia, consumidores, profesionales de la salud, investigadores e instituciones enfrentan dificultades para comprobar si los datos publicados corresponden realmente al producto analizado y si han sido modificados posteriormente.
 
Actualmente, la información nutricional pasa por varios actores: fabricantes, laboratorios de análisis, organismos reguladores, distribuidores y sistemas de información nutricional. En muchos casos cada participante almacena los resultados en bases de datos independientes cuya relación es difícil de verificar. Esto genera duplicidad de registros, inconsistencias entre fuentes y problemas para identificar el origen de determinada información.
 
La evidencia del problema puede observarse en diferencias entre bases de datos nutricionales nacionales e internacionales, cambios en formulaciones de productos sin un mecanismo sencillo para rastrear versiones anteriores y dificultades que enfrentan investigadores para validar la procedencia de datos históricos utilizados en estudios científicos.
 
La situación impacta especialmente en productos destinados a personas con restricciones alimentarias, enfermedades metabólicas o necesidades dietéticas específicas, donde la precisión de la información puede influir directamente en decisiones relacionadas con la salud.

**Fuentes consultadas:**
- La FAO, a través de la red INFOODS, publicó guías específicas para verificar y armonizar datos de composición de alimentos, reconociendo que la calidad de los datos sigue siendo un problema en las tablas y bases publicadas ([FAO/INFOODS – Guidelines for Checking Food Composition Data](https://www.fao.org/fileadmin/templates/food_composition/documents/upload/Guidelines_data_checking.pdf); [Charrondière et al., *Food Chemistry*](https://www.sciencedirect.com/science/article/abs/pii/S0308814614017841)).
- En Colombia, la [Resolución 810 de 2021 del Ministerio de Salud](https://normograma.invima.gov.co/compilacion/docs/resolucion_minsaludps_0810_2021.htm) obliga a declarar la información nutricional de los alimentos envasados y busca prevenir prácticas que induzcan a engaño, lo que muestra que la veracidad de estos datos es una preocupación regulatoria.

### Usuario y actores

> Quién sufre el problema y qué necesita resolver. Cómo lo resuelve hoy y qué le cuesta en dinero, tiempo o esfuerzo. Demás actores que intervienen en el flujo, con el papel que cumple cada uno. Extensión: 150–300 palabras.

Los principales usuarios afectados son nutricionistas, consumidores, investigadores, instituciones de salud y organismos reguladores que necesitan acceder a información nutricional confiable y verificable.
 
Actualmente estos usuarios obtienen la información mediante etiquetas de productos, bases de datos públicas, publicaciones científicas o información suministrada por fabricantes. Sin embargo, cuando surge alguna discrepancia o necesitan verificar la procedencia de los datos, deben realizar procesos manuales de validación que consumen tiempo y recursos.
 
Los actores involucrados son:
 
1. Productores de alimentos, que generan los productos y reportan información nutricional.
2. Laboratorios de análisis, responsables de medir y certificar la composición nutricional.
3. Organismos reguladores, encargados de supervisar el cumplimiento normativo.
4. Distribuidores y minoristas, que comercializan los productos.
5. Instituciones de salud e investigación, que utilizan los datos para estudios y recomendaciones.
6. Consumidores finales, quienes consultan la información para tomar decisiones de compra.
 
El costo actual se refleja en procesos de auditoría más complejos, tiempo adicional dedicado a verificaciones manuales y pérdida de confianza cuando existen discrepancias entre distintas fuentes de información.

### Flujo actual de valor

> Recorrido paso a paso de cómo se mueve hoy el dinero, la información o el activo, desde el origen hasta el destino. Diagrama o secuencia numerada, con los intermediarios explícitos. Señalar si algún paso responde a una obligación normativa. Extensión: 150–300 palabras.

El flujo actual de información sigue generalmente los siguientes pasos:
 
1. Un productor desarrolla o modifica un producto alimenticio.
2. Se envían muestras a un laboratorio para analizar la composición nutricional.
3. El laboratorio genera un informe con los resultados obtenidos.
4. El fabricante incorpora la información en etiquetas y sistemas internos.
5. Los organismos reguladores verifican el cumplimiento de la normativa alimentaria vigente.
6. Distribuidores y minoristas comercializan el producto.
7. Los datos nutricionales son publicados en diversos portales, bases de datos o aplicaciones.
8. Consumidores, nutricionistas e investigadores consultan la información disponible.
 
Los intermediarios principales son los laboratorios, organismos reguladores y plataformas de publicación de datos.
 
Los procesos de análisis, certificación y etiquetado responden normalmente a obligaciones regulatorias relacionadas con seguridad alimentaria, transparencia de información al consumidor y cumplimiento de estándares nacionales e internacionales.
 
La información fluye entre múltiples sistemas independientes, generando dificultades para auditar la procedencia exacta de cada dato y verificar cuándo, por quién y bajo qué condiciones fue modificada.

### Fricciones identificadas

> Puntos concretos donde el flujo falla, se encarece o se demora. Cada fricción indica en qué paso ocurre, qué la causa y a quién afecta. Extensión: 150–300 palabras.

La primera fricción ocurre en los pasos 2 a 4, durante el intercambio de información entre fabricantes y laboratorios. Los resultados pueden almacenarse en diferentes sistemas, lo que dificulta mantener una única versión verificable de los datos.
 
La segunda fricción aparece en el paso 5, cuando organismos reguladores y entidades externas intentan auditar información histórica. Reconstruir el historial completo de modificaciones suele requerir consultar múltiples bases de datos y documentos.
 
La tercera fricción ocurre en los pasos 7 y 8 y afecta a investigadores y profesionales de la salud. La existencia de múltiples fuentes puede generar discrepancias que demandan verificaciones adicionales y retrasan procesos de investigación o toma de decisiones clínicas.
 
La cuarta fricción ocurre en el paso 8 e impacta directamente en consumidores. Cuando encuentran diferencias entre etiquetas, aplicaciones o bases de datos públicas, resulta difícil identificar cuál fuente contiene la información correcta.
 
Finalmente, en los pasos 3 y 5, los procesos de auditoría y validación generan costos operativos significativos para empresas e instituciones debido a la necesidad de conservar registros separados y coordinar revisiones periódicas entre múltiples organizaciones.

### Oportunidad e hipótesis

> Oportunidad priorizada entre las fricciones identificadas, con el motivo de la elección. Hipótesis inicial de por qué blockchain podría mejorar ese punto, expresada en términos de qué cambiaría para el usuario. Extensión: 150–300 palabras.

La oportunidad priorizada consiste en mejorar la trazabilidad y verificabilidad del historial de datos nutricionales desde su generación inicial hasta su utilización final por consumidores e instituciones.
 
Esta oportunidad fue seleccionada porque representa el origen de varias de las fricciones identificadas. Cuando todos los actores pueden consultar un historial confiable y compartido, disminuyen los costos de auditoría, aumentan los niveles de confianza y resulta más sencillo detectar modificaciones o inconsistencias.
 
La hipótesis inicial es que una solución basada en blockchain permitiría registrar cada análisis nutricional, actualización o certificación en un historial compartido e inalterable accesible para todos los participantes autorizados.
 
Para el usuario final esto significaría poder verificar el origen de la información nutricional, conocer cuándo fue actualizada y validar quién realizó cada modificación. Como consecuencia, aumentaría la transparencia y la confianza en los datos utilizados para tomar decisiones relacionadas con salud y alimentación. Un nutricionista, por ejemplo, podría confirmar en segundos qué laboratorio certificó el dato que usa para diseñar una dieta.

### Criterio de pertinencia

> Justificación de por qué el caso requiere un registro distribuido y no una base de datos tradicional o una integración entre sistemas existentes. Debe apoyarse en al menos uno de los criterios de la Sesión 1: varias partes que no confían entre sí necesitan compartir un mismo registro, el histórico no puede alterarse, o se elimina un intermediario que hoy concentra la confianza. Extensión: 150–300 palabras.

Este caso requiere un registro distribuido porque involucra múltiples organizaciones independientes que necesitan compartir información crítica sin depender completamente de una única entidad administradora.
 
Fabricantes, laboratorios, organismos reguladores e instituciones de salud poseen distintos intereses y responsabilidades. Cada uno necesita registrar información relevante y confiar en los datos suministrados por los demás actores. Una base de datos centralizada obligaría a depositar toda la confianza en una sola organización encargada de administrar el sistema.
 
Además, el historial de modificaciones constituye un elemento fundamental. Los análisis nutricionales pueden actualizarse como resultado de nuevas mediciones, cambios en formulaciones o revisiones regulatorias. Mantener evidencia verificable de cada cambio resulta esencial para auditorías y procesos de control.
 
La solución también se alinea con el criterio de histórico inalterable analizado durante la Sesión 1. Cualquier modificación debe conservar evidencia permanente de quién realizó el cambio, cuándo ocurrió y cuál era la información anterior.
 
Por estas razones, un registro distribuido ofrece ventajas significativas respecto de esquemas tradicionales basados únicamente en bases de datos aisladas o integraciones puntuales entre sistemas.

### Supuestos y riesgos

> Dos o tres supuestos que tendrían que ser ciertos para que la hipótesis funcione, y qué podría invalidarla. Extensión: 150–300 palabras.

El primer supuesto es que los laboratorios, fabricantes y organismos reguladores estarán dispuestos a participar en una red compartida y registrar sus actividades de manera consistente. Si los actores clave no participan, la trazabilidad quedaría incompleta.
 
El segundo supuesto es que la información registrada inicialmente será confiable. Aunque la tecnología puede proteger la integridad del historial, no garantiza que los datos introducidos sean correctos desde el origen.
 
El tercer supuesto es que los beneficios obtenidos en auditoría, transparencia y confianza compensarán los costos de adopción e integración tecnológica.
 
Entre los principales riesgos se encuentran la resistencia organizacional al cambio, posibles restricciones regulatorias relacionadas con la gestión de información alimentaria y la dificultad de establecer estándares comunes para el intercambio de datos entre instituciones.
 
Asimismo, si los procedimientos de validación previos al registro no son adecuados, podrían preservarse permanentemente datos incorrectos, reduciendo el valor de la solución propuesta.
