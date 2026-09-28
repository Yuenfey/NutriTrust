# Propuesta individual

**Nombre:** Juliana Lugo

**Usuario de GitHub:** julilugo09

---

## El problema

> El problema en una sola frase, sin mencionar blockchain.

Al finalizar un contrato de alquiler de vivienda, los inquilinos sufren demoras injustificadas, deducciones arbitrarias o la pérdida total de su dinero de depósito de garantía debido a disputas subjetivas sobre el estado del inmueble y a que el arrendador retiene los fondos unilateralmente en su cuenta personal.

---

## ¿Quién lo sufre?

> Quién tiene el problema y en qué situación lo vive.

Lo sufren principalmente jóvenes profesionales, familias y estudiantes que toman en arriendo habitaciones o inmuebles residenciales. La situación se vive al momento de entregar el inmueble: el inquilino necesita con urgencia ese dinero (que usualmente equivale a uno o dos cánones de arrendamiento) para pagar el depósito del nuevo lugar al que se muda, pero queda a merced de la voluntad del propietario. Cualquier desgaste natural o daño menor preexistente se convierte en motivo para retener el dinero semanas o meses, o para cobrar arreglos inflados sin sustento claro.

---

## ¿Cómo se resuelve hoy y qué cuesta?

> Cómo lo resuelven hoy las personas afectadas y qué les cuesta en dinero, tiempo o esfuerzo.

Hoy la resolución depende de la buena fe del arrendador:
- **En dinero:** Si el arrendador se niega a devolver el depósito o descuenta valores exagerados por reparaciones cosméticas, el inquilino suele perder entre $500.000 y más de $2.000.000 COP, dinero con el que contaba para su siguiente vivienda.
- **En tiempo y esfuerzo:** Se intercambian decenas de mensajes por WhatsApp, correos y fotos viejas del día de la mudanza para intentar demostrar qué daños ya estaban. Si la vía del diálogo fracasa, acudir a centros de conciliación o casas de justicia toma semanas o meses, por lo que la gran mayoría de inquilinos termina resignándose a la pérdida para evitar el desgaste legal.

---

## ¿Por qué creo que blockchain podría aportar?

> Criterios de la Sesión 1: partes que no confían entre sí comparten un registro, histórico inalterable, o eliminar un intermediario que concentra la confianza.

Considero que este problema surge de una asimetría de poder: **una de las partes concentra unilateralmente la custodia del dinero y no existe un registro inalterable compartido sobre las condiciones iniciales del inmueble**.

Blockchain podría aportar bajo los criterios de la Sesión 1 de la siguiente manera:
1. **Eliminar el custodio unilateral mediante un escrow programable:** El depósito no reposaría en la cuenta bancaria del arrendador ni del inquilino, sino en un contrato de custodia (escrow) donde los fondos quedan bloqueados y solo pueden liberarse hacia el inquilino o hacia el propietario con la firma digital de ambas partes (esquema multifirma).
2. **Histórico inalterable de evidencia:** Al inicio del contrato, el acta de entrega con el inventario detallado y los hashes criptográficos de las fotografías y videos del estado del inmueble quedan registrados en un libro inmutable. De esta manera, ninguna de las dos partes puede alterar o desconocer el estado en que se recibió la propiedad al momento de la liquidación final.
