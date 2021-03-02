# Project1: Probably Interesting Data

## Distribution estimation
1. Set up a new git repository in your GitHub account
2. Pick two datasets from https://www.kaggle.com/uciml/datasets
3. Choose a programming language (Python, C/C++, Java)
4. Formulate ideas on how machine learning can be used to model distributions within the dataset
5. Build a heuristic and/or algorithm to model the data using mixture models of probability distributions programmatically
6. Document your process and results
7. Commit your source code, documentation and other supporting files to the git repository in GitHub


## What are we doing?
- Using Expectation-Maximization model we are trying to form disitributions.

---
## Data
- Wine quality data (available in data folder of this repo)
- Iris data (available in data folder of this repo)

---

## Results:

- Actual distributions of the wine quality dataset:
- ![](https://github.com/SFLazarus/Mixture-Models/blob/main/reports/wineQuality-data-actual%20distributions.png)
- Predicted distributions of the wine quality dataset:
- ![](https://github.com/SFLazarus/Mixture-Models/blob/main/reports/wineQuality-data-predicted-distributions.png)
- Actual distributions of the Iris dataset
- ![](https://github.com/SFLazarus/Mixture-Models/blob/main/reports/iris-data-actual%20distributions.png)
- Predicted distributions of the Iris dataset
- ![](https://github.com/SFLazarus/Mixture-Models/blob/main/reports/iris-data-predicted-distributions.png)

- E-M model has formed distributions quite good but for iris data resukts were nmuch satisfying than that for wine quality data
- I observed that when the data is distributed and scattered well, then the distribution predictions are much better.

---
## References:

- https://en.wikipedia.org/wiki/Expectation%E2%80%93maximization_algorithm#Gaussian_mixture
- https://www.youtube.com/watch?v=DIADjJXrgps
- https://www.youtube.com/watch?v=qy3WKmSXM64

---

# Project Structure:
### Readme.md
- Project description
### Data
- Contains raw data files both Iris dataset and wine quality dataset
### Notebooks
- Jupyter Notebook implementing Expectation-Maximization model.
### Reports
- Visualizations in png format images 
### Requirements.txt
- Info about Tools, frameworks and libraries required to reproduce the work flow
