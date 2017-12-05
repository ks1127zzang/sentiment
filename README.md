# Sentiment Analysis Experiments

This repository contains experiments in Vietnamese sentiment analysis problems. It is a part of [underthesea](https://github.com/magizbox/underthesea) project.

# Results

![](https://img.shields.io/badge/F1-0.46-red.svg)

| Model             | F1   |
|-------------------|------|
| SVM + ngrams(1,3) | 0.46 |

# Reproduce

Setup Environment

```
# clone project
$ git clone https://github.com/undertheseanlp/sentiment

# create environment
$ cd sentiment
$ conda create -n sentiment python=3.5
$ pip install -r requirements.txt
$ pip install git+https://github.com/undertheseanlp/languageflow
```

# Related Works

* Vietnamese Sentiment Analysis publications, [link](https://github.com/magizbox/underthesea/wiki/Vietnamese-NLP-Publications#sentiment-analysis)
