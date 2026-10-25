# Principio de Incertianguis

Solución para el **Reto 1. Comercio popular y barrial** del *Chilangatón: Tecnología e Innovación Social para Futuros de la Ciudad* (25 de octubre, UTOPÍA Elena Poniatowska Amor, Coyoacán, CDMX).

## El reto

El comercio popular y barrial de la CDMX (339 mercados públicos, 1,367 tianguis registrados, 86,931 unidades de abarrotes) **no tiene un medio integrado para saber dónde se ubica, cuándo opera y qué ofrece**. Además solo el 30.6% de las unidades económicas usó internet en 2023 y el 87.8% cobra en efectivo, mientras compite en desventaja con supermercados y tiendas de conveniencia.

## La idea

> **Principio de Incertianguis:** la información de un tianguis nunca es cierta ni falsa, solo tiene distintos grados de confianza. En lugar de fingir certeza, el sistema **expone la incertidumbre** —y la usa como señal de qué falta documentar.

Un catálogo abierto que responde: *¿qué tianguis está abierto ahora cerca de mí, qué vende y qué tan confiable es ese dato?*

## Alcance del prototipo

1. **Ubicar cada tianguis** en Google Maps sin API de pago (endpoint interno + paginación), midiendo confianza del enlace en vez de forzar un match.
2. **Detectar los que no existen digitalmente** — el hallazgo accionable: los que no tienen Place Page son los que necesitan difusión.
3. **Normalizar giros** más allá de "tianguis", para búsqueda por categoría.
4. **UX de cercanía**: qué está abierto ahora, con filtros por giro y transporte cercano.

## Estado

Investigación y recolección de datos en curso. Ver [`PROGRESO.md`](PROGRESO.md) para metodología, mediciones y hallazgos.

## Stack

Python (recolección y scoring) + datos abiertos de SEDECO, DENUE/INEGI y Google Maps.

## Equipo

Chilangatón 2026 — Reto 1.
