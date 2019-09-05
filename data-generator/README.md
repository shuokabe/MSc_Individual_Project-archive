# Presentation

This data-generator folder contains three Jupyter notebooks (in Python 3), which aim to generate the data used in this project.

- Concatenated_text transforms the raw WMT 2018 task 4 data into files in the input format for document QE in deepQuest (e.g. train.src, train.mt, train.mqm).
The raw data, which contains one folder per document, is transformed into three files: one for the source text, one for the target Machine Translation and one for the QE score.

- Token_concatenated_text creates the token version of the dataset by adding sub-category information at the beginning of the source input.

- Visual_data creates the .vis files for deepQuest, which contains the visual features for the documents in the data. One line represents one document and contains a dense vector with 4,096 elements.
