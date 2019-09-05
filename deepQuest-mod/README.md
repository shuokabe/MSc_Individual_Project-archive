# Presentation

This deepQuest-mod folder contains all the files that were added or modified from deepQuest to make neural-based Multimodal Quality Estimation possible.

- model_zoo is a modified version of the original deepQuest's model_zoo file. It contains the new MQE models EncSentVis and EncDocVis for respectively sentence and document-level QE.

- prepare_data is a modified version of the original deepQuest's prepare_data file. It enables to handle the new visual feature input correctly.

- launch.sh and sent-launch.sh are shell files which make easier the move of the concerned dataset

- The train-shell folder contains the shell scripts to execute the training and testing with the desired MQE model.

- The config folder contains the different configuration files for the baseline and its modified MQE version for sentence-level and document-level neural-based approaches.
