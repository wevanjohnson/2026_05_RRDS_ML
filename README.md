# RRDS Machine Learning Tutorial (May 2026)

These are the materials for the Red Rock Data Science 2026 machine learning tutorial. The tutorial is scheduled for Thursday, May 21, 2026, from 1:30-3:30pm.

## Things you should know about this tutorial

* Lots of diverse material and new concepts will be covered.
    + Programming and machine learning are __NOT__ spectator sports. You need to practice the skills you learn over and over again.
* Communication: if you have questions or concerns, please email me: <w.evan.johnson@rutgers.edu>
* Materials:
    + All materials for this tutorial are posted on the GitHub page: [https://github.com/wevanjohnson/2026_05_RRDS_ML](https://github.com/wevanjohnson/2026_05_RRDS_ML)
    + Slides are available as both `.Rmd` source files and rendered `.pdf` files.
    + The hands-on `caret` tutorial is available as `caretPackageTutorial.Rmd` and rendered as `caretPackageTutorial.html`.
* Data:
    + The hands-on examples use `TBnanostring.rds`.

## Setup

Please install R and RStudio before the tutorial.

Install the R packages used in the slides and hands-on examples:

```r
install.packages(c(
  "tidyverse", "caret", "DT", "gridExtra", "kableExtra", "dslabs",
  "e1071", "rpart", "randomForest", "neuralnet", "nnet",
  "gbm", "glmnet", "pROC", "xgboost", "lime", "caretEnsemble"
))
```

## Materials

| File | Topic |
| :--- | :---- |
| `ML_introduction.Rmd` / `ML_introduction.pdf` | Introduction to machine learning, data science, regularization, and kernel-based learning |
| `regularization.Rmd` / `regularization.pdf` | Bias-variance tradeoff, ridge regression, lasso, elastic net, and `glmnet` |
| `svm.Rmd` / `svm.pdf` | Support vector machines, kernels, and TB NanoString classification |
| `trees.Rmd` / `trees.pdf` | Decision trees, regression trees, classification trees, and random forests |
| `gradientBoost.Rmd` / `gradientBoost.pdf` | Boosting, gradient boosting, XGBoost, LIME, and SHAP |
| `neuralNet.Rmd` / `neuralNet.pdf` | Neural networks, deep learning, CNNs, RNNs, and transformers |
| `caretPackageTutorial.Rmd` / `caretPackageTutorial.html` | Hands-on machine learning workflow using `caret` and the TB NanoString dataset |

## Schedule

| Day/Time | Topics |
| :------- | :----- |
| Thu 1:30-2:00pm | Introduction to machine learning, data science workflows, regularization, and kernels |
| Thu 2:00-2:35pm | Support vector machines, decision trees, random forests, and boosting |
| Thu 2:35-3:05pm | Neural networks and deep learning concepts |
| Thu 3:05-3:30pm | Hands-on `caret` workflow with the TB NanoString data |
