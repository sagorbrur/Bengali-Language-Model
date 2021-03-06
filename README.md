# Bengali Language Model
Bengali Language model is a language model build with fast ai's [ULMFit](https://arxiv.org/abs/1801.06146)

NB: **This repository mostly followed [fastai-ulmfit](https://github.com/fastai/fastai/blob/master/examples/ULMFit.ipynb) and [nlp-for-bengali](https://github.com/goru001/nlp-for-bengali) repository**


# Dependencies
* python 3
* fastai
* pytorch 1.1.0(gpu)
* sentencepiece

# Dataset
* Bengali Wikipedia Dump Dataset
* Crawl News Article
## Data Format

```
- data
  - train
    - article1.txt
    - article2.txt
    ..............
    - articlen.txt
  - valid
    - val_article1.txt
    - val_article2.txt
    ..................
    - val_articlen.txt
    
```

# Evaluation Results

## Language Model
* Accuracy: 48.26% on validation dataset
* Perplexity of Language Model is: ~22.79

## Pretrained model and Prediction
* **Check [bnlm](https://github.com/sagorbrur/bnlm) for detail Prediction**
* [Pretrained Language Model](https://drive.google.com/open?id=1wuI285FVB5X61GL8BaRY3u_oBCqiuKrC)
* [Pretrained Sentencepiece Model](https://github.com/sagorbrur/bnlp/blob/master/model/bn_spm.model)


