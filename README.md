# Extractive Multi-document Summarization using K-means, Centroid-based Method, MMR, and Sentence Position

Python implementation of Extractive Multi-document Summarization as described in [Extractive Multi-document Summarization using K-means, Centroid-based Method, MMR, and Sentence Position](https://www.researchgate.net/publication/338101046_Extractive_Multi-document_Summarization_using_K-means_Centroid-based_Method_MMR_and_Sentence_Position)

## Installation

1. Clone this repository.
2. Ensure packages are installed using "pip install -r requirements.txt".

## Dataset

We use a dataset DUC2007 that is a famous dataset for text summarization.

## Model

We propose an approach to multi-document summarization based on k-means clustering algorithm, combining with centroid-based method, maximal marginal relevance and sentence positions

<img src="https://github.com/caomanhhaipt/Extractive-Multi-document-Summarization-using-Kmeans-Centroid-based-Method-MMR-and-Position/blob/master/img/model.PNG" width="800">




## Generate summary from novel data

```shell
# Running directly from the repository:
test.py --cluster="cluster" --number_sentence_with_centroid="number_sentence_with_centroid" --number_sentence_with_mmr="number_sentence_with_mmr" --path_to_data="path_to_folder"
```
