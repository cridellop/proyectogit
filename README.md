Este repositorio contiene la implementación y comparación de tres metodologías clave de Decisión Multicriterio (DMC): AHP, ELECTRE I y PROMETHEE. El objetivo es evaluar cinco alternativas de inversión para determinar la opción óptima sopesando siete subcriterios agrupados en Rentabilidad, Compromiso y Operativa.

🎯 El Problema
La selección se basa en encontrar la mejor alternativa de inversión (A1 a A5) evaluando un conjunto de criterios ponderados:

Rentabilidad: (Retorno Esperado, Riesgo, Diversificación)

Compromiso: (Horizonte Temporal, Dedicación)

Operativa: (Liquidez, Comisiones)

🛠️ Metodologías Aplicadas
AHP (Analytic Hierarchy Process): Para la ponderación de criterios y evaluación basada en comparaciones pareadas.

ELECTRE I: Un método de superación (outranking) para identificar el núcleo de alternativas preferidas.

PROMETHEE (I y II): Métodos de superación para establecer un preorden parcial (PROMETHEE I) y un ranking completo (PROMETHEE II) de las alternativas.

📁 Estructura del Repositorio
A continuación, se describe el contenido de los archivos principales del proyecto:

<strong>Trabajo02_cridellop.Rmd</strong>
asdasdad
Es el informe completo del proyecto. Este documento R Markdown contiene la definición detallada del problema, la matriz de decisión inicial y la implementación completa de las metodologías AHP, ELECTRE I y PROMETHEE utilizando código R.

<strong>Trabajo02_cridellop.html / Trabajo02_cridellop.pdf</strong>

Los informes renderizados (HTML y PDF) con la resolución completa del problema y los resultados finales.

<strong>Inversion.ahp</strong>

El modelo AHP en formato YAML. Almacena la estructura jerárquGica de tres niveles (Objetivo > Criterios > Subcriterios) y todos los juicios de comparación pareada introducidos para el análisis con la librería ahp.

<strong>teoriadecision_funciones_...R</strong>

Conjunto de scripts de R (teoriadecision_funciones_multicriterio.R, ..._diagram.R, ..._utiles.R) que contienen las funciones personalizadas utilizadas para el análisis multicriterio.

<strong>solucion_ahp.png</strong>

Imagen que muestra la tabla de resultados (pesos globales) generada por el método AHP.asdasdasd
