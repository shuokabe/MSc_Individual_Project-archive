# Presentation

This deepQuest-mod folder contains all the files that were added or modified from deepQuest to make neural-based Multimodal Quality Estimation possible.

- model_zoo is a modified version of the original deepQuest's model_zoo file. It contains the new MQE models EncSentVis and EncDocVis for respectively sentence and document-level QE.

- prepare_data is a modified version of the original deepQuest's prepare_data file. It enables to handle the new visual feature input correctly.

- launch.sh and sent-launch.sh are shell files which make easier the move of the concerned dataset
