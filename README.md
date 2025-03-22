# SeQNRoN: Seq2Seq + Neuron

SeQNRoN은 97,000개의 입출력 데이터로 학습한 **Seq2Seq 기반의 NLP 모델**입니다. 이 모델은 개발이 중단되었으며 개인 또는 단체의 상업적 사용 또한 허용합니다.

## 특징
- **모델 아키텍쳐**: Seq2Seq(**GRU** / **어텐션 메커니즘 미포함**)
- **데이터셋**: 약 97,000개의 입출력 데이터(**한국어**)
- **주요 용도**:
  - 자연어 처리(NLP)
---
# 장단점

-**장점**: 
 1. **완전한 로컬 모델**입니다.
 2. 응답이 빠릅니다.

-**단점**:
 1. RNN 아키텍쳐 특성상 **대화 내용을 자주 잊어**버립니다.
 2. **어텐션 메커니즘이 포함되지 않았기 때문에** 출력값이 일관되지 않거나, 문맥이 맞지 않거나, 중간에 출력이 끊길 수 있습니다.


