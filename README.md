# CommonsenseQA의 오답 유형 분석: Unified-QA 모델을 중심으로

## 1. 연구목적 
Talmor et al.(2019)에서 제시된 commonsenseQA의 low accuracy 항목에 대해 unified-QA 모델에서 얼마나 개선되었는지 확인하고, 오류의 경향을 분석하여 commonsenseQA 모델이 가지는 취약점과 앞으로의 연구가 신경써야 할 과제를 제언한다.
2. 연구방법
1) Dataset: Talmor et al.(2019)에서 사용된 development data set(총 1221개의 질문)에서 100개의 질문을 randomly sample
2) Tool: Google Colab
3) Khashabi et al.(2020)에서 소개된 unified-QA 모델 (unifiedQA-v2-t5-large-1251000)에 test input으로 제공하여 결과를 확인, 오답 항목을 manually inspect하여 각 항목이 어떤 오답 유형에 속하는지 분류하고 빈도를 계산
4. 코드 실행 방법
  FinalCode.ipynb를 Google Colab 또는 Anaconda 등의 Notebook에서 실행
