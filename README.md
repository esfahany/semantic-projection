# Semantic Projection using GloVe
Python implementation of semantic projection from [Grand et al. (2022)](https://www.nature.com/articles/s41562-022-01316-8)

Download pre-trained GloVe vectors here: https://nlp.stanford.edu/projects/glove/

Notebook includes functions to calculate:
- Feature vector from two opposing word sets (such as {small, little, tiny} and {large, big, huge})
- Word projections onto feature vector
- Scalar "projection score" of words on feature vector
- Ranking of words on feature vector

There's also an example using the "animals" category from the paper of running a regression of the semantic projection scores on a set of human ratings (ratings generated by me):
![image](https://user-images.githubusercontent.com/26694002/176605204-f985a770-ae5e-43f8-8670-bc8c9be8dcc5.png)
