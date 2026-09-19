# Registro de operaciones

Historial cronológico de la biblioteca. Las entradas nuevas se añaden al final con el formato `## [AAAA-MM-DD] operacion | Título`.

[Volver al índice](index.md).

## [2026-09-18] init | Creación de la biblioteca

- Creada la estructura inicial en Markdown: `raw/`, `wiki/` y `plantillas/`.
- Documentadas las convenciones y los procedimientos de incorporación, consulta y revisión en [AGENTS.md](../AGENTS.md).
- Añadidos la [guía de uso](../README.md), el [índice](index.md) y las plantillas de [fuente](../plantillas/fuente.md), [tema](../plantillas/tema.md) y [consulta](../plantillas/consulta.md).

## [2026-09-18] ingest | LLM Wiki — Andrej Karpathy

- Incorporada la guía proporcionada por el usuario como primera fuente.
- Guardado el [documento original](../raw/llm-wiki-karpathy.md) en inglés, a partir de la revisión `ac46de1ad27f92b28ac95459c782c07f6b8c964a` del gist.
- Leído el documento completo y creado el [resumen en español](fuente-llm-wiki-karpathy.md).
- Creado y enlazado el tema [Biblioteca de conocimiento mantenida por IA](tema-biblioteca-conocimiento.md).
- Actualizado el [índice](index.md) con las dos páginas de contenido.

## [2026-09-18] maintenance | Cotejo de la captura inicial

- Detectados dos errores de transcripción en la copia archivada durante la incorporación: una palabra sustituida y una enumeración reordenada.
- Añadida una [copia cotejada](../raw/llm-wiki-karpathy-cotejado.md) del texto de la misma revisión del gist, conservando la [captura inicial](../raw/llm-wiki-karpathy.md).
- Actualizadas las referencias en la [guía de uso](../README.md), el [resumen de la fuente](fuente-llm-wiki-karpathy.md) y el [tema relacionado](tema-biblioteca-conocimiento.md). El historial de captura del resumen explica la diferencia entre los dos archivos.

## [2026-09-18] maintenance | Verificación inicial de la estructura

- Comprobados por inspección los destinos de los enlaces locales de los documentos creados y los apartados citados del original.
- Confirmado que las dos páginas de contenido aparecen en el índice, se enlazan entre sí y contienen sus metadatos y referencias.
- Comprobado que las páginas de la wiki no contienen campos de plantilla pendientes de sustituir.
- Páginas: [índice](index.md), [fuente](fuente-llm-wiki-karpathy.md) y [tema](tema-biblioteca-conocimiento.md).

## [2026-09-18] query | Destino de las capturas desde Brave

- Consulta operativa sobre dónde guardar los artículos capturados con una extensión del navegador: el destino de las fuentes es `raw/`, según la [guía de uso](../README.md).
- Orientación para Obsidian Web Clipper: seleccionar la bóveda de esta biblioteca y usar `raw` como ubicación relativa de las notas. La incorporación a la wiki se solicita después al agente.
- No se ha creado una página de consulta. Pendiente confirmar el nombre de la extensión si no se trata de Obsidian Web Clipper; su configuración no se ha modificado.

## [2026-09-18] ingest | Spider-Man — Wikipedia

- Leído el texto completo disponible de la captura, incluidas bibliografía y notas; creados el resumen y las conexiones sobre personaje, cómics, cine y equipo.
- Páginas: [fuente](fuente-wikipedia-spider-man.md), [Spider-Man](tema-spider-man.md), [cine](tema-spider-man-cine.md), [trajes](tema-trajes-spider-man.md) e [índice](index.md).
- Límites: imágenes externas no examinadas; notas 26, 30 y 176 vacías. Documentadas diferencias de autoría, poderes, fechas y ámbito de taquilla, además de referencias temporales antiguas.

## [2026-09-18] ingest | Tobey Maguire — Wikipedia

- Leído el texto completo disponible, incluidas tablas y referencias; resumidas la trayectoria del actor, la trilogía de Raimi y su regreso en 2021.
- Páginas: [fuente](fuente-wikipedia-tobey-maguire.md), [Tobey Maguire](tema-tobey-maguire.md), [cine](tema-spider-man-cine.md) e [índice](index.md).
- Límites: imágenes externas no examinadas ni referencias externas verificadas. Registradas discrepancias sobre primer papel en cine, denominación del reconocimiento de PETA y ranking de taquilla frente al artículo del personaje.

## [2026-09-18] ingest | Andrew Garfield — Wikipedia

- Leído el texto completo disponible, incluidas tablas y referencias; conectados cine, teatro, televisión, música y su versión de Peter Parker.
- Páginas: [fuente](fuente-wikipedia-andrew-garfield.md), [Andrew Garfield](tema-andrew-garfield.md), [cine](tema-spider-man-cine.md) e [índice](index.md).
- Límites: imágenes externas no examinadas; nota 121 vacía, errores de tabla y diferencias entre fechas de obras y premios. Modalidad de aparición en *Across the Spider-Verse* y estado de proyectos recientes pendientes de cotejo.

## [2026-09-18] ingest | Tom Holland — Wikipedia

- Leído el texto completo disponible, incluidas tablas y referencias; resumidas su trayectoria, interpretación en el UCM, producción y filantropía.
- Páginas: [fuente](fuente-wikipedia-tom-holland.md), [Tom Holland](tema-tom-holland.md), [cine](tema-spider-man-cine.md) e [índice](index.md).
- Límites: imágenes externas no examinadas; discrepancia interna sobre National Board of Review y referencias que no respaldan de forma evidente determinadas filas. Afirmaciones de 2026 sobre estrenos, récords y vida personal registradas como atribuciones de la captura, sin verificación externa.

## [2026-09-18] ingest | Trajes de Spider-Man — El Output

- Procesados los doce apartados de cómics y los cinco bloques cinematográficos del texto; clasificados los trajes por función, transformación, entorno e identidad.
- Páginas: [fuente](fuente-el-output-trajes-spider-man.md), [trajes](tema-trajes-spider-man.md), [Spider-Man](tema-spider-man.md), [cine](tema-spider-man-cine.md), [Maguire](tema-tobey-maguire.md), [Garfield](tema-andrew-garfield.md), [Holland](tema-tom-holland.md) e [índice](index.md).
- Límites: lectura textual completa y cobertura visual parcial, con imágenes remotas no examinadas. Catálogo de 2021 no exhaustivo; números de cómic y algunos orígenes de trajes pendientes de contrastar.

## [2026-09-18] ingest | Los tres Spider-Man — RTVE

- Leído el texto completo de la guía y contrastado con las capturas de Wikipedia para distinguir las tres etapas cinematográficas y su encuentro en *No Way Home*.
- Páginas: [fuente](fuente-rtve-actores-spider-man.md), [cine](tema-spider-man-cine.md), [Maguire](tema-tobey-maguire.md), [Garfield](tema-andrew-garfield.md), [Holland](tema-tom-holland.md) e [índice](index.md).
- Límites: imágenes externas no examinadas. Documentadas la confusión sobre el UCM, la especulación de precuela, la discrepancia de fechas, la edad desactualizada de Holland, la disponibilidad caducada en RTVE Play y la numeración de universo sin corroborar.

## [2026-09-18] maintenance | Categorización y comprobación de la colección

- Inventariados los ocho archivos de `raw/`: seis capturas nuevas sobre Spider-Man y dos copias del documento de Karpathy ya relacionadas en un único resumen.
- Creadas doce páginas: seis resúmenes de fuentes y seis temas, incluidos los tres perfiles de actores. La wiki reúne ahora siete fuentes y siete temas.
- Reorganizado el [índice](index.md) por personaje y cómics, cine y adaptaciones, trajes y equipo, actores y método; las fuentes se agrupan por procedencia y función.
- Actualizados la [guía de uso](../README.md), el [tema de método](tema-biblioteca-conocimiento.md) y la [fuente de Karpathy](fuente-llm-wiki-karpathy.md) para reflejar la colección existente.
- Comprobados mecánicamente 21 documentos de la wiki, guía, instrucciones y plantillas: destinos locales y apartados, metadatos, campos pendientes, inclusión en el índice, conexiones entrantes, enlaces de retorno entre fuentes y temas y cobertura de los ocho originales. La comprobación terminó sin errores.
- Alcance de contenido: texto de las seis capturas leído, con tablas y referencias disponibles. Quedan pendientes las imágenes externas y la comprobación directa de las obras o páginas citadas; las lagunas y discrepancias concretas están en cada resumen y en los temas correspondientes.
