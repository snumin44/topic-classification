# 📰 Topic Classification with Different Approaches

__Topic Classification__ 을 다음과 같은 다양한 방법론으로 해결합니다.

1. Classification
2. Masked Language Modeling (MLM)
3. Matching
4. Seq2Seq

```
■ 프로젝트 요약
 
- 목표: Sequence Classification 을 해결할 수 있는 다양한 방법론 탐색 및 구현
- 팀원: 개인 프로젝트
- 언어: Python3
- 기술 스택: Pytorch, HuggingFace
```


## 1. Classification

- Classifier를 이용해 사전학습모델(PLM)을 Fine-tuning 하는 방법입니다.
- 일반적으로 Classification 테스크에서 사용되는 방법입니다. 


## 2. Masked Language Modeling (MLM)

- MLM Head를 이용해 프롬프트의 [MASK] 토큰을 예측하는 방법입니다.
- Verbalizer를 통해 예측한 토큰과 레이블을 연결합니다.    

## 3. Matching

- 텍스트와 레이블 사이의 함의(Entaliment) 여부를 예측하는 방법입니다.
- 다중 분류 테스크를 이진 분류 테스크로 전환해 해결합니다. 

## 4. Seq2Seq

- 인코더 모델이 아닌 Seq2Seq 모델을 이용해 분류 테스크를 해결합니다. 
- 분류 테스크를 생성 테스크로 전환해 해결합니다. 

