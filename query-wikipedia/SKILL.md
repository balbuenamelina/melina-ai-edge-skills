---
name: query-wikipedia
description: Buscar y verificar información factual en Wikipedia antes de responder. Usar para personas, teorías, conceptos, fechas, lugares, obras y acontecimientos.
---

# QUERY WIKIPEDIA

Usá esta habilidad cuando Melina pida investigar, buscar o verificar información.

Llamá a `run_js` con:

- script name: index.html
- data:
  - topic: tema concreto
  - lang: "es"

Ejemplo:

topic: "Baruch Spinoza"
lang: "es"

Usá la información recuperada como fuente.

Diferenciá entre:
- información encontrada en Wikipedia;
- interpretación propia;
- inferencia.

No inventes datos que no aparezcan en la fuente.

Si Wikipedia no devuelve información suficiente, decilo.

Wikipedia sirve como punto de partida, no como autoridad definitiva para cuestiones filosóficas complejas.
