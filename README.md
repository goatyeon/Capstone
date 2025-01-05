# 고해상도 위성영상과 지상관측 데이터를 활용한 대기오염 지도 구축 및 서비스 개발 🌍

## 프로젝트 개요

대기오염 문제는 환경과 건강에 심각한 영향을 미칩니다. 하지만 현장 관측소가 없는 지역의 미세먼지 농도 예측은 제한적입니다.  
이 프로젝트는 **Sentinel-2 위성영상**과 **AirKorea 대기질 데이터**를 활용하여 **기계학습 기반 대기오염 예측 모델**을 개발하고,  
미세먼지 농도를 시각화하는 **정밀 지도 서비스**를 제공하는 것을 목표로 합니다.

---

## 주요 기능

- **대기오염 예측 모델 개발**  
  - 기계학습 알고리즘(RF, LGBM, XGBoost, DNN)을 활용하여 고해상도 예측 수행
  - 데이터 부족 지역(북한 등)에서도 신뢰성 있는 예측 가능

- **미세먼지 지도 시각화**  
  - 사용자 친화적인 인터페이스로 대기질 상태를 지도에 표현
  - 정책 결정 및 환경 관리에 활용 가능

- **지속적인 확장 가능성**  
  - 북한을 포함한 한반도 전역 및 글로벌 대기질 예측 확장

---

## 기술 스택

- **데이터 소스**
  - Sentinel-2 위성영상
  - AirKorea 대기질 데이터
  - DEM(디지털 고도 모델) 및 기상 데이터

- **기계학습 및 분석**
  - Python: `sklearn`, `XGBoost`, `LightGBM`, `TensorFlow`
  - 데이터 전처리 및 결측값 처리

- **결과 시각화**
  - GIS 및 대기질 지도 생성 도구
  - Python: `matplotlib`, `seaborn`

---

## 기대 효과

- **정확한 대기오염 데이터 제공**  
  - 개인과 정부의 효과적인 대기질 관리 및 정책 수립 지원

- **데이터 부족 지역 적용 가능**  
  - 북한 및 전 세계의 데이터 부족 지역에서도 활용 가능한 모델 구축

- **환경 문제 해결 기여**  
  - 대기오염 저감 및 도시계획 지원을 통한 지속 가능한 환경 조성


