# HU-A6.1: Carga del día como suma de la carga de tolvas

| Campo | Valor |
|---|---|
| **Épica / Actividad** | A6 – Cálculo de la carga diaria y la ley del blending |
| **Priorización** | WSJF (ranking: A4, A3, A6) |
| **Estado** | Borrador |

## Historia de usuario

**Como** planeador de mina,

**quiero** que el sistema sume lo que se carga a cada tolva desde cada pila y entregue la carga total del día,

**para** saber cuántas toneladas se enviaron a planta y de qué pilas provienen, sin consolidación manual.

## Criterios de aceptación

1. Carga de tolva = suma de toneladas enviadas desde cada pila a esa tolva.
2. Carga del día = suma de las cargas de todas las tolvas.
3. Se muestra el detalle por tolva y por pila de origen.
4. No se puede cargar a una tolva más tonelaje del que tiene disponible la pila.

## Dependencias

- HU-A4.1 (tonelaje acumulado de la pila, base para el tonelaje disponible).

## Notas

- _Pendiente: definir si el tonelaje disponible descuenta lo ya cargado en días anteriores._
