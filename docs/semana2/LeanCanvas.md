# Lean Canvas – NutriTrust

> **Borrador** propuesto por Santiago Mesa en la rama `santiago` para revisión del equipo. Integra el Lean Canvas del Product Blueprint y la versión de Yuen Fey Alvarez (rama `propuesta-yuen-alvarez`).

![Lean Canvas de NutriTrust](img/LeanCanvas.svg)

---

## Versión en texto

| Bloque | Contenido |
|---|---|
| **1. Problema** | Los datos nutricionales están dispersos en etiquetas, tablas oficiales y PDFs de laboratorio, sin forma de verificar su origen. Al actualizarse las tablas oficiales (TCAC) se excluyen alimentos y se rompe el historial. Las correcciones y los cambios de formulación no dejan un rastro auditable. |
| **Alternativas actuales** | Hojas de cálculo, PDFs institucionales, valores teóricos asumidos y auditorías manuales. |
| **2. Segmentos de clientes** | **Usuarios del MVP:** nutricionistas clínicos, investigadores y planificadores de servicios de alimentación. **Actores que alimentan la red:** laboratorios, colegios de nutricionistas y reguladores (INVIMA). |
| **Adoptantes tempranos** | Investigadores y nutricionistas que hoy calculan a mano y necesitan citar la fuente del dato. |
| **3. Propuesta de valor única** | El dato nutricional que cualquiera puede verificar: quién lo midió, quién lo validó y cómo cambió. |
| **Concepto de alto nivel** | Una "historia clínica" para cada alimento. |
| **4. Solución** | Registro de análisis firmado por laboratorios acreditados. Validación por quórum de expertos antes de oficializar un dato. Historial versionado y consulta pública del origen del dato. |
| **5. Canales** | Colegios y asociaciones de nutricionistas, redes de investigación y universidades, laboratorios bromatológicos acreditados, organizaciones de ayuda humanitaria y, en una fase posterior, código QR en empaques. |
| **6. Flujo de ingresos** | **Fase 1:** acceso gratuito para profesionales y ayuda humanitaria, financiado con convocatorias del ecosistema Stellar. **Fase 2:** suscripción para laboratorios y fabricantes que certifican datos; API de pago para food service. **Fase 3:** licencias institucionales para reguladores y universidades. |
| **7. Estructura de costos** | Desarrollo de contratos Soroban y de la plataforma web, tarifas de la red Stellar (fracciones de centavo por transacción), almacenamiento off-chain, auditoría de seguridad y cumplimiento de Habeas Data, y acompañamiento a laboratorios para sumarse a la red. |
| **8. Métricas clave** | Datos validados por mes, expertos y laboratorios activos en el quórum, tiempo para verificar un dato (de días a minutos) y consultas de verificación por mes. |
| **9. Ventaja especial** | La red de laboratorios y expertos validadores, y el historial acumulado: la tecnología se copia, la red y el historial no. Equipo que une nutrición clínica e ingeniería. |

---

## Qué cambia frente a las versiones anteriores

- **Formato:** la plantilla pide el Lean Canvas como enlace a un lienzo de una página. Este archivo trae el lienzo como imagen, en la distribución clásica de nueve bloques, y una versión en texto.
- **Un bloque por casilla:** en la versión de Yuen, las métricas aparecían dentro de Solución y los canales dentro de Ventaja especial. Aquí cada bloque tiene su casilla.
- **Segmento más enfocado:** la versión del Blueprint incluía a todos los actores como clientes. Aquí se separan los usuarios del MVP, los actores que alimentan la red y los adoptantes tempranos.
- **Validación por quórum:** se toma de la versión de Yuen, porque es lo que diferencia a NutriTrust de una base de datos tradicional.
- **Ingresos por fases:** se mantienen las fases de Yuen, pero la tercera se limita a licencias institucionales para que sea creíble a corto plazo.
