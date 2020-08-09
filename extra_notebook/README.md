## Extra Notebook

Jupyter Notebook on this directory only served as quick experiment

## Notebook description

| Filename             | Link to Kaggle Kernel                                                             | Environment | Description                                                                                                                          |
| -------------------- | --------------------------------------------------------------------------------- | ----------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| 01_sklearn_nb.ipynb  | https://www.kaggle.com/ilosvigil/scl-2020-8-scikit-learn?scriptVersionId=39954833 | Kaggle CPU  | Uses Bernoulli NB & different preprocessing                                                                                          |
| 02_sklearn_svm.ipynb | https://www.kaggle.com/ilosvigil/scl-2020-8-scikit-learn?scriptVersionId=39962068 | Kaggle CPU  | Uses SVC & different preprocessing                                                                                                   |
| 03_tabnet.ipynb      | https://www.kaggle.com/ilosvigil/scl-2020-8-tabnet?scriptVersionId=40219093       | Kaggle CPU  | Uses [pytorch-tabnet](https://github.com/dreamquark-ai/tabnet) library                                                               |
| 04_fastai.ipynb      | https://www.kaggle.com/ilosvigil/scl-2020-8-fast-ai?scriptVersionId=40215465      | Kaggle CPU  | Uses [fast.ai tabular](https://docs.fast.ai/tabular.html) module                                                                     |
| 05_ensemble.ipynb    | -                                                                                 | Local       | Ensemble submission file from main notebook 02a_lightgbm_v20.ipynb, 02a_lightgbm_v21.ipynb, 02a_lightgbm_v23.ipynb & 02b_mljar.ipynb |

## Leaderboard (LB) Score

| Notebook filename    | Submission filename            | Public LB | Private LB |
| -------------------- | ------------------------------ | --------- | ---------- |
| 01_sklearn_nb.ipynb  | submission.csv                 | 0.41422   | 0.41164    |
| 02_sklearn_svm.ipynb | submission.csv                 | 0.46062   | 0.47006    |
| 03_tabnet.ipynb      | submission_ensemble_mean.csv   | 0.52090   | 0.52344    |
| 03_tabnet.ipynb      | submission_ensemble_mode.csv   | 0.50874   | 0.51385    |
| 04_fastai.ipynb      | submission_mean.csv            | 0.48266   | 0.48953    |
| 05_ensemble.ipynb    | submission_weighted_vote_1.csv | 0.52755   | 0.53050    |
| 05_ensemble.ipynb    | submission_weighted_vote_2.csv | 0.52789   | 0.52881    |
| 05_ensemble.ipynb    | submission_majority_vote.csv   | 0.52808   | 0.53101    |
