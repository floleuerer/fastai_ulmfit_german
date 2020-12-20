# ULMFiT German with SentencePiece

Based on https://github.com/fastai/course-nlp/blob/master/nn-turkish.ipynb and ported to fastai2

## Notebooks

01 + 02) Prepare Wiki  
03) Train a German LM with SentencePiece tokenizer from scratch on Wikipedia  
04) Fine Tune LM on domain corpus   
05) Train classifier on fine tuned model  

13-15) Same as notebooks 03-05 but with 15k vocab size

## Pretrained weights

### AWD_LSTM Sentencepiece 30k vocab

Trained with Notebook 03  
Model: http://meansqua.red/files/de_ulmfit/30k/de_wikitext.pth  
Vocab: http://meansqua.red/files/de_ulmfit/30k/de_wikitext_vocab.pkl  

### AWD_LSTM Sentencepiece 15k vocab

Trained with Notebook 13  
Model: http://meansqua.red/files/de_ulmfit/15k/de_wikitext.pth  
Vocab: http://meansqua.red/files/de_ulmfit/15k/de_wikitext_vocab.pkl  