# Chinese POS Tagging

## Intro

A PyTorch implementation of Chinese Part-of-Speech tagging with with [Huggingface Transformers](https://github.com/huggingface/transformers)

## Model Descriptions

Model is based on Pretrained [Albert Model](https://github.com/google-research/albert) and CRF layer

Use [BERT chinese tokenizer](https://github.com/google-research/bert) for chinese tokenization 

## Training Curve

<p align="center">
<img src="/README/loss.png" height="400">
</p>



## Data Preprocess
- Use MONPA and CKIP pos tagging toolkit for pre tagging
- Training Dataset (News articles & PTT articles) 
    - CNA News