# :earth_africa: Neural_Machine_Translation_Tensorflow
Implementation of a NMT model using the latest version of tensorflow. \
The model translates from english to german. :uk: :arrow_right: :de:

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









