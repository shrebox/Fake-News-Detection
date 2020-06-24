Checkout the code [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/shrebox/Fake-News-Detection/blob/master/Fake_News_Detection_LIARv2.ipynb)

Detailed analysis: [*Report_Fake_News_Detection_NUS.pdf*](https://github.com/shrebox/Fake-News-Detection/blob/master/Report_Fake_News_Detection_NUS.pdf)

# Fake-News-Detection

Refer to this paper: ​https://aclweb.org/anthology/W18-5513​.

● Dataset download link: ​https://github.com/Tariq60/LIAR-PLUS/tree/master/dataset

● An earlier version of the dataset appeared in this paper:
https://arxiv.org/pdf/1705.00648.pdf​.

● Earlier Dataset can be downloaded from:
​https://github.com/thiagorainmaker77/liar_dataset​.

LIAR-PLUS is a benchmark dataset for fake news detection, released recently. This dataset
has evidence sentences extracted automatically from the full-text verdict report written by
journalists in Politifact. It consists of 12,836 short statements taken from POLITIFACT and
labeled by humans for truthfulness, subject, context/venue, speaker, state, party, and prior
history. For truthfulness, the LIAR dataset has six labels: pants-fire, false, mostly-false,
half-true, mostly-true, and true. These six label sets are relatively balanced in size.

There are two tasks:
1. Binary classification task (true, false)
2. Six-way classification task (pants on fire, false, mostly false, half-true, mostly true, true)
Your task is to select a classifier (or a group of classifiers) that you think is suitable for this
dataset and get the highest possible accuracy. You can choose different classifiers for the
two tasks. You are free to use any ideas you think will be suitable for this dataset. For
example, you may plot graphs for gaining insights about the features or clean/re-organise
the data for feature extraction.

**Code file**: *Fake_News_Detection_LIARv2.ipynb*

**Analysis Report**: *Report_Fake_News_Detection_NUS.pdf*

