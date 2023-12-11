# Daegu-Traffic-Accident-Damage-Prediction-AI-Competition  
Dacon_AI_Competition  
  
### 외부데이터(활용방법)
-https://www.data.go.kr/data/15075668/fileData.do#layer_data_infom(공공데이터포털)로 들어간다.  
-http://taas.koroad.or.kr/gis/mcm/mcl/initMap.do?menuId=GIS_GMP_STS_RSN 데이터 출처로 들어간다.  
-사고년도를 2019년 이전, 시도를 대구광역시, 시군구를 전체로 설정하여 csv파일로 다운받는다.(2007년~2018년)  
-기존 train.csv와 합하여 훈련 및 검증 데이터 셋으로 활용한다.  
  
  
### 코드파일 실행순서  
1. COLAB_FINAL.ipynb 실행  
2. LOCAL_FINAL.ipynb 실행(1번을 통해 얻은 submission을 다운받은 후 로컬 코드상 알맞은 경로에 옮겨놓은 뒤 실행) > 최종 csv 파일  
