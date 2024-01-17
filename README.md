# Evaluation Framework with Novel Agriculture Ontology

**Authors:** Khadija Meghraoui (IAVH2, Morocco), Teeradaj Racharak (JAIST, Japan), Kenza Ait El Kadi (IAVH2, Morocco), Saloua Bensiali (IAVH2, Morocco), Imane Sebari (IAVH2, Morocco).

**Contacts:** k [dot] meghraoui [at] iav [dot] ac [dot] ma  / racharak [at] jaist [dot] ac [dot] jp / k [dot] aitelkadi [at] iav [dot] ac [dot] ma / s [dot] bensiali [at] iav [dot] ac [dot] ma / i [dot] sebari [at] iav [dot] ac [dot] ma

**Disclaimer:** This repository contains executable source codes supporting our submission to ICAART 2024 (Short paper).

## Link to the conference:
https://icaart.scitevents.org/

## File Documentation
1. crop ontology to use
2. OWL2Vecstar
3. RDF2Vec
4. Word2Vec
5. Cosine_similarity_OWL2Vec
6. Cosine_similarity_RDF2Vec
7. Cosine_similarity_Word2Vec
8. t_SNE_and_Heatmap_OWL2Vec
9. t_SNE_and_Heatmap_RDF2Vec
10. t_SNE_and_Heatmap_Word2Vec

**1. The "crop ontology to use" File:** This file contains the agriculture ontology constructed by the authors of this work, with various concepts, role names, and populated individuals. 

**2. The "OWL2Vecstar" File:** The latter contains the source code that was executed to generate the embedding or representation learning of the designed ontology using OWL2Vec*.

**3. The "RDF2Vec" File:** It encompasses the source code that was run to produce the embedding for the designed ontology using RDF2Vec.

**4. The "Word2Vec" File:** It includes the source code that was executed to generate the embedding for the designed ontology using Word2Vec.

**5. The "Cosine_similarity_OWL2Vec"File:** It indicates the calculation of cosine similarity matrices for every 10 individuals in each considered class, utilizing vector representations generated using the OWL2Vec* algorithm.

**6. The "Cosine_similarity_RDF2Vec"File:** It indicates the calculation of cosine similarity matrices for every 10 individuals in each considered class, utilizing vector representations generated using RDF2Vec algorithm.

**7. The Cosine_similarity_Word2Vec"File:** It indicates the calculation of cosine similarity matrices for every 10 individuals in each considered class, utilizing vector representations generated using Word2Vec algorithm.

**8 The "t_SNE_and_Heatmap_OWL2Vec"File:** In this code section, we have established a visualization in the vector space derived from the embedding using the t-SNE technique, as well as the representation through heatmaps of the cosine similarity matrices for the different classes of our ontology. It is worth noting that these visualizations pertain to the OWL2Vec* algorithm.

**9 The "t_SNE_and_Heatmap_RDF2Vec"File:** Within this portion of the code, we have implemented a visualization in the vector space created from the embedding using the t-SNE technique. Additionally, we have represented the cosine similarity matrices for various classes in our ontology through heatmaps. It is important to highlight that these visualizations are associated with the RDF2Vec algorithm.




