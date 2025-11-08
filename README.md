Análisis Multicriterio para la Selección de Inversiones
Este repositorio documenta la aplicación de modelos de Decisión Multicriterio (MCDA) para un problema de selección de inversiones. El objetivo es clasificar y evaluar cinco alternativas de inversión basándose en un marco de evaluación jerárquico.

La estructura de decisión considera siete subcriterios fundamentales, agrupados en tres categorías principales:

Rentabilidad: (Retorno Esperado, Riesgo, Diversificación)

Compromiso: (Horizonte Temporal, Dedicación)

Operativa: (Liquidez, Comisiones)

Componentes del Proyecto
Los archivos principales de este repositorio son:

<strong><code>Trabajo02_cridellop.Rmd</code></strong> Documento R Markdown que sirve como el análisis central. Integra la definición del problema, el código de ejecución para los modelos y la narrativa de los resultados.

<strong><code>Trabajo02_cridellop.html</code> / <code>.pdf</code></strong> Salidas compiladas del informe (formatos HTML y PDF), presentando el análisis final, las tablas y visualizaciones.

<strong><code>Inversion.ahp</code></strong> Archivo de modelo (formato YAML) que define la jerarquía de 3 niveles y contiene las matrices de comparación pareada requeridas por la librería ahp.

<strong><code>teoriadecision_funciones_...R</code></strong> Módulos de scripts (<code>..._multicriterio.R</code>, <code>..._diagram.R</code>, <code>..._utiles.R</code>) que encapsulan las funciones personalizadas de R necesarias para ejecutar los algoritmos.

<strong><code>solucion_ahp.png</code></strong> Imagen de la tabla de pesos globales (resultado de AHP) utilizada para ilustrar el informe.

Metodología Aplicada
El análisis compara los resultados de tres métodos fundamentales de MCDA:

AHP (Analytic Hierarchy Process): Utilizado para la ponderación sistemática de la jerarquía de criterios y la síntesis de las alternativas.

ELECTRE I: Método de superación (outranking) implementado para identificar el núcleo de alternativas preferidas o no dominadas.

PROMETHEE (I y II): Métodos de superación para establecer un preorden parcial (PROMETHEE I) y un ranking completo (PROMETHEE II) basado en flujos de preferencia.
