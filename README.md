# Mimic Text Generator
Building some base markov chain based text generators in python and spark. Plan to use this to compare against deep learning approaches.


Currently has support for an ngram based model built in python and one built in pyspark. The API takes in a path of text files and will do basic tokenization on the documents and then feed that into the markov model.

Blog associated with this work
https://towardsdatascience.com/natural-language-generation-part-1-back-to-basics-2f0b2654624f
