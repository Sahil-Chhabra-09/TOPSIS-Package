# Topsis Score Calculation package

![Laptop Info](https://user-images.githubusercontent.com/122990320/223558087-1d3ebabc-c2f0-4c6c-8fad-7e160f9bc10d.png)

```pip install topsisGod```

```from topsisGod import topsis```

Input: Three parameters

1. data: data should contain only integer fields so preprocess the data and temporarily remove the model names
2. Weights: weight of each attribute, considered to be an integer list
3. Impact: Considered to be a character list

Weight = [0.7,0.25,0.5,0.23]

Impact = ['+', '+', '+', '-']

Output: Returns the score of each row

To calculate the rank based on the score, append the score list as:

```score = topsis(data, w, i)```

```from topsisGod import rerank```

```rerank(data,score)```
