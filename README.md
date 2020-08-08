# Shopee Code League 2020 - Sentiment Analysis

This is source code/solution for ?th place (top ?%) in Private LB with score ? of [[Student] Shopee Code League 2020 - Marketing Analytics](https://www.kaggle.com/c/student-shopee-code-league-marketing-analytics).

## Disclaimer

* This is work of Cocoa team, we **DO NOT** represent any organization.
* Although we use License "The Unlicense", dataset and generated dataset falls under Shopee Terms and Conditions which can be seen on [Kaggle](https://www.kaggle.com/c/student-shopee-code-league-marketing-analytics/rules)


## Environment List

> Some of the notebook are run on different environment

| Environment Name | Description                         |
| ---------------- | ----------------------------------- |
| Kaggle CPU       | 2C/4T CPU, 16GB RAM                 |
| Local            | 6C/12T CPU, 16GB RAM, 16GB Swapfile |

To ensure you can run jupyter notebook which runs on "Local" environment, make sure that :

1. Use OS based on GNU/Linux
2. Use Python 3.8
3. Install required Python library

```
python3.8 -m pip install matplotlib seaborn pandas numpy mljar-supervised
```

## Notebook description

> Jupyter notebook on `extra_notebook` directory isn't used on the competition

| Filename               | Link to Kaggle Kernel                                                              | Environment | Description                     |
| ---------------------- | ---------------------------------------------------------------------------------- | ----------- | ------------------------------- |
| 01_preprocessing.ipynb | https://www.kaggle.com/ilosvigil/scl-2020-8-preprocessing?scriptVersionId=40024448 | Kaggle CPU  | Minimum amount of preprocessing |
| 02a_mljar.ipynb        | -                                                                                  | Local       | -                               |
| 02b_lightgbm_v20.ipynb | https://www.kaggle.com/ilosvigil/scl-2020-8-lightgbm?scriptVersionId=40306747      | Kaggle CPU  | -                               |
| 02b_lightgbm_v21.ipynb | https://www.kaggle.com/ilosvigil/scl-2020-8-lightgbm?scriptVersionId=40332941      | Kaggle CPU  | -                               |
| 02b_lightgbm_v23.ipynb | https://www.kaggle.com/ilosvigil/scl-2020-8-lightgbm?scriptVersionId=40371184      | Kaggle CPU  | -                               |
| 02c_ensemble.ipynb     | -                                                                                  | Local       | -                               |

## Dataset

The dataset is available on this repository and/or Kaggle datasets platform.

| Created By                        | Filename/directory path | Link to Kaggle datasets                                                      |
| --------------------------------- | ----------------------- | ---------------------------------------------------------------------------- |
| Shopee                            | `data/raw`              | https://www.kaggle.com/c/student-shopee-code-league-marketing-analytics/data |
| Notebook : 01_preprocessing.ipynb | `data/processed`        | https://www.kaggle.com/ilosvigil/shopee-marketing-data                       |

## Leaderboard (LB) Score

| Notebook filename      | Submission filename                       | Used for Final Score | Public LB   | Private LB |
| ---------------------- | ----------------------------------------- | -------------------- | ----------- | ---------- |
| 02a_mljar.ipynb        | submission_2020-08-06 22:24:43.301671.csv | Yes                  | **0.53712** | ?          |
| 02b_lightgbm_v20.ipynb | submission_best_mode.csv                  | No                   | 0.52442     | ?          |
| 02b_lightgbm_v20.ipynb | submission_ensemble_mode.csv              | No                   | 0.52608     | ?          |
| 02b_lightgbm_v21.ipynb | submission_ensemble_mode.csv              | No                   | 0.51941     | ?          |
| 02b_lightgbm_v21.ipynb | submission_weighted_ensemble_mean.csv     | No                   | 0.52344     | ?          |
| 02b_lightgbm_v21.ipynb | submission_best_mean.csv                  | ?                    | 0.52854     | ?          |
| 02b_lightgbm_v23.ipynb | submission_best_mode.csv                  | No                   | 0.52511     | ?          |
| 02b_lightgbm_v23.ipynb | submission_weighted_ensemble_mean.csv     | ?                    | 0.53007     | ?          |
| 02c_ensemble.ipynb     | submission_weighted_vote_1.csv            | No                   | 0.52755     | ?          |
| 02c_ensemble.ipynb     | submission_weighted_vote_2.csv            | No                   | 0.52789     | ?          |
| 02c_ensemble.ipynb     | submission_majority_vote.csv              | No                   | 0.52808     | ?          |

## Guide

> This guide assume you move 

1. Run `01_preprocessing.ipynb`
2. Run `02a_mljar.ipynb`
