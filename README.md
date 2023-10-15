# LDAPrototype
## Library versions
R version used  - 4.2.0

rpy2 version - 3.5.13

Python version - 3.8.17

import_ipynb version - 0.1.4


# R script used
```
library("ldaPrototype")
data(reuters_docs)
data(reuters_vocab)
res = LDARep(docs = reuters_docs, vocab = reuters_vocab, n = 4, K = 10, num.iterations = 30, seeds = 1:4)
topics = mergeTopics(res, vocab = reuters_vocab)
```
