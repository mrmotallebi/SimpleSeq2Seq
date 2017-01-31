# Sequence To Sequence model for Chainer 

This repository is the implementation of simple seq2seq model (not containing attention system).

## Description

hoge

***DEMO:***

![Demo](https://github.com/OnizukaLab/SentimentAnalysis/blob/master/image/demo_test.png?raw=true)

## Features

- seq2seq
  - SequenceToSequenceを用いたChatBotの生成

## Requirement

- pyenv 
- anaconda3-2.4.0
- chainer (1.5 ~ latest?)
- gensim (Word2Vec) 

## Usage

1. Install cornell corpus into own your PC, and run cornell_corpus.py to make txt file (named pair_corpus.txt). 
2. Train the seq2seq model using its text.
3. Run interpreter.py to talk ChatBot trained by you.

## Installation

    $ git clone https://github.com/OnizukaLab/SimpleSeq2Seq.git


## Author

[@KChikai](https://github.com/KChikai)
