# efficient-ml-practice

효율적 딥러닝(신경망 양자화 등) 실습 노트북 모음. Google Colab에서 바로 실행할 수 있습니다.

## 노트북

| 노트북 | 내용 | 열기 |
|---|---|---|
| [`notebooks/kmeans-quantization.ipynb`](notebooks/kmeans-quantization.ipynb) | **K-Means 양자화** (scikit-learn, 비균등) — 비슷한 값을 대표값으로 묶기 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/warpspaceinc/efficient-ml-practice/blob/main/notebooks/kmeans-quantization.ipynb) |
| [`notebooks/linear-quantization.ipynb`](notebooks/linear-quantization.ipynb) | **Linear 양자화** (torch.fake_quantize, 균등) — 아핀 매핑 r = S(q − Z) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/warpspaceinc/efficient-ml-practice/blob/main/notebooks/linear-quantization.ipynb) |

위 **Open in Colab** 배지를 누르면 Colab에서 바로 열립니다. 별도 설치 없이 상단부터 순서대로 실행하면 됩니다 (런타임 → 모두 실행).
