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
- Fuente: NCBI

## Metodología
El análisis se realizó en Google Colab siguiendo los siguientes métodos:
- Lectura y verificación de secuencias en formato FASTA usando Biopython.
- Alineamiento múltiple de secuencias con MAFFT.
- Cálculo de distancias utilizando la matriz BLOSUM62.
- Construcción de un árbol filogenético mediante el método Neighbor-Joining.
- Visualización del árbol filogenético.

## Resultados
Se construyó un árbol filogenético del gen NRAMP5 a partir de 10 secuencias de aminoácidos provenientes de distintas especies de plantas de importancia agrícola y modelo. El alineamiento múltiple se realizó a nivel proteico y el árbol fue inferido utilizando el método Neighbor-Joining, considerando las distancias evolutivas entre las secuencias.

El árbol filogenético obtenido muestra una agrupación evidente de las secuencias de NRAMP5 acorde a la relación filogenética entre las especies, lo que sugiere una alta conservación evolutiva del gen dentro del reino Plantae.

- Agrupamiento por linajes evolutivos

Las secuencias de plantas monocotiledóneas, representadas por *Oryza sativa* (Osj_NRAMP5) y *Zea mays* (ZmNRAMP5), forman un clado bien definido, indicando una mayor cercanía evolutiva entre estas especies y una posible conservación funcional del transportador NRAMP5 en este grupo.

Por otro lado, las secuencias correspondientes a leguminosas como *Medicago truncatula* (MtNRAMP5) y *Trifolium repens* (TrNRAMP5), se agrupan en un mismo clado, lo cual es consistente con su relación taxonómica y sugiere una evolución paralela del gen dentro de este linaje.

Las especies de orquídeas como *Phalaenopsis equestris* (PeNRAMP5) y *Platanthera zijinensis* (PzNRAMP5), también conforman un clado independiente, evidenciando una diferenciación clara respecto a otros grupos de plantas analizadas.
Las secuencias de *Solanum tuberosum* (StNRAMP5-like) y *Nicotiana attenuata* (NaNRAMP5) se agrupan juntas, reflejando su pertenencia a la familia Solanaceae y una alta similitud a nivel proteico del gen NRAMP5.
La secuencia de *Arabidopsis thaliana* (AtNRAMP5) aparece separada del clado de solanáceas y monocotiledóneas, lo cual concuerda con su posición filogenética como dicotiledónea modelo y su divergencia evolutiva respecto a otros grupos analizados.

- Posición de *Theobroma cacao*

La secuencia de NRAMP5 de *Theobroma cacao* se ubica de manera más divergente en el árbol, formando una rama independiente. Esta posición sugiere una mayor distancia evolutiva con respecto a las demás especies incluidas en el análisis, lo que podría estar asociado a variaciones estructurales o funcionales del transportador NRAMP5 en cacao.
Este resultado es particularmente relevante, dado el interés del gen NRAMP5 en la absorción y translocación de metales como el cadmio, y refuerza la importancia de estudiar este gen en cacao desde una perspectiva funcional y comparativa.

## Conclusiones
El análisis filogenético del gen NRAMP5 evidenció su conservación entre diferentes grupos de plantas, así como variaciones que reflejan la historia evolutiva de las especies. La posición filogenética de *Theobroma cacao* resalta el interés de realizar estudios posteriores sobre genes relacionados con el transporte de metales en esta especie.
