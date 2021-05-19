# MLClassifiers

This repository is for building machine learning models for textual as well as visual terms

## Introduction

To regenerate your results you should have do follow our guideline:

1. Run unbiased Scene graph generation on your dataset to generate descriptions for your images.
2. Filter the results and export them to the sqlite database.
3. Augment the dataset based on previous results.


### unbiased Scene graph generation

We have used this [repository](https://github.com/KaihuaTang/Scene-Graph-Benchmark.pytorch) to generate scene graphs, please follow their instructions to install the scene graph benchmark.
