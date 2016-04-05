# word_embedding_cnn
Sentiment analysis system using a cnn and word embeddings as input

* uses kaggle challenge's sentiment analysis data from rotten tomatoes

**to set up:**
```
sudo apt-get install python-numpy python-scipy python-dev python-pip python-nose g++ libopenblas-dev git
sudo pip install Theano
sudo apt-get install python-pandas
sudo apt-get install python-numpy
```
**to run:**
```
python process_data.py <path to word vectors>
THEANO_FLAGS=mode=FAST_RUN,device=cpu,floatX=float32 python conv_net_sentence.py -static -word2vec
```
