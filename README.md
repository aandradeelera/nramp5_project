# Análisis bioinformático del gen NRAMP5 en plantas

Proyecto final – Curso de Herramientas Bioinformáticas (2025)

---

## Introducción
El gen NRAMP5 (Natural Resistance-Associated Macrophage Protein 5) participa en el transporte de metales en plantas y ha sido ampliamente estudiado por su relación con la absorción de metales esenciales y tóxicos. El análisis bioinformático de este gen permite explorar su conservación y relación evolutiva entre distintas especies vegetales.

## Hipótesis
El gen NRAMP5 presenta variabilidad en su secuencia de aminoácidos entre diferentes especies de plantas, reflejando su relación evolutiva.

## Objetivo
Analizar la relación filogenética del gen NRAMP5 en diferentes especies vegetales mediante alineamiento múltiple y reconstrucción filogenética.

## Dataset
- Número de secuencias: 10
- Tipo de secuencias: aminoácidos
- Gen analizado: NRAMP5
- Especies vegetales diversas, incluyendo *Theobroma cacao*
- Fuente: bases de datos públicas

## Metodología
El análisis se realizó en Google Colab siguiendo los métodos desarrollados durante el curso:
- Lectura y verificación de secuencias en formato FASTA usando Biopython.
- Alineamiento múltiple de secuencias con MAFFT.
- Cálculo de distancias utilizando la matriz BLOSUM62.
- Construcción de un árbol filogenético mediante el método Neighbor-Joining.
- Visualización del árbol filogenético.

## Resultados
El alineamiento múltiple permitió comparar las secuencias del gen NRAMP5 entre las especies analizadas. El árbol filogenético obtenido mostró agrupamientos coherentes con la clasificación taxonómica conocida. La secuencia de *Theobroma cacao* se presentó como un linaje diferenciado, sugiriendo una mayor divergencia respecto a las demás especies analizadas.

## Conclusiones
El análisis filogenético del gen NRAMP5 evidenció su conservación entre diferentes grupos de plantas, así como variaciones que reflejan la historia evolutiva de las especies. La posición filogenética de *Theobroma cacao* resalta el interés de realizar estudios posteriores sobre genes relacionados con el transporte de metales en esta especie.
