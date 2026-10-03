# Problem Brief

## Decisión del problema

### Problema elegido

> El problema ganador en una frase, sin mencionar blockchain, y quién lo propuso.

La información sobre la composición nutricional de los alimentos carece de estructura, y es difícil de verificar o rastrear en su historial de procedencia.

**Propuesto por:** Yuen Fey Alvarez Porras (seleccionado por consenso tras evaluar las propuestas individuales).

### Por qué elegimos este

> Qué inclinó al equipo por este problema frente a los demás, según los criterios de la Sesión 1.

El equipo eligió este problema por su inmenso potencial de escalabilidad y su impacto directo en la salud pública, los servicios de alimentación y el futuro de la nutrición de precisión (nutrigenómica). A diferencia de las propuestas descartadas, este reto requiere una infraestructura que conecte ecosistemas enteros y elimine los cuellos de botella de la información científica a gran escala.

Este problema cumple estrictamente con los criterios de la Sesión 1:

Registro compartido sin un dueño único: La industria, los investigadores y los gobiernos tienen intereses distintos. Al igual que en los sistemas de custodia (escrow), un registro distribuido permite que la validación de un alimento requiera el acuerdo de múltiples expertos (quórum), evitando que los datos nutricionales sean manipulados por silos institucionales o intereses comerciales privados.

Histórico inalterable para auditorías confiables: Para automatizar cálculos críticos, o cruzar el perfil de un alimento con bases de datos metabólicas y genéticas, los profesionales necesitan verificar el linaje de la evidencia. Un registro inmutable garantiza que la procedencia del dato quede guardada permanentemente, previniendo el fraude científico e impidiendo que el emisor original borre u oculte el pasado.

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
 
Infraestructura descentralizada para garantizar la trazabilidad, homologación y verificabilidad de los datos de composición de alimentos.

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

La información sobre la composición nutricional de los alimentos carece de estructura unificada, y resulta muy difícil verificar, homologar o rastrear su historial de procedencia.

Contexto y alcance: Si bien la información nutricional existe y cada gobierno la consolida bajo sus propios criterios, estos estándares son locales, aislados y estructuralmente inestables. Esta fragmentación genera una pérdida constante de información histórica. En la práctica clínica, la falta de una base continua convierte cualquier cálculo a escala en un proceso manual que consume enormes cantidades de tiempo. Esto obstaculiza casos de uso críticos inmediatos (como planes de compra en emergencias humanitarias) y frena el avance científico a largo plazo: es imposible cruzar modelos algorítmicos predictivos o genéticos con bases de datos de bioactivos (el Foodome) si la información de origen del alimento no es estandarizada y confiable.

Evidencia:

Observación directa (Inestabilidad institucional): La pérdida de datos es evidente al comparar documentos oficiales. Por ejemplo, la Tabla de Composición de Alimentos Colombianos (TCAC) de 2015 contaba con 967 alimentos, mientras que la versión de 2018 se redujo a 773. Cientos de alimentos locales y variaciones de formato quedaron excluidos sin un repositorio histórico auditable.

Fuentes consultadas: La FAO, a través de la red INFOODS, reconoce formalmente en sus guías (Guidelines for Checking Food Composition Data) que la calidad, consistencia y los vacíos metodológicos en las tablas nacionales publicadas siguen siendo un problema crítico para la interoperabilidad científica y la prescripción.

**Fuentes consultadas:**
- La FAO, a través de la red INFOODS, publicó guías específicas para verificar y armonizar datos de composición de alimentos, reconociendo que la calidad de los datos sigue siendo un problema en las tablas y bases publicadas ([FAO/INFOODS – Guidelines for Checking Food Composition Data](https://www.fao.org/fileadmin/templates/food_composition/documents/upload/Guidelines_data_checking.pdf); [Charrondière et al., *Food Chemistry*](https://www.sciencedirect.com/science/article/abs/pii/S0308814614017841)).
- En Colombia, la [Resolución 810 de 2021 del Ministerio de Salud](https://normograma.invima.gov.co/compilacion/docs/resolucion_minsaludps_0810_2021.htm) obliga a declarar la información nutricional de los alimentos envasados y busca prevenir prácticas que induzcan a engaño, lo que muestra que la veracidad de estos datos es una preocupación regulatoria.

### Usuario y actores

> Quién sufre el problema y qué necesita resolver. Cómo lo resuelve hoy y qué le cuesta en dinero, tiempo o esfuerzo. Demás actores que intervienen en el flujo, con el papel que cumple cada uno. Extensión: 150–300 palabras.

Los Usuarios principales (quienes sufren el problema directamente) son los profesionales de nutrición, investigadores clínicos, planificadores de servicios de alimentación a colectividades y organizaciones de ayuda humanitaria. Ellos necesitan acceder a datos exactos, auditables y estandarizados para calcular requerimientos poblacionales, diseñar minutas a gran escala o validar mecanismos metabólicos predictivos en investigación.

Cómo lo resuelven hoy y qué les cuesta:
Actualmente resuelven esta necesidad de forma operativa y fragmentada. Extraen información de PDFs estáticos o desactualizados, transcriben datos manualmente a hojas de cálculo, los cruzan con bases extranjeras y ante discrepancias o falta de alimentos locales, asumen valores teóricos. Esto les cuesta horas de desgaste. Además, implica un altísimo costo en riesgo social, científico y financiero: un cálculo derivado de un dato obsoleto puede subestimar las necesidades de poblaciones vulnerables, encarecer drásticamente planes de compra en emergencias institucionales, o invalidar estudios clínicos al basarse en evidencia fragmentada.

Los Actores (quienes intervienen en el flujo, pero no asumen esta fricción operativa diaria) son:

Fuentes oficiales e institucionales (ej. ICBF, Ministerios): Custodios actuales de la información que financian y publican esporádicamente las tablas de referencia.

Laboratorios bromatológicos: Entidades que ejecutan los análisis químicos rigurosos (ej. métodos AOAC) y generan los datos científicos crudos.

Comunidad profesional (Quórum de validación): Colegios de nutricionistas y académicos que poseen el criterio técnico para resolver equivalencias culturales y auditar discrepancias.

Sector comercial e Industria: Actores que en el futuro consumirán esta infraestructura para certificar el perfil nutricional verificable de sus productos como valor agregado.

### Flujo actual de valor

> Recorrido paso a paso de cómo se mueve hoy el dinero, la información o el activo, desde el origen hasta el destino. Diagrama o secuencia numerada, con los intermediarios explícitos. Señalar si algún paso responde a una obligación normativa. Extensión: 150–300 palabras.

El activo que fluye en este ecosistema es la información científica (el dato bromatológico). El recorrido actual de este activo es el siguiente:

Análisis de origen: Una entidad oficial o laboratorio realiza un análisis bromatológico bajo financiamiento público o independiente.

Publicación centralizada (Obligación Normativa): Los resultados pasan a un intermediario gubernamental (ej. Ministerios, ICBF) que, cumpliendo con la obligación normativa de mantener guías de salud pública, los compila en documentos estáticos (informes técnicos, PDFs o tablas impresas como la TCAC).

Estancamiento institucional: La tabla de referencia queda congelada en esa versión durante años. El dato publicado se asume como "dogma oficial" por diseño, sin importar si surgen métodos analíticos más precisos en el intermedio.

Transcripción y consumo: Los Usuarios (profesionales de salud e investigadores) extraen manualmente esta información, transcribiéndola a hojas de cálculo propias (Excel) o software aislado para poder realizar cálculos dietarios o clínicos.

Silenciamiento de la controversia: Cuando surge una discrepancia científica (ej. un contraanálisis de una universidad independiente o un cambio en la nomenclatura local), no existe un canal unificado ni un consenso para actualizar el registro, obligando al usuario a elegir un valor de forma empírica y rompiendo la trazabilidad de la evidencia.

### Fricciones identificadas

> Puntos concretos donde el flujo falla, se encarece o se demora. Cada fricción indica en qué paso ocurre, qué la causa y a quién afecta. Extensión: 150–300 palabras.

Fricción de procedencia (Pasos 1 y 2): Ocurre en la transición del análisis de laboratorio a la publicación gubernamental centralizada. Causa: El uso de formatos cerrados e institucionales (PDFs o impresos) omite la metodología analítica cruda (ej. métodos AOAC). Afecta a: Investigadores clínicos y nutricionistas, quienes no pueden auditar con qué rigor científico se obtuvo el valor reportado.

Fricción de centralización y obsolescencia (Paso 3): Ocurre durante el estancamiento institucional del dato. Causa: Una sola entidad estatal concentra el poder, el presupuesto y la confianza para actualizar la tabla de referencia, provocando desfases de más de una década. Afecta a: Planificadores de salud pública y profesionales, obligados a realizar cálculos con perfiles bromatológicos que ya no reflejan la biodiversidad local o las técnicas agrícolas actuales.

Fricción de desgaste operativo (Paso 4): Ocurre en el momento del consumo de la información. Causa: La ausencia de una infraestructura interoperable obliga a realizar procesos manuales de extracción, transcripción a hojas de cálculo y cruce de variables. Afecta a: Profesionales y organizaciones de ayuda humanitaria, encareciendo y retrasando el diseño urgente de minutas, cálculos poblacionales o planes de compra en emergencias.

Fricción en la resolución de controversias (Paso 5): Ocurre cuando un laboratorio independiente genera evidencia que contradice el dogma oficial. Causa: No existe un canal neutral ni un mecanismo de consenso para que la comunidad evalúe, vote y actualice el registro. Afecta a: Toda la comunidad científica, obligando a los investigadores a asumir valores teóricos y generando el riesgo de invalidar estudios clínicos enteros por basarse en datos sin trazabilidad consensuada.

### Oportunidad e hipótesis

> Oportunidad priorizada entre las fricciones identificadas, con el motivo de la elección. Hipótesis inicial de por qué blockchain podría mejorar ese punto, expresada en términos de qué cambiaría para el usuario. Extensión: 150–300 palabras.

La oportunidad priorizada es resolver la fricción en la resolución de controversias y la obsolescencia del dato (Pasos 3 y 5).

Elegimos esta oportunidad porque representa el cuello de botella estructural del sistema: si la información base carece de un historial auditable o está desactualizada, todos los esfuerzos posteriores (desde estudios clínicos hasta la planificación de minutas para emergencias humanitarias) heredan ese error. Al descentralizar la validación, eliminamos la dependencia de una única entidad estatal que congela los datos durante décadas.

Hipótesis inicial:
Creemos que implementar un registro distribuido gobernado por Contratos Inteligentes (Soroban) permitirá crear una capa de consenso científico neutral. En este sistema, cualquier actualización, homologación cultural o resolución de una discrepancia analítica quedará registrada en un historial inalterable.

Para el Usuario (el profesional de nutrición o investigador), esto significaría dejar de confiar a ciegas en un PDF estático. Al consultar la composición de un alimento, el usuario vería el linaje exacto de la evidencia. El sistema le garantizaría que un dato nuevo o discrepante solo fue aprobado porque el contrato inteligente verificó la firma digital de un Quórum técnico (un grupo mínimo de profesionales acreditados). Como resultado, el nutricionista podría confirmar en segundos qué laboratorio generó el dato y con qué rigor metodológico, aumentando drásticamente la seguridad y agilidad al tomar decisiones críticas de salud pública o investigación clínica.

### Criterio de pertinencia

> Justificación de por qué el caso requiere un registro distribuido y no una base de datos tradicional o una integración entre sistemas existentes. Debe apoyarse en al menos uno de los criterios de la Sesión 1: varias partes que no confían entre sí necesitan compartir un mismo registro, el histórico no puede alterarse, o se elimina un intermediario que hoy concentra la confianza. Extensión: 150–300 palabras.

Este caso exige un registro distribuido (blockchain) y no una base de datos centralizada porque cumple estrictamente con los criterios técnicos analizados en la Sesión 1:

Múltiples partes sin confianza plena y eliminación del intermediario central: Laboratorios independientes, instituciones académicas y entidades gubernamentales tienen metodologías e intereses distintos. Una base de datos tradicional obliga a depositar toda la confianza en un único custodio estatal (ej. un ministerio o el ICBF), quien concentra el poder de decidir qué datos se publican y cuáles se descartan de forma unilateral. Un registro distribuido elimina este intermediario, permitiendo un ecosistema neutral donde la validez del dato depende del consenso de expertos.

Histórico inalterable para la evidencia científica: La ciencia exige conservar el linaje exacto de la información. Si un laboratorio independiente refuta un dato oficial, ambas versiones deben coexistir. El registro inmutable garantiza que ninguna entidad pueda sobreescribir, maquillar u ocultar el historial de discrepancias metodológicas.

Arquitectura pertinente:
Siguiendo los principios de diseño de redes distribuidas, este proyecto no utilizará la blockchain como base de datos. Los extensos metadatos taxonómicos de los alimentos vivirán en una base de datos tradicional. La red blockchain se utilizará exclusivamente para registrar lo que las partes necesitan verificar: los hashes criptográficos de los reportes bromatológicos de laboratorio y las firmas digitales del Quórum de expertos que avalan la información.

### Supuestos y riesgos

> Dos o tres supuestos que tendrían que ser ciertos para que la hipótesis funcione, y qué podría invalidarla. Extensión: 150–300 palabras.

Supuestos:

Viabilidad de adopción inicial: Suponemos que es posible extraer y estructurar los datos fácticos de fuentes oficiales abiertas (como la TCAC o bases de la FAO) para inicializar la base de datos, sin requerir que los ministerios integren sus sistemas directamente desde el día uno.

Incentivos de validación: Suponemos que las instituciones académicas, laboratorios independientes y profesionales estarán dispuestos a participar como validadores técnicos (Quórum) motivados por el rigor científico, el prestigio académico y la necesidad gremial de contar con una herramienta confiable para sus propios cálculos.

Riesgos que podrían invalidar la hipótesis:

El "Problema del Oráculo" (Basura entra, basura queda): La tecnología blockchain garantiza que el registro no se altere, pero no puede garantizar que el análisis de laboratorio original sea metodológicamente impecable. Si las reglas del Contrato Inteligente son débiles y el Quórum falla en su revisión, se preservarán permanentemente datos científicos incorrectos, destruyendo la confianza en el sistema.

Riesgo legal por inmutabilidad de datos personales: Como rige el principio de que en redes públicas "nada se borra", existe el riesgo de violar normativas de privacidad (Habeas Data) si se exponen los datos de los profesionales que auditan la información. Para evitar que esto invalide el proyecto, el diseño debe garantizar que los datos personales residan en bases de datos tradicionales, enviando a la blockchain únicamente identificadores o firmas criptográficas seudonimizadas para verificar las autorías.
