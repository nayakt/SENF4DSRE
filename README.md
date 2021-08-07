This repository contains the source code of the paper "Improving Distantly Supervised Relation Extraction with Self-Ensemble Noise Filtering" published in RANLP 2021.

### Datasets ###

NYT dataset used for experiments in the paper can be downloaded from the following link:

https://drive.google.com/drive/folders/1zSlXoeppoNpihbN75JbxuqZWiiYbpCLM?usp=sharing

Download train.json, dev.json, test.json, relations.txt, w2v.txt

Each line in the '.json' files is one instance. It contains the sentence text, relation mentions and entity mentions. Fields are self explanatory.

### Requirements ###

1) python3.6
2) pytorch 1.7
3) CUDA 8.0

### How to run ###

python3.6 models.py source_dir target_dir model_id train/test

Use model_id as 1 for CNN, 2 for PCNN, 3 for EA and 4 for BGWA.



