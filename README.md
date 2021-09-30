# Multi-label Text Classification

Holds code for collecting data from arXiv to build a multi-label text classification dataset and a simpler classifier on
top of that. Our dataset is now [available on Kaggle](https://www.kaggle.com/spsayakpaul/arxiv-paper-abstracts). We hope
it will be a useful benchmark for building multi-label text classification systems. Currently,
we are working on a pipeline to collect an even bigger dataset. 

Here's an accompanying blog post on keras.io discussing the motivation behind using this dataset, commentaries on the
techniques used to build the simple classifier, etc.: [Large-scale multi-label text classification](https://keras.io/examples/nlp/multi_label_classification/).


## Acknowledgements

We would like to thank [Matt Watson](https://github.com/mattdangerw) for helping us build the simple baseline classifier model. Thanks to
[Lukas Schwab](https://github.com/lukasschwab) (author of [`arxiv.py`](https://github.com/lukasschwab/arxiv.py) for helping us build
our initial data collection utilities. 
