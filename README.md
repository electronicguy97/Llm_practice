## LLM 만들기
[홍정모 연구소](https://honglab.co.kr/)의 LLM 만들기를 참고하였습니다.

### 목적
- LLM의 기본을 학습하며 하드웨어에 맞게 코드 변경 학습
### 환경 설정
- Python 3.10.16
- Pytorch 2.5.1+cu121
- transformers 4.39.3
- GPU 3060 * 2

#### 1.Pretraining.ipynb
- 현재 성능에 맞는 코드 변경 
- Validation 추가
- GPU분할
- AMP 등 기타 작업
  
#### 2.fullfinetuning1_base
- 양자화 진행

#### 3.fullfinetuning1_instruct
- LoRA 사용
