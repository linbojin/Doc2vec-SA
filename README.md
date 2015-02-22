# dv4sa
Sentiment Analysis Based On Combining Term Weighting Scheme And Word Vectors

version 1.0.0:
+ average feature vectors
+ tf-idf feature vectors
+ credibility adjustment tf-idf feature vectors
+ bag of centroids feature vectors

verison 1.1.0:<br/>
for PL-sent dataset
+ bag of words sklearn        77.1%
+ tf-idf-uni                  77.2%
+ cre-tfidf-uni               77.5%
+ word vecs ave scheme        77.3%
+ word vecs tf-idf scheme     77.2%
+ word vecs cre tf-idf scheme 76.9% (c=0.1)
+ word vecs bag of centroids  75.3% (c=0.1)


Usage:<br/>
Install [Anaconda](http://continuum.io/downloads) <br/>
$ wget http://09c8d0b2229f813c1b93-c95ac804525aac4b6dba79b00b39d1d3.r79.cf1.rackcdn.com/Anaconda-2.1.0-Linux-x86_64.sh <br/>
$ bash Anaconda-2.1.0-Linux-x86_64.sh

./run.sh