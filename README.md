# Capstone  
## 관측소가 없는 지역의 미세먼지를 위성영상으로 예측
<br>

### 2024년 12월 진행 상황
- 에어코리아 + 센티넬 데이터 매칭 코드 완성
- 특정 지역만 수행 완료
  (강릉, 경기-광주, 구미, 포항, 광주, 대구, 대전, 부산,  
   서울, 울산, 인천, 목포, 여수, 당진, 서산, 아산, 천안, 청주)

### 이후 해야하는 것
- 부족한 지역 데이터 다운로드
- 센티넬 전처리(밴드값 추출) 
- 모델 코드 구현 (lgbm, rf는 이미 있으니까 xgboost 파이프 라인 모델 만들면 좋을듯)
