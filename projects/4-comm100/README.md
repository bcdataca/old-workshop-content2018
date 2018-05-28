# Determining intent and automating knowledge base creation from live chat transcripts

**Hosted by:** Comm100  
**Mentors:** David Carlson and Kevin Gao

## Goal

The goals for this challenge can be comprised as follows. 
1. Cluster or Correlate chat sessions:
    * Build an algorithm or methodology to cluster or correlate similar issues
      across chat sessions defined by you
2. We have a Knowledge Base (KB) tool but it is manual work on the client side
   to create Q&A’s. Is there a way to progress towards full automation in
   building a Knowledge Base with what’s already there?
    * Build a KB comprised of questions and their corresponding answers in an
      automated way.

In essence, the challenge for participants is to develop a mathematical model
for determining intent [of the client, based on their chat messages], and to
develop a tool that can be used to repeat that process with new data sets (i.e.,
the tool should be robust, generalizable, extensible).


For more information on this project, please visit the
[project page](http://workshop.bcdata.ca/2018/project/project-4/) online.


## Data team notes

Users who are familiar with computational linguistics and its tools (*e.g.,*
[`nltk`](https://www.nltk.org/)), or who are comfortable analyzing large amounts
of text data will be well-suited for tackling this project. We anticipate that
familiarity with topic models and related machine learning tools would be a
bonus.


### Resource crumbs

* [Reasoning with Neural Tensor Networks for Knowledge Base Completion](https://nlp.stanford.edu/pubs/SocherChenManningNg_NIPS2013.pdf); or [see here](https://github.com/GauravBh1010tt/DeepLearn?utm_source=mybridge&utm_medium=blog&utm_campaign=read_more) for a repository from which that was pulled. 
* Tutorial for
  [creating a chat bot](https://www.youtube.com/watch?v=dvOnYLDg8_Y) with deep
  learning and tensorflow in Python
* [PyTextRank](https://medium.com/@aneesha/beyond-bag-of-words-using-pytextrank-to-find-phrases-and-summarize-text-f736fa3773c5)
* [GluonNLP](https://github.com/dmlc/gluon-nlp?utm_source=mybridge&utm_medium=blog&utm_campaign=read_more) "is a toolkit that enables easy text preprocessing, datasets loading and neural models building to help you speed up your Natural Language Processing (NLP) research". 
