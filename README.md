

# 프로젝트

# 자동차 분류
- 데이터 수집, 전이학습, Fine Tuning
- 시중에 판매하는 5개의 국내 차량 브랜드를 기준으로 이미지 데이터를 수집. 기아, 현대, 르노 삼성, 쌍용, 제네시스로 구성된 5개 브랜드의 차종을 Selenium을 활용해 구글 이미지에 검색하고 나오는 차량 이미지 데이터를 수집 후 기본 CNN 모델을 만든 후 결과를 보고 전이학습 및 Fine Tuning 을 진행에 결과를 확인하고 이미지가 잘 정제 및 라벨링이 잘되어있는 케글에 있는 데이터 셋을 활용하여 검증하였습니다.
- 이슈
- 이미지를 많이 수집할수 없었음
- 해결방법
- 이미지 제네레이터를 통해 이미지 증강
- 이슈 
- 컴퓨터 사양이 좋지않아 모델을 무겁게 돌릴수 없었음
자세한 내용과 코드는 블르그와 깃 자동차분류에 있습니다!
- https://waste-of-movement.tistory.com/4

-
# 자연재난
- 기상청 데이터를 이용하여 자연재난(폭염,한파,호우,대설)등을 분석 및 예측하였습니다.
- 이슈 
- 2011년~ 2022년의 90개 이상의 지역 기후 데이터를 받아왔으나 결측치있는 데이터 들이 굉장히 많았음
- 결측치를 해결할수있는 데이터는 그대로 가지겨가고 할수없는부분은 버렸음 
- 일짜 데이터가아니라 시간데이터로 활용을했다면 좀더 좋은 예측값을 얻을수 있을거라 판단
장고와 AWS 이용해 홈페이지 배포
www.weatherdata.shop
코드와 자세한 내용은 블로그에 있습니다!
- https://waste-of-movement.tistory.com/10
# 대중교통 시각화
- 서울 대중교통 시각화
- 많은 사람들이 대중교통을 이용하고 있습니다. 서울시 주민등록인구 9백 5십만명인 점을 고려하여 매일 대중교통을 이용하난 사람들 규모, 시간대, 지역, 시간에 따른 특징 분석 ex) 퇴근 후 가장 많이 하차한 지역의 특정, 월별 승차,하차 인원의 특징 등의 대중교통 시각화를 해보았습니다.
- 이슈
버스 같은경우 시도군구 별로 나누기에는 정류장수가 매우 많아 힘들었습니다. 또한 데이터셋에 서울 이외에 즉 경기도에서 서울 로 출퇴근하는 사람들의 부분을 분석하기에는 무리
자세한 내용은 및 블로그와 코드는 깃 대중교통 폴더에있습니다.
-https://waste-of-movement.tistory.com/2

# 기술스택
Python
- 기본 문법 구조 및 라이브러리 숙지
- 조건문, 반복문, 함수, 클래스 작성 가능
- 크롤링, API Json 파싱 가능
- Jupyer Notebook, 파이참, Google Colab 환경 이용

데이터 분석 및 시각화 
- Numpy, Pandas, Dataframe 활용 가능
- 데이터 전처리 및 EDA 가능
- Matplotib, Seaborn 과 같은 차트 그리는 도구 사용 

Django, AWS , Mysql, Docker
 Mysql 기본적인 문법 밑 스키마 생성 가능
 Mysql, Django, AWS, Docker 를 활용하여 배포 경험 있음
 
머신러닝
- scikit-learn 기능 숙지
- 지도학습, 비지도학습, 앙상블, 알고리즘 사용
지도) KNN, Liner Regression, Logistic Regression, SVM, Tree 비지도) K-mean, DBSCAN 앙상블) Xgboost, LightFBM, Voting
- GridSearchCV로 효율적인 하이퍼 파라미터 튜닝 가능

딥러닝
- Tensorflow 활용하여 기본적인 CNN 구현 가능
- YOLO 활용 경험 있음
- RNN, LSTM 같은 시계열 모델 구축 경험
- GAN 체험
