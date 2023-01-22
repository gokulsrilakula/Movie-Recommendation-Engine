# Movie-Recommendation-Engine
Content-Based-Movie-Recommender-System

This is a hollywood movie recommender system built with Python. I've used IMDB 5000 Movie Dataset(From Kaggle) to build this.
![Movei Recomendation Engine](https://user-images.githubusercontent.com/89767722/213937342-54d743c1-2c1d-4a32-8d77-33081e797850.jpg)

TF-IDF stands for term frequency-inverse document frequency and it is a measure, used in the fields of information retrieval (IR) and machine learning, that can quantify the importance or relevance of string representations (words, phrases, lemmas, etc)  in a document amongst a collection of documents (also known as a corpus).

Content Based Recommender System recommends items similar to the items user likes. How does it decide which item is most similar to the item user likes? Here we use the similarity scores.

Similarity Score :
It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.

How Cosine Similarity works?
Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.
