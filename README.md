# Shopee Code League 2020 - Marketing Analytics

This is source code/solution for 7th place (top 2%) in Private LB with score ? of [[Student] Shopee Code League 2020 - Marketing Analytics](https://www.kaggle.com/c/student-shopee-code-league-marketing-analytics). Check [Overview Archive](https://www.kaggle.com/c/student-shopee-code-league-marketing-analytics/overview) and [Leaderboard Archive](https://archive.is/9X9tt) if Kaggle is down or the link is invalid.

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

| Filename               | Link to Kaggle Kernel                                                              | Environment | Description                                                                       |
| ---------------------- | ---------------------------------------------------------------------------------- | ----------- | --------------------------------------------------------------------------------- |
| 01_preprocessing.ipynb | https://www.kaggle.com/ilosvigil/scl-2020-8-preprocessing?scriptVersionId=40024448 | Kaggle CPU  | Minimum amount of preprocessing                                                   |
| 02a_lightgbm_v20.ipynb | https://www.kaggle.com/ilosvigil/scl-2020-8-lightgbm?scriptVersionId=40306747      | Kaggle CPU  | Uses [LightGBM](https://github.com/microsoft/LightGBM) library                    |
| 02a_lightgbm_v21.ipynb | https://www.kaggle.com/ilosvigil/scl-2020-8-lightgbm?scriptVersionId=40332941      | Kaggle CPU  | Uses [LightGBM](https://github.com/microsoft/LightGBM) library                    |
| 02a_lightgbm_v23.ipynb | https://www.kaggle.com/ilosvigil/scl-2020-8-lightgbm?scriptVersionId=40371184      | Kaggle CPU  | Uses [LightGBM](https://github.com/microsoft/LightGBM) library                    |
| 02b_mljar.ipynb        | -                                                                                  | Local       | Use [mljar-supervised](https://github.com/mljar/mljar-supervised/) AutoML library |

## Dataset

The dataset is available on this repository and/or Kaggle datasets platform.

| Created By                        | Filename/directory path | Link to Kaggle datasets                                                      |
| --------------------------------- | ----------------------- | ---------------------------------------------------------------------------- |
| Shopee                            | `data/raw`              | https://www.kaggle.com/c/student-shopee-code-league-marketing-analytics/data |
| Notebook : 01_preprocessing.ipynb | `data/processed`        | https://www.kaggle.com/ilosvigil/shopee-marketing-data                       |

## Leaderboard (LB) Score

| Notebook filename      | Submission filename                       | Used for Final Score | Public LB   | Private LB  |
| ---------------------- | ----------------------------------------- | -------------------- | ----------- | ----------- |
| 02a_lightgbm_v20.ipynb | submission_best_mean.csv                  | No                   | 0.52518     | 0.52700     |
|                        | submission_best_mode.csv                  | No                   | 0.52442     | 0.52488     |
|                        | submission_ensemble_mean.csv              | No                   | 0.52685     | 0.52871     |
|                        | submission_ensemble_mode.csv              | No                   | 0.52608     | 0.52885     |
|                        | submission_weighted_ensemble_mean.csv     | No                   | 0.52685     | 0.52885     |
| 02a_lightgbm_v21.ipynb | submission_best_mean.csv                  | No                   | 0.52854     | 0.52979     |
|                        | submission_best_mode.csv                  | No                   | 0.52671     | 0.52836     |
|                        | submission_ensemble_mean.csv              | No                   | 0.52273     | 0.52523     |
|                        | submission_ensemble_mode.csv              | No                   | 0.51941     | 0.52384     |
|                        | submission_weighted_ensemble_mean.csv     | No                   | 0.52344     | 0.52496     |
| 02a_lightgbm_v23.ipynb | submission_best_mean.csv                  | No                   | 0.52510     | 0.52426     |
|                        | submission_best_mode.csv                  | No                   | 0.52511     | 0.52433     |
|                        | submission_ensemble_mean.csv              | No                   | 0.53174     | 0.53409     |
|                        | submission_ensemble_mode.csv              | No                   | 0.53189     | 0.53392     |
|                        | submission_weighted_ensemble_mean.csv     | Yes                  | 0.53007     | **0.53444** |
| 02b_mljar.ipynb        | submission_2020-08-06 22:24:43.301671.csv | Yes                  | **0.53712** | 0.53173     |

## Guide

> This guide assume you change path or move the file correctly

1. Run `01_preprocessing.ipynb`
2. Run `02a_lightgbm_v20.ipynb`, `02a_lightgbm_v21.ipynb`, `02a_lightgbm_v23.ipynb` or `02b_mljar.ipynb`
