### Repo for the project _Imputation Models for Overcoming Non-Random Missingness in ICU EHR Data: A Benchmark Study_

- Since this project involved benchmarking several SOTA imputation models, we have cloned their respective repositories and included here.
    - One dir per model.
    - The exception is BRITS where we used the implementation by the author of SAITS.
- For CSDI, results were obtained via a jupyter notebook, CSDI/evaluate.ipynb.
- For all other models, results were obtained by calling corresponding python executable main scripts.
- Results are reproducable by downloading the Physionet 2012 and 2019 datasets from their respective websites and using the train-test splits such as:
    - Set A of each dataset is training data.
    - Set B of each dataset is testing data.

