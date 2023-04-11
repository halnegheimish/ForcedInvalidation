# Forced Invalidation

This repository contains code and data for the paper "Towards preserving word order importance through Forced Invalidation", presented at EACL2023.

## Abstract
Large pre-trained language models such as BERT have been widely used as a framework for natural language understanding (NLU) tasks. However, recent findings have revealed that pre-trained language models are insensitive to word order. The performance on NLU tasks remains unchanged even after randomly permuting the word of a sentence, where crucial syntactic information is destroyed. To help preserve the importance of word order, we propose a simple approach called Forced Invalidation (FI): forcing the model to identify permuted sequences as invalid samples. We perform an extensive evaluation of our approach on various English NLU and QA based tasks over BERT-based and attention-based models over word embeddings. Our experiments demonstrate that Forced Invalidation significantly improves the sensitivity of the models to word order.

## Usage
### Data
The data used in this study is available at data/.

### Code
The code used in this study is available at notebooks/. It includes the training of the models, data processing, and evaluation scripts.

## Acknowledgements
The original datasets used were downloaded from the following sources:

https://ai2-public-datasets.s3.amazonaws.com/drop/drop_dataset.zip<br/>
https://github.com/allenai/contrast-sets/tree/main/DROP<br/>
https://huggingface.co/datasets/glue/viewer/cola/train<br/>
https://huggingface.co/datasets/glue/viewer/mnli/train<br/>
https://huggingface.co/datasets/glue/viewer/rte/train<br/>
https://huggingface.co/datasets/swag
