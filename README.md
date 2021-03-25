# Tampered_IMG_detection

 * Predictive Modeling : CASIA v2 데이터를 ELA(Error Level Analysis)로 전처리 한 후 EfﬁcientNetB0 로 모델링하고, 다시 distilled 하여 Model size 를 줄인 코드입니다.
 * 모델 크기와 상관 없이 성능이 중요한 경우, EfﬁcientNetB0 모델링 코드까지 가져가셔서 튜닝하면 됩니다. 
 * 모델 크기도 함께 볼 경우, Student model(MobileNetV2) 코드까지 봅니다. Teacher model 대비 Student model은 파라메터 수가 20,106,661개에서 3,538,984 개로 17.6% 의 크기로 줄어들었으나, 대신 성능이 AUC score 기준 92% 에서 70% 로 줄어들었습니다. 이 또한 추가 튜닝을 통해 향상시킬 수 있습니다. 
