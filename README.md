# Multi-label Text Classification

Holds code for collecting data from arXiv to build a multi-label text classification dataset and a simpler classifier on
top of that. Our dataset is now [available on Kaggle](https://www.kaggle.com/spsayakpaul/arxiv-paper-abstracts). The dataset collection process
has been shown in [this notebook](https://github.com/soumik12345/multi-label-text-classification/blob/master/beam_arxiv_scrape.ipynb). We hope
it will be a useful benchmark for building multi-label text classification systems.

Here's an accompanying blog post on keras.io discussing the motivation behind this dataset, building a simple
baseline model, etc.: [Large-scale multi-label text classification](https://keras.io/examples/nlp/multi_label_classification/).

## Acknowledgements

We would like to thank [Matt Watson](https://github.com/mattdangerw) for helping us build the simple baseline classifier model. Thanks to
[Lukas Schwab](https://github.com/lukasschwab) (author of [`arxiv.py`](https://github.com/lukasschwab/arxiv.py) for helping us build
our initial data collection utilities. Thanks to [Robert Bradshaw](https://www.linkedin.com/in/robert-bradshaw-1b48a07/) for his inputs
on the Apache Beam pipeline. Thanks to the [ML-GDE program](https://developers.google.com/programs/experts/) for providing GCP credits
that allowed us to run the Beam pipeline at scale on Dataflow.
