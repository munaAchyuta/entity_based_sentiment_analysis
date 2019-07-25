# entity_based_sentiment_analysis

## Description
given unstructured discussion data, get main entity of discussion. and find sentiments or summarization of those entity.

## Requirements
* suggestion : just run each cell and install dependency packages.
* get pretrained wordvectors(glove.6B.50d.txt) and keep in pretrained-word-vectors directory.
* git clone https://github.com/yizhongw/StageDP.git in root directory.
* get stanford corenlp in root directory. change path accordingly wherever required.
* sentiment best result comes from using BERT. here huggingface pytorch-BERT code is used. so get repo and use notebook.

## data
* just shared sample data format inside datasets directory for sentiment classification. so user has to get it's own data similar to given format.

## Execution steps.

* entity_cluster.ipynb  --> to get entity related data.
* sent_classfy_gensim_logit.ipynb --> pass above entity related data to sentiment api.
* sent_classfy_bert_logit.ipynb --> pass above entity related data to sentiment api. (OR)

## Note
* these notebooks contains each dependency applications code. but not as a single ordered code. so user has to test each related cell one by one. for integration , user has to take cells from each notebook.
