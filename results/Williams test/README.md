# Williams test

This folder contains the results of the Williams tests for different settings.

- The `Pred wrapper [setting].ipynb` Jupyter notebook files contain the predictions for all tested models and group them into a data file in a specific format for the Williams test.

- The different folders contain the files from https://github.com/ygraham/mt-qe-eval, where the file and model names are modified for each case.
  - The `[setting]-pred.csv` file is the prediction data created with the corresponding `Pred wrapper [setting].ipynb` file.
  - The `metrics.[setting]` file contains the name of the models (sorted) tested in the Williams test.
  - The `pearons-sig-[setting].R` file contains the R code to compute the Williams test.
  - The `[setting]-pred-pearson-sig.csv` file is the result of the Williams test.

- The `Correlation graph.ipynb` Jupyter notebook uses the results from the Williams test (`[setting]-pred-pearson-sig.csv`) to compute the correlation matrix with a heatmap.

- The `Examples-in-data.ipynb` file computes the predictions for different models on some hand-picked examples in the dataset.
