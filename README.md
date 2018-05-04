# Neural_Machine_Translation_Tensorflow
:earth_africa: Implementation of a NMT model using the latest version of tensorflow. \
The model translates from english to german.

## Prerequisites
- Tensorflow 1.8
- Nltk
- Numpy
- Pandas

## Dataset
European Parliament Proceedings Parallel Corpus 1996-2011 - German_to_English
http://www.statmt.org/wmt16/translation-task.html \
http://www.statmt.org/wmt16/translation-task.html

## Code
3x .py files:
  - model class + necessary for preprocessing and training 
 
1x Jupyter Notebook:
  - shows the results of using the network

## Architecture
**Sequence2Sequence Model.**
- Bidirectional RNN (LSTM or GRU)
- Bahdanau Attention
- Adam Optimizer
- Beam Search or Greedy Decoding

## Some Results
'''
Actual Text:
resumption of the session

Actual translation:
wiederaufnahme der sitzungsperiode

Created translation:
wiederaufnahme der sitzungsperiode



Actual Text: 
( the house rose and observed a minute ' s silence )

Actual translation:
( das parlament erhebt sich zu einer schweigeminute . )

Created translation:
( das parlament erhebt der einer einer schweigeminute . )



Actual Text:
madam president , on a point of order .

Actual translation:
frau präsidentin , zur geschäftsordnung .

Created translation:
frau präsidentin , zur geschäftsordnung .
'''







