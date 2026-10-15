# HU-A4.1: Ley de la pila calculada automáticamente

| Campo | Valor |
|---|---|
| **Épica / Actividad** | A4 – Cálculo de ley ponderada por pila |
| **Priorización** | WSJF (ranking: A4, A3, A6) |
| **Estado** | Borrador |

## Historia de usuario

**Como** geólogo de control de calidad,

**quiero** que el sistema calcule la ley de cada pila como el promedio ponderado de las muestras de sus volquetes,

**para** conocer la ley real del mineral sin cálculos manuales en Excel y reducir errores que afectan la recuperación en planta.

## Criterios de aceptación

1. Ley de pila = Σ(ley de muestra × tonelaje del volquete) ÷ Σ tonelaje de volquetes con muestra.
2. El cálculo se actualiza cada vez que se registra o corrige una muestra de esa pila.
3. Se muestran el tonelaje acumulado, el número de volquetes y el número de muestras de la pila.
4. Los volquetes sin muestra no entran en el cálculo y se informan aparte.

## Supuestos a validar

- El "ponderado" de las muestras usa el **tonelaje de cada volquete como peso**. Si se usa otro criterio, deben ajustarse los criterios de aceptación de esta HU y de HU-A6.x.

## Dependencias

- HU-A3.1 (registro de volquete y su muestra): provee los datos de entrada.

## Notas
 
- _Pendiente: definir precisión decimal de la ley y unidad (p. ej. g/t, %)._
