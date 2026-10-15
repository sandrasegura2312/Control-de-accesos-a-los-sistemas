# HU-A4.2: Trazabilidad y cierre de la ley de pila

| Campo | Valor |
|---|---|
| **Épica / Actividad** | A4 – Cálculo de ley ponderada por pila |
| **Priorización** | WSJF (ranking: A4, A3, A6) |
| **Estado** | Borrador |

## Historia de usuario

**Como** superintendente de planeamiento,

**quiero** ver qué muestras componen la ley de una pila y poder cerrarla cuando está completa,

**para** confiar en el dato que uso para decidir el blending y poder sustentarlo ante una auditoría.

## Criterios de aceptación

1. Desde la ley de la pila se puede ver el detalle: volquete, tonelaje, ley y hora de cada muestra.
2. Una pila cerrada queda bloqueada, y solo un rol autorizado puede reabrirla, dejando registro del motivo.
3. El sistema indica el estado de la pila: abierta, cerrada o con observaciones.

## Dependencias

- HU-A4.1 (ley de pila calculada automáticamente).
- HU-A3.2: una pila con volquetes sin muestra no puede cerrarse sin justificación.

## Notas

- _Pendiente: definir qué roles están autorizados a reabrir una pila._
- _Pendiente: definir qué condiciones generan el estado "con observaciones"._
