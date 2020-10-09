# Chinese POS Tagging

## Intro

- A PyTorch implementation of Chinese Part-of-Speech tagging with with [Huggingface Transformers](https://github.com/huggingface/transformers)


- Model is based on Pretrained [Chinese Albert Model](https://github.com/brightmart/albert_zh) and CRF layer

- Use [BERT chinese tokenizer](https://github.com/google-research/bert) for chinese tokenization 

- Combine CrossEntropyLoss and CRFLoss with fixed weight to do multitask training (CE : 1.0, CTC : 1e-2)

### Data Preprocess
- Use MONPA and CKIP pos tagging toolkit for pre tagging
- Training Dataset (News articles & PTT articles) 
    - CNA News

## Training Curve

<p align="center">
<img src="/README/loss.png" height="400">
</p>



## Demo website

[http://goodweather.ml/](http://goodweather.ml/)


## Examples

<p align="center">
<img src="/README/example_1.png" height="500">
</p>