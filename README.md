# plagiarism_checker
being in Tybsc i had to give different entrance for college and heard about plagiarism so tried my hand of how it works

# python-plagiarism-checker
_This is Simple project for checking plagiarism of text documents using cosine similarity_

```
On Demo I have used three textfiles on the same directory with plagiarism.ipynb, once we run the notebook
it will open all textfile and tries to find the similarities between them by using cosine similarity
https://www.machinelearningplus.com/nlp/cosine-similarity/
```
https://www.machinelearningplus.com/nlp/cosine-similarity/
```
I used TfidfVectorizer to convert text to vectors so as
I can computer the cosine similarity
```
```
from sklearn.feature_extraction.text import TfidfVectorizer
```
```
I used scikit-learn to computer the cosine similarity
```
```
from sklearn.metrics.pairwise import cosine_similarity
```
