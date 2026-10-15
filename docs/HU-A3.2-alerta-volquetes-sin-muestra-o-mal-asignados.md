# HU-A3.2: Alerta de volquetes sin muestra o mal asignados

| Campo | Valor |
|---|---|
| **Épica / Actividad** | A3 – Registro de muestras por volquete |
| **Priorización** | WSJF (ranking: A4, A3, A6) |
| **Estado** | Borrador |

## Historia de usuario

**Como** jefe de control de calidad,

**quiero** ver los volquetes pendientes de muestra y poder corregir asignaciones erróneas con registro de cambios,

**para** evitar que se calcule la ley de una pila con datos incompletos o mal atribuidos.

## Criterios de aceptación

1. Lista de volquetes sin muestra por pila y por turno, con su antigüedad.
2. Al corregir la pila asignada a un volquete, se conserva quién cambió qué y cuándo.
3. Una pila con volquetes sin muestra no puede cerrarse sin una justificación.

## Dependencias

- HU-A3.1 (registro de volquete y su muestra).
- HU-A4.2 (cierre de pila).

## Notas

- _Pendiente: definir los turnos y el umbral de antigüedad a partir del cual se resalta un volquete pendiente._
