# efficient-ml-practice

효율적 딥러닝(신경망 양자화 등) 실습 노트북 모음. Google Colab에서 바로 실행할 수 있습니다.

공통 흐름: 파이토치로 MNIST를 MLP로 학습 → 가중치를 **safetensors**로 저장/로드 → 가중치 분포 히스토그램 → 해당 방식으로 양자화 → 비트 수별 정확도 비교.

## 노트북

| 노트북 | 내용 | 열기 |
|---|---|---|
| [`notebooks/kmeans-quantization.ipynb`](notebooks/kmeans-quantization.ipynb) | **K-Means 양자화** (scikit-learn, 비균등) — 비슷한 값을 대표값으로 묶기 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/warpspaceinc/efficient-ml-practice/blob/main/notebooks/kmeans-quantization.ipynb) |
| [`notebooks/linear-quantization.ipynb`](notebooks/linear-quantization.ipynb) | **Linear 양자화** (torch.fake_quantize, 균등) — 아핀 매핑 r = S(q − Z) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/warpspaceinc/efficient-ml-practice/blob/main/notebooks/linear-quantization.ipynb) |

> ⚠️ 이 저장소는 **비공개**입니다. Colab 배지로 열려면 저장소 접근 권한이 있는 계정으로 GitHub 연동(Colab → GitHub 탭에서 `warpspaceinc` 접근 허용)이 필요합니다. 권한이 없으면 노트북 파일을 내려받아 Colab에 업로드해 실행하세요.
