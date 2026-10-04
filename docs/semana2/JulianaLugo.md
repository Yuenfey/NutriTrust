# Historias de usuario individuales

**Nombre:** Juliana Lugo  
**Usuario de GitHub:** Julilugo09  
**Rol:** Full Stack Developer  
**Proyecto:** NutriTrust  

---

## Mis historias de usuario

> Entre 5 y 7 historias en formato "como [rol] quiero [acción] para [beneficio]", pensadas desde distintos roles o necesidades del producto que el equipo está diseñando.

1. **Historia 1 (Desarrollador / Integrador de software de salud):**  
   Como **desarrollador de aplicaciones de nutrición**, quiero **acceder a datos bromatológicos estandarizados y auditables mediante un canal de consulta unificado**, para **integrar información nutricional verificada en mis herramientas clínicas sin tener que consolidar múltiples fuentes dispersas**.

2. **Historia 2 (Analista de laboratorio):**  
   Como **analista de laboratorio de alimentos**, quiero **adjuntar la metodología analítica y los parámetros de ensayo a cada resultado que registro**, para **que los profesionales puedan auditar el rigor técnico con el que se obtuvo el dato bromatológico**.

3. **Historia 3 (Nutricionista dietista):**  
   Como **nutricionista dietista**, quiero **consultar la fecha de última validación y el estado de aprobación de los nutrientes de un alimento**, para **diseñar dietas terapéuticas basadas en información vigente y confiable**.

4. **Historia 4 (Validador técnico / Quórum científico):**  
   Como **validador técnico de alimentos**, quiero **revisar las propuestas de nuevos análisis bromatológicos pendientes de aprobación**, para **emitir mi voto técnico antes de que el valor sea reconocido como oficial**.

5. **Historia 5 (Inspector de regulación):**  
   Como **inspector de regulación alimentaria**, quiero **visualizar el historial cronológico y las discrepancias registradas de un producto**, para **verificar el cumplimiento normativo en auditorías sanitarias o controversias entre fabricantes**.

6. **Historia 6 (Planificador institucional):**  
   Como **planificador de compras para programas de alimentación pública**, quiero **comparar los aportes nutricionales certificados entre diferentes proveedores de un insumo**, para **seleccionar alimentos que garanticen el requerimiento nutricional de la población atendida al mejor costo**.

---

## La más importante y por qué

> Organiza las historias de mayor a menor importancia: en la primera fila va la más importante. En cada fila indica el número de la historia y por qué la ubicaste en esa posición.

| Orden de importancia | Historia # | Por qué |
| :---: | :---: | --- |
| 1 (la más importante) | 2 | Es la base de toda la confianza del sistema. Si el laboratorio no registra el dato con su metodología analítica y parámetros de respaldo, ningún validador puede auditarlo, ningún desarrollador puede consumirlo con certeza y la información carecería de valor probatorio. |
| 2 | 4 | La validación técnica multipartita es el mecanismo que rompe los monopolios institucionales y el dogma oficial. Permite que el dato pase de ser una simple declaración privada a un estándar científico consensuado. |
| 3 | 1 | Representa la interfaz de valor y escalabilidad de NutriTrust. Desde mi rol de desarrolladora, permitir que plataformas clínicas y sistemas hospitalarios consuman datos estandarizados es lo que convierte el registro en una solución práctica de impacto masivo. |
| 4 | 3 | Resuelve el problema diario del usuario clínico (nutricionistas), permitiéndole dejar de basar prescripciones en PDFs desactualizados o incompletos. |
| 5 | 5 | Es indispensable para la transparencia institucional y la resolución de litigios sanitarios, pero depende funcionalmente de que ya existan registros inmutables y trazables en el sistema. |
| 6 (la menos importante) | 6 | Aporta un gran impacto socioeconómico en compras públicas, pero constituye un caso de uso derivado que se apoya en la madurez previa del catálogo y la verificación técnica. |

---

## Reflexión sobre mi aporte

Como Full Stack Developer, formulé estas historias con foco en la interoperabilidad, la integridad de los datos de entrada y la experiencia de los consumidores de la información (tanto profesionales de la salud como aplicaciones tecnológicas). Ninguna historia menciona tecnologías específicas, respetando los criterios de la Sesión 3, y cubren el ciclo de vida del dato: desde su captura técnica en el laboratorio y su validación colegiada, hasta su consumo automatizado por software clínico y entidades regulatorias.
