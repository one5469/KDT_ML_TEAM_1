# 수면 데이터 분석 및 스트레스 수준 추정

Kaggle 수면 데이터를 활용한 4인 팀 프로젝트입니다. 수면·생활 습관 데이터를 탐색하고, 수면 시간과 수면의 질을 이용해 스트레스 수준을 추정하는 회귀 실험을 담당했습니다.

- 기간: 2024.03.07–2024.03.08
- 담당: 권혁원 / 데이터 분석, 모델 비교 및 추론 실험
- 데이터: Sleep Efficiency, Sleep Health and Lifestyle
- 기술: Python, pandas, Matplotlib, scikit-learn, joblib

## 담당 작업 및 구현

- 수면 효율, 수면 단계, 생활 습관 변수의 분포와 관계 탐색
- 수면 효율을 기준으로 한 분류 실험 및 수면 효율 회귀 실험
- 수면 시간·수면의 질을 입력으로, 스트레스 수준을 목표로 하는 회귀 모델 구성
- 선형 회귀, KNN, SVR, Random Forest, Gradient Boosting 등의 모델 비교
- KNN과 SVR의 주요 하이퍼파라미터 탐색
- Voting·Stacking 회귀 모델과 MSE·MAE 등 평가 지표 비교
- 학습 모델 저장 및 별도 입력을 이용한 추론 실험

## 주요 파일

| 파일 | 내용 |
| --- | --- |
| [sourceFile.ipynb](sourceFile.ipynb) | Sleep Efficiency 데이터 탐색 |
| [sourceFile2.ipynb](sourceFile2.ipynb) | 수면 효율 분류·회귀 실험 |
| [sourceFile3.ipynb](sourceFile3.ipynb) | 스트레스 수준 회귀 및 앙상블 실험 |
| [KHW_execute_model.ipynb](KHW_execute_model.ipynb) | 저장 모델의 추론 실험 |

이 문서는 개인 폴더의 수면 분석 작업을 설명합니다. 변수 간 관계는 해당 데이터에서 관찰한 통계적 관계입니다.
