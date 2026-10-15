# HU-A3.1: Registro de volquete y su muestra

| Campo | Valor |
|---|---|
| **Épica / Actividad** | A3 – Registro de muestras por volquete |
| **Priorización** | WSJF (ranking: A4, A3, A6) |
| **Estado** | Borrador |

## Historia de usuario

**Como** técnico de muestreo,

**quiero** registrar cada volquete que llega y asociarlo a la pila (polígono) de su labor de origen,

**para** garantizar que toda la carga esté muestreada y que cada muestra cuente para la pila correcta.

## Criterios de aceptación

1. Por cada volquete se registra: pila/polígono, labor, placa, tonelaje, fecha y hora, y código de muestra.
2. Se genera una sola muestra por volquete y no se permite duplicar el código de muestra.
3. Solo se puede asignar el volquete a pilas existentes en el programa de muestreo SIG.
4. El registro funciona desde el punto de muestreo, sin depender de la oficina (móvil o tablet).

## Dependencias

- Programa de muestreo SIG (fuente de pilas/polígonos válidos).

## Notas

- _Pendiente: definir comportamiento sin conectividad (modo offline y sincronización posterior)._
