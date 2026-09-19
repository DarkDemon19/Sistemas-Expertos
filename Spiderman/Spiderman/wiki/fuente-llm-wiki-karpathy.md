# LLM Wiki — Andrej Karpathy

**Tipo:** fuente  
**Creado:** 2026-09-18  
**Actualizado:** 2026-09-18  
**Autor:** Andrej Karpathy  
**Origen:** [Gist LLM Wiki](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f)  
**Revisión archivada:** `ac46de1ad27f92b28ac95459c782c07f6b8c964a`  
**Capturado e incorporado:** 2026-09-18  
**Original:** [Copia local cotejada en inglés](../raw/llm-wiki-karpathy-cotejado.md)  
**Lectura:** completa; se ha incorporado el documento del gist.

## Resumen

Karpathy propone que un agente de IA construya y mantenga una wiki personal persistente a partir de fuentes elegidas por el usuario. Los resúmenes, las conexiones y las síntesis quedan guardados para que el conocimiento se acumule con cada incorporación y cada consulta útil. Véase el original, [«The core idea»](../raw/llm-wiki-karpathy-cotejado.md#the-core-idea).

## Ideas clave

- **Tres capas:** documentos originales inmutables, una wiki elaborada por la IA y un documento de instrucciones que define la organización y el trabajo del agente. [«Architecture»](../raw/llm-wiki-karpathy-cotejado.md#architecture).
- **Incorporación integrada:** una nueva fuente puede actualizar su resumen y varias páginas de temas o entidades, además de sus referencias cruzadas. [«Operations»](../raw/llm-wiki-karpathy-cotejado.md#operations).
- **Consultas que dejan conocimiento:** las respuestas valiosas pueden convertirse en páginas de la wiki con sus citas. [«Operations»](../raw/llm-wiki-karpathy-cotejado.md#operations).
- **Revisión periódica:** conviene detectar contradicciones, afirmaciones desactualizadas, páginas aisladas y lagunas de información. [«Operations»](../raw/llm-wiki-karpathy-cotejado.md#operations).
- **Índice y registro complementarios:** `index.md` permite encontrar contenidos; `log.md` explica qué se hizo y cuándo. [«Indexing and logging»](../raw/llm-wiki-karpathy-cotejado.md#indexing-and-logging).
- **Implementación modular:** los formatos, la estructura y las herramientas deben adaptarse a las necesidades de cada biblioteca. [«Note»](../raw/llm-wiki-karpathy-cotejado.md#note).

## Relaciones

- [Biblioteca de conocimiento mantenida por IA](tema-biblioteca-conocimiento.md): síntesis del patrón y aplicación a esta biblioteca.

## Límites y preguntas abiertas

- El texto describe una propuesta de organización y la experiencia de su autor. Las afirmaciones sobre esfuerzo de mantenimiento y escala no vienen acompañadas de una evaluación comparativa en este documento. Véanse [«Why this works»](../raw/llm-wiki-karpathy-cotejado.md#why-this-works) e [«Indexing and logging»](../raw/llm-wiki-karpathy-cotejado.md#indexing-and-logging).
- La propuesta general ya se ha aplicado a la primera colección de esta biblioteca; su [página de método](tema-biblioteca-conocimiento.md#colección-actual) explica cómo se conectan las fuentes sobre Spider-Man.

## Historial de captura

La [captura inicial](../raw/llm-wiki-karpathy.md) contiene dos errores de transcripción: «The LLM stays current» en lugar de «The wiki stays current», y un cambio de orden en la enumeración de «Why this works». Se conserva como antecedente. La copia cotejada enlazada como original reproduce el texto consultado de la misma revisión del gist; las citas de esta página remiten a ella.

[Volver al índice](index.md).
