# HomePriceForecasting(Kaggle)

***

## 프로젝트 내용
광주광역시 스마트 미디어 인재개발원에서 빅데이터융합 SW개발자 과정 중 2차 프로젝트로 Kaggle 경진대회를 진행하였습니다. 머신러닝을 이용하여 주어진 데이터를 분석하여 가격을 예측하고 오차가 가장 적은 팀을 가려내는 대회였습니다. 이 프로젝트는 데이터분석으로 실행 시 순차적으로 결과물만 나옴으로 사용방법에는 큰 어려움이 없을 것입니다. 프로젝트의 순서는 아래와 같이 진행되었습니다.

### 머신러닝 프로세스

1. 문제정의
    + 회귀
    + 주택가격예측
    + 대회에서 높은 순위 차지
  
2. 데이터 수집
    + 스마트인재개발원 주관 Kaggle 주택가격예측대회 데이터 셋 활용
  
3. 데이터 전처리 및 탐색적 데이터 분석(EDA)
    + 결측치
    + 특성공학(스케일링, 인코딩, 변환 등)
    + 기술통계
    + 상관계수
    + 시각화
  
4. 모델선택, 학습 및 하이퍼파라미터 튜닝 
    + GradientBoosting
    + XGBRegressor
    + ElasticNet, Lasso
    + 3개의 모델 더한 후, 나누기
  
5. 모델 평가

## 프로젝트 정보

1. 설치
    + Jupiter Notebook(최신버전)
    
2. 사용방법
    + HomePrice.ipynb를 다운받습니다.
    + data라는 폴더를 만들어 test.csv, train.csv를 파일을 넣습니다.
    + test.csv, train.csv 파일의 위치는 변경되어도 되나, 정상적인 작동을 위해서는 HomePrice.ipynb안에 있는 코드를 수정해야합니다.
    
3. 필요 패키지
    + 대다수의 패키지는 import시 자동으로 연동이 됩니다만, 예외의 경우가 있으므로 패키지를 설치해야 할 경우가 있습니다.
    + Ex) !pip install optuna, !pip install catboost, !pip install lightgbm
    
4. 
    
