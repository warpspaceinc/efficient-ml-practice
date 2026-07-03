# efficient-ml-practice

효율적 딥러닝(신경망 양자화 등) 실습 노트북 모음. Google Colab에서 바로 실행할 수 있습니다.

## 노트북

| 노트북 | 내용 |
|---|---|
| [`notebooks/mnist-mlp-quantization.ipynb`](notebooks/mnist-mlp-quantization.ipynb) | 파이토치로 MNIST를 MLP로 학습 → 가중치를 **safetensors**로 저장/로드 → 가중치 분포 히스토그램 → **K-Means**·**Linear** 두 방식으로 양자화하고 비트 수별 정확도 비교 |

## Colab에서 열기

이 저장소는 **비공개**입니다. Colab에서 열려면 저장소 접근 권한이 있는 계정으로 GitHub 연동을 허용한 뒤 아래 형식의 URL을 사용하세요.

```
https://colab.research.google.com/github/warpspaceinc/efficient-ml-practice/blob/main/notebooks/mnist-mlp-quantization.ipynb
```

또는 노트북 파일을 내려받아 Colab에 업로드해도 됩니다.

## 관련 글

- [딥러닝 시대의 데이터타입](https://ho4040.github.io/ko/posts/numeric-data-types/)
- [가중치를 공유해서 모델 줄이기 — K-Means 기반 양자화](https://ho4040.github.io/ko/posts/kmeans-weight-quantization/)
- [정수 연산만으로 신경망 추론하기 — Linear Quantization](https://ho4040.github.io/ko/posts/linear-quantization/)
