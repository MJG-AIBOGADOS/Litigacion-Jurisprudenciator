---
name: normas-consolidadas
description: Consulta el texto vigente de un artículo en los consolidados del BOE guardados en este plugin (Ley de Enjuiciamiento Civil, Ley de Enjuiciamiento Criminal, Ley de la Jurisdicción Contencioso-administrativa, Ley reguladora de la Jurisdicción Social, Estatuto de los Trabajadores, Ley Orgánica 1/2025, Ley Orgánica 5/2000 de menores y su Reglamento). Úsala cuando Jurisprudenciator no esté disponible, se hayan agotado los créditos o falle, y haga falta el texto de un artículo para redactar o para comprobar una cita. También cuando el abogado diga "sin créditos", "mira en las normas guardadas" o "consulta el consolidado".
---

# Normas consolidadas guardadas

Respaldo de legislación para cuando el conector Jurisprudenciator no responda.

## Orden de fuentes

1. Jurisprudenciator, siempre primero.
2. Estos archivos, si Jurisprudenciator no está disponible, se han agotado los créditos o falla.
3. El BOE en línea, si el artículo no está aquí.

Nunca de memoria.

## Dónde están y cómo se consultan

Los archivos están en `references/normas/` de este plugin. `00-INDICE-NORMAS.md` lista cada ley, su identificador del BOE y la fecha del consolidado.

Cada ley tiene un epígrafe `### Artículo N.` por artículo. Para leer un artículo concreto no hay que abrir la ley entera: se busca su epígrafe y se extrae hasta el siguiente. Por ejemplo, el artículo 264 de la Ley de Enjuiciamiento Civil está en `LEC.md` bajo `### Artículo 264.`.

## Reglas al citar

Antes de que un artículo de estos archivos entre en un escrito que se presenta, hay que comprobar en `https://www.boe.es/buscar/act.php?id=<boe_id>` que la fecha de última modificación del BOE no es posterior a la del archivo. Si lo es, el archivo está caducado para ese artículo: hay que decírselo al abogado y no citarlo como vigente.

Al usar estos archivos hay que decir en la respuesta que el texto sale del consolidado guardado y de qué fecha es, no de Jurisprudenciator.

Estos archivos son legislación, no jurisprudencia. Para sentencias hace falta Jurisprudenciator o el buscador público del CENDOJ: una sentencia nunca se cita desde aquí ni de memoria.
