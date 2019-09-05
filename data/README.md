# Presentation

This data folder contains the main used data, whether the raw data as given at the start (raw-data sub-folder) or the data created for this project.

In order to limit the file size, for the sentence-level biRNN data, the provided data will be a zip file of the main datasets. Indeed, the used data for this sub-task has been created and used in a similar way to the document-level biRNN dataset.

## Document-level biRNN dataset
- doc-qe-data-vis is a data generated for this project for the document-level QE biRNN sub-task, which contains the training, development and test datasets (source text, machine-translated text, visual features (used for MQE models) and MQM score).

- token-doc-qe-data-vis is the token version of doc-qe-data-vis, i.e. all the source texts contain the product's sub-category information at the beginning.

## Sentence-level biRNN dataset
- sentence-qe-data.zip is the equivalent of doc-qe-data-vis for sentence-level biRNN.

## Raw data
The raw-data folder contains the following elements:
- doc_level_training.tar.gz and doc_level_gold.zip: the raw WMT 2018 QE task 4 data (doc_level_gold contains the gold label (i.e. MQM score) for the test dataset).

- sentence-qe-train-dev.gz and sentence-qe-test.zip: the sentence-level version of the WMT 2018 task 4 data, provided by Dr Frédéric Blain.

- token data (folder): the datafile containing the document ID from the document-level datasets, the product ID, the title of the product, and the product's sub-category information.

- visual-features (folder): the datafile containing the document ID from the document-level datasets, the product ID, and the title of the product. By using the product ID, the visual features for the products can be found from an online heavy metadata file.

- quest_baseline: the original dataset for document-level QE used as the baseline for the WMT 2018 task 4.
