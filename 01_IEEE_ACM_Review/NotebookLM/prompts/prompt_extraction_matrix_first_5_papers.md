# Prompt utilizado en NotebookLM para la construcción de la matriz de extracción de datos (Primeros 5 artículos IEEE/ACM)

Actúa como un investigador experto en Inteligencia Artificial, aprendizaje profundo y revisión sistemática de literatura científica.

## Contexto

Estoy desarrollando una investigación sobre la técnica de Inteligencia Artificial denominada **Autoencoders**, cuya pregunta de investigación es:

**¿Cómo contribuyen los autoencoders a la reducción de dimensionalidad?**

Se han cargado en NotebookLM cinco artículos científicos seleccionados de las bases de datos IEEE Xplore y ACM Digital Library, considerados relevantes para responder la pregunta de investigación.

Los artículos pueden incluir diferentes variantes de autoencoders, tales como:

* Stacked Autoencoders (SAE)
* Variational Autoencoders (VAE)
* Graph Autoencoders (GAE)
* Adversarial Autoencoders
* Multimodal Autoencoders
* Deep Autoencoders

## Restricciones Obligatorias

* Utiliza únicamente la información contenida en los artículos proporcionados.
* No inventes información.
* No agregues conocimiento externo.
* No completes información faltante mediante inferencias.
* Si un artículo no reporta un dato específico, indica explícitamente "No reportado".
* Mantén un enfoque académico y objetivo.
* Toda la información extraída debe estar sustentada por el contenido de los artículos.

## Tarea Principal

Analiza los cinco artículos y construye una **Matriz de Extracción de Datos** que permita identificar y comparar la evidencia científica relacionada con la contribución de los autoencoders a la reducción de dimensionalidad.

### Para cada artículo extrae los siguientes campos:

1. ID del artículo
2. Título
3. Autores
4. Año de publicación
5. Fuente (IEEE o ACM)
6. DOI
7. Objetivo de la investigación
8. Tipo de Autoencoder utilizado
9. Dominio o aplicación estudiada
10. Dataset(s) utilizado(s)
11. Metodología propuesta
12. Técnica de reducción de dimensionalidad empleada
13. Métricas de evaluación utilizadas
14. Resultados principales
15. Ventajas identificadas
16. Limitaciones reportadas por los autores
17. Contribución específica a la reducción de dimensionalidad
18. Relación con la pregunta de investigación
19. Observaciones relevantes
20. Nivel de relevancia para responder la pregunta de investigación (Alta, Media o Baja)

## Formato de salida

Presenta la información en forma de tabla estructurada.

Posteriormente incluye una sección denominada:

### Síntesis Comparativa

Analiza de manera comparativa los cinco artículos e identifica:

* Similitudes entre los enfoques propuestos.
* Diferencias metodológicas.
* Tipos de autoencoders más utilizados.
* Estrategias de reducción de dimensionalidad observadas.
* Principales ventajas reportadas.
* Limitaciones recurrentes.
* Patrones comunes encontrados.

### Conclusión

Elabora una conclusión académica que sintetice:

* Cómo contribuyen los autoencoders a la reducción de dimensionalidad según la evidencia encontrada.
* Qué enfoques muestran mejores resultados.
* Cuáles son las limitaciones más frecuentes.
* Qué aspectos requieren investigación futura.

## Reglas de citación

* Toda afirmación debe estar respaldada por los artículos analizados.
* Utiliza citas en formato IEEE dentro del texto: [1], [2], [3], [4], [5].
* No realices afirmaciones sin evidencia documental.
* Al finalizar, incluye la lista completa de referencias en formato IEEE utilizando exclusivamente los cinco artículos proporcionados.

## Nivel de profundidad

Alto nivel académico, orientado a investigación científica y elaboración de una matriz de extracción reproducible.
