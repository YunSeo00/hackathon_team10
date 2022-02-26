## 코드 공유 게시판입니다.


- preprocessing.ipynb : 데이터를 살펴보고 임베딩 작업을 위해 딥러닝 모델을 돌려본 코드
- onehotencoding.ipynb: 원핫인코딩된 데이터를 생성하는 코드
  - [train_data_onehot_origin.csv](https://drive.google.com/file/d/1OU5ton-1ljWyCXtm4G4xBXzntkkWxcEj/view?usp=sharing)
  - [test_data_onehot_origin.csv](https://drive.google.com/file/d/1C0C3E701o4JQXP5o9ISk1B-4NO2brpMI/view?usp=sharing)
- embedding.ipynb : 임베딩 벡터를 생성하는 코드 (vector길이가 너무 길어서인지 저장 불가)
- 4model.ipynb : i,e / n,s / t,f / p,j 를 각각 예측한 뒤 결과를 합치는 방식
  - 이 방법은 각 4개의 지표가 독립이라는 가정하에 실행하는 방식이라 함.
  - 하지만 이 모델의 결과는 전체를 한 번에 예측했을 때보다 성능이 더 낮음.
  - 따라서 각 지표가 독립이 아닐 것이라 예상됨.  
- validation_code.ipynb : 검증데이터에서 데이터 증식, tf-idf vector 생성, 최종 모델 적합한 코드
- Final_code_team10.ipynb : 최종 데이터 예측 코드
