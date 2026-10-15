# HU-A6.2: Ley esperada del blending diario

| Campo | Valor |
|---|---|
| **Épica / Actividad** | A6 – Cálculo de la carga diaria y la ley del blending |
| **Priorización** | WSJF (ranking: A4, A3, A6) |
| **Estado** | Borrador |

## Historia de usuario

**Como** superintendente de operaciones,

**quiero** ver la ley ponderada del blending de cada tolva y del día completo, a partir de la ley de las pilas que la componen,

**para** anticipar la ley que recibirá planta y ajustar la mezcla antes de cargar, en lugar de descubrir la desviación después.

## Criterios de aceptación

1. Ley de tolva = Σ(ley de pila × toneladas aportadas) ÷ Σ toneladas de la tolva.
2. Ley del día = Σ(ley de tolva × toneladas de tolva) ÷ Σ toneladas del día.
3. Si se usa una pila abierta (ley aún provisional), el sistema lo marca visiblemente.
4. Se alerta cuando la ley de una tolva o del día sale del rango objetivo definido por planta.

## Supuestos a validar

- La ponderación usa toneladas como peso (ver HU-A4.1).

## Dependencias

- HU-A4.1 y HU-A4.2 (ley y estado de la pila).
- HU-A6.1 (toneladas por tolva y pila de origen).

## Notas

- _Pendiente: definir quién configura el rango objetivo de ley y si varía por tolva o es único para el día._
