# NLP study

## week1
- LM/HMM/CRF

## week2

### LM
- 단어 희소성을 대체하기 위한 일반화 방법
- Kneser-Ney  디스카운팅
- Interpolation
- Back-off
- 언어 모델 평가 방법: perplexity
- [RNNLM](https://wikidocs.net/46496)
- [CLM : Conditional Language Model](https://www.cl.cam.ac.uk/teaching/1718/R228/lectures/lec9.pdf)


### HMM
- [참고 사이트1 : CMU-lecture](http://www.cs.cmu.edu/~10715-f18/lectures/lecture2-crf.pdf)
- [참고 사이트2 : 블로그](https://www.quantumdl.com/entry/Endtoend-Sequence-Labeling-via-Bidirectional-LSTMCNNsCRF)
- [참고 사이트3](https://towardsdatascience.com/implementing-a-linear-chain-conditional-random-field-crf-in-pytorch-16b0b9c4b4ea)
- Evaluation Problem → forward algorithm (DP)
- Decoding Problem → HMM 핵심 (viterbi)
- Learning Problem → MLE(maximum likelihood method)
  - MLE (Maximum Likelihood Estimation) vs. 베이즈 정리
- EM(Expectation-Maximization) 알고리즘
- Labeling Bias


### MEMM
- [참고 사이트1: 블로그](https://ratsgo.github.io/machine%20learning/2017/11/04/MEMMs/)

### CRF

### BERT
- https://docs.nvidia.com/deeplearning/nemo/user-guide/docs/zh/latest/nlp/bert_pretraining.html
- https://codlingual.tistory.com/98
- https://github.com/Meelfy/pytorch_pretrained_BERT
