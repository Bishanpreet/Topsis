#Topsis Package
A Python package to implement topsis on a given dataset.
##Usage
Following query on terminal will provide you the best and worst decisions for the dataset.
```
python topsis.py dataset_sample.csv 1,1,1,1 0,1,1,0
```
TOPSIS (Technique for Order Preference by Similarity to Ideal Solution) is a multi-criteria decision-making method that is used to determine the best choice among a set of alternatives by considering multiple criteria ⁴. It is a method of compensatory aggregation that compares a set of alternatives, normalizing scores for each criterion and calculating the geometric distance between each alternative and the ideal alternative, which is the best score in each criterion.

The TOPSIS method provides us with the ability to rank alternatives based on relative similarity for ideal solution. Ideal solution is classified in two ways: positive and negative. Positive ideal solutions give maximum benefit criteria and minimum cost criteria.
Some of the advantages of TOPSIS methods are:

Simplicity,
Rationality,
Comprehensibility,
Good computational efficiency,
Ability to measure the relative performance for each alternative in a simple mathematical form 12.
The relative closeness value is calculated for each alternative and is defined as the ratio of the distance from the ideal solution to the sum of the distances from the ideal and negative ideal solutions ⁵. The relative closeness value is always between 0 and 1, and an alternative is best when it is closer to 1.
