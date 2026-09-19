# Biblioteca de conocimiento mantenida por IA

**Tipo:** tema  
**Creado:** 2026-09-18  
**Actualizado:** 2026-09-18

## Síntesis

Una biblioteca de este tipo transforma documentos seleccionados por una persona en páginas conectadas que se actualizan con ayuda de una IA. El resultado es conocimiento persistente: resúmenes, relaciones y respuestas útiles que pueden consultarse y ampliarse después. [Fuente: LLM Wiki](fuente-llm-wiki-karpathy.md); original, [«The core idea»](../raw/llm-wiki-karpathy-cotejado.md#the-core-idea).

## Organización básica

El patrón distingue tres capas ([«Architecture»](../raw/llm-wiki-karpathy-cotejado.md#architecture)):

| Capa | Función | Aplicación en esta biblioteca |
| --- | --- | --- |
| Fuentes originales | Conservar el material de referencia | `raw/` |
| Wiki elaborada | Mantener resúmenes y conexiones | `wiki/` |
| Instrucciones | Dar continuidad a la forma de trabajar de la IA | [AGENTS.md](../AGENTS.md) |

## Ciclo de trabajo

1. **Incorporar:** leer una fuente y actualizar el conocimiento relacionado.
2. **Consultar:** responder a partir de lo documentado y conservar las síntesis útiles.
3. **Revisar:** detectar enlaces ausentes, contradicciones, información desactualizada y lagunas.

Estas operaciones proceden de [«Operations»](../raw/llm-wiki-karpathy-cotejado.md#operations). El [índice](index.md) facilita la navegación y el [registro](log.md) conserva la historia del trabajo, siguiendo [«Indexing and logging»](../raw/llm-wiki-karpathy-cotejado.md#indexing-and-logging).

## Decisiones de esta biblioteca

Estas son decisiones de implementación locales, adaptadas a la petición de empezar con elementos sencillos:

- Páginas en español, guardadas como archivos Markdown.
- Una carpeta plana de wiki con prefijos para fuentes, temas y consultas.
- Metadatos breves y tres plantillas reutilizables.
- Incorporación mediante peticiones al agente, una fuente cada vez como punto de partida.

La [guía de uso](../README.md) explica cómo trabajar con esta estructura. Karpathy deja abierta la implementación concreta en [«Note»](../raw/llm-wiki-karpathy-cotejado.md#note).

## Colección actual

La primera colección temática se centra en [Spider-Man](tema-spider-man.md). Las capturas aportadas se conectan mediante páginas de [cine y adaptaciones](tema-spider-man-cine.md), [trajes y equipo](tema-trajes-spider-man.md) y perfiles de actores accesibles desde el [índice](index.md).

Como aplicación del patrón, cada captura cuenta con un resumen que enlaza el original y declara sus límites de lectura. Los temas reúnen información de varias fuentes y explican las discrepancias encontradas, como las de continuidad cinematográfica. El índice agrupa por categorías sin requerir nuevas subcarpetas.

## Fuentes y relaciones

- [LLM Wiki — Andrej Karpathy](fuente-llm-wiki-karpathy.md): única fuente incorporada hasta el momento sobre este patrón.

## Preguntas abiertas

- ¿Qué profundidad de resumen será útil para los documentos que se incorporen?

[Volver al índice](index.md).
