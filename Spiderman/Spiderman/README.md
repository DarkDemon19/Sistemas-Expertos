# Biblioteca de conocimiento

Una biblioteca personal que crece con tus documentos y tus preguntas. Tú aportas las fuentes; la IA las lee y mantiene una wiki de resúmenes, temas y conexiones que puedes consultar en Obsidian.

Basada en [LLM Wiki, de Andrej Karpathy](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f).

**Empieza por el [índice de la biblioteca](wiki/index.md).**

## Estructura básica

```text
README.md                            Guía de uso
AGENTS.md                            Instrucciones para la IA
raw/                                 Documentos originales
wiki/                                Conocimiento elaborado por la IA
  index.md                           Catálogo de páginas
  log.md                             Historial de operaciones
  fuente-*.md                        Resúmenes con enlaces a los originales
  tema-*.md                          Síntesis, personajes y actores
  consulta-*.md                      Respuestas guardadas cuando se necesiten
plantillas/                          Modelos para nuevas páginas
  fuente.md
  tema.md
  consulta.md
```

Todo se guarda en archivos Markdown, que también puedes abrir con un editor de texto. Las páginas de la wiki empiezan en una sola carpeta; los prefijos `fuente-`, `tema-` y `consulta-` ayudan a distinguirlas.

## Primeros pasos

### 1. Abrir la biblioteca

Abre esta carpeta como bóveda en Obsidian y entra en `wiki/index.md`. Los enlaces permiten navegar entre los resúmenes, los temas y sus documentos originales.

Para trabajar con la IA, abre el agente en esta misma carpeta y pídele que lea [AGENTS.md](AGENTS.md). Ahí están las reglas de organización y mantenimiento.

### 2. Añadir un documento

Copia un artículo, PDF, apunte o transcripción dentro de `raw/`. Después pide a la IA, sustituyendo el nombre por el de tu archivo:

> Lee AGENTS.md e incorpora raw/mi-documento.pdf a la biblioteca. Resume su contenido, intégralo en los temas relacionados y actualiza el índice y el registro.

También puedes darle un enlace:

> Incorpora esta URL a la biblioteca: [pega aquí el enlace]. Guarda una copia del contenido accesible en raw/ y procésala siguiendo AGENTS.md.

La IA conserva el original y escribe el resumen en `wiki/`. Si el documento necesita transcripción o no se puede leer completo, lo indicará en la página de la fuente.

**Añadir un archivo por sí solo no lo procesa:** la incorporación se realiza cuando se la pides al agente.

### 3. Hacer preguntas

> Lee AGENTS.md y consulta la wiki: ¿qué sabemos sobre [tema]? Incluye enlaces a las fuentes.

Para conservar una respuesta útil:

> Guarda esta respuesta como una página de consulta en la wiki y enlázala desde el índice y los temas relacionados.

### 4. Revisar la biblioteca

> Revisa la biblioteca siguiendo AGENTS.md: comprueba enlaces, páginas sin conectar, afirmaciones sin fuente y posibles contradicciones. Actualiza el registro con el resultado.

## Ejemplo ya incorporado

La guía que dio origen a esta biblioteca está guardada como [documento original](raw/llm-wiki-karpathy-cotejado.md), con un [resumen en español](wiki/fuente-llm-wiki-karpathy.md) y un [tema relacionado](wiki/tema-biblioteca-conocimiento.md).

El original conserva su idioma; las páginas elaboradas están en español. La primera colección temática ya reúne información sobre [Spider-Man](wiki/tema-spider-man.md), sus [películas e intérpretes](wiki/tema-spider-man-cine.md) y sus [trajes](wiki/tema-trajes-spider-man.md). Todas las fuentes y páginas están accesibles desde el [índice](wiki/index.md).

## Cómo crecer

Empieza añadiendo una fuente cada vez y revisando su resumen. Las [plantillas de fuente](plantillas/fuente.md), [tema](plantillas/tema.md) y [consulta](plantillas/consulta.md) orientan a la IA; también puedes copiarlas manualmente, sustituir los campos `{{...}}` y completar su contenido.

Cuando haya suficientes páginas para necesitarlo, podrás agruparlas en subcarpetas o incorporar herramientas de búsqueda. El [registro](wiki/log.md) deja constancia de cómo evoluciona la biblioteca.
