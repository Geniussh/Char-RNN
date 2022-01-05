## Recurrent Neural Networks as Character-level Language Models ##

Recurrent Neural Networks (RNNs) have been proved to be a powerful approach to character-level language models. 

Inspired by Andrej Karpathy's blog _[The Unreasonable Effectiveness of Recurrent Neural Networks](http://karpathy.github.io/2015/05/21/rnn-effectiveness/)_, I experimented three RNN architectures on 3 datasets while generating meaning results from the trained models.

### RNN Architectures ###
* [Vanilla RNN](https://pytorch.org/docs/master/generated/torch.nn.RNN.html)
* [GRU](https://pytorch.org/docs/master/generated/torch.nn.GRU.html)
* [LSTM](https://pytorch.org/docs/master/generated/torch.nn.LSTM.html)

### Datasets ###
* Shakespeare Text
* LaTeX files from [The Stacks Project](https://stacks.math.columbia.edu/ "The Stacks Project")
* Trump's Tweets @readldonaldtrump from [Kaggle](https://www.kaggle.com/austinreese/trump-tweets "Kaggle")
