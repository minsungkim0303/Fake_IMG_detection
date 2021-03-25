# Fake_IMG_detection

 * Predictive Modeling : CASIA v2 데이터를 ELA(Error Level Analysis)로 전처리 한 후 EfﬁcientNetB0 로 모델링하고, 다시 distilled 하여 Model size 를 줄인 코드입니다.
 * 모델 크기와 상관 없이 성능이 중요한 경우, EfﬁcientNetB0 모델링 코드까지만 봅니다. 성능 향상을 위해서는 추가 튜닝이 필요합니다. (현재 성능 AUC score 기준 약 93%)
 * 모델 크기도 함께 볼 경우, Student model(MobileNetV2) 코드까지 봅니다. Teacher model 대비 Student model은 파라메터 수가 20,106,661개에서 3,538,984 개로 17.6% 의 크기로 줄어들었으나, trade-off 로 성능이 AUC score 기준 93% 에서 70% 로 줄어들었습니다. 이 또한 성능향상을 위해서는 추가 튜닝이 필요합니다.  
