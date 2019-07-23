# entity_based_sentiment_analysis

## Description
given unstructured discussion data, get main entity of discussion. and find sentiments of those entity.

## Requirements
* suggestion : just run each cell and install dependency packages.
* get pretrained wordvectors(glove.6B.50d.txt) and keep in pretrained-word-vectors directory.
* git clone https://github.com/yizhongw/StageDP.git in root directory.
* get stanford corenlp in root directory. change path accordingly wherever required.

## Execution steps.

* entity_cluster.ipynb  --> to get entity related data.
* sent_classfy_gensim_logit.ipynb --> pass above entity related data to sentiment api.
