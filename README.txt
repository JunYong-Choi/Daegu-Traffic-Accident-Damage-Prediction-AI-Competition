*외부데이터(활용방법)
-https://www.data.go.kr/data/15075668/fileData.do#layer_data_infom(공공데이터포털)로 들어간다.
-http://taas.koroad.or.kr/gis/mcm/mcl/initMap.do?menuId=GIS_GMP_STS_RSN 데이터 출처로 들어간다.
-사고년도를 2019년 이전, 시도를 대구광역시, 시군구를 전체로 설정한다.
-조건설정에서 사망사고,중상사고,경상사고,부상신고를 체크한다.
-데이터 검색 후 csv로 다운받는다.(2007년~2018년)
-기존 train.csv와 합하여 훈련 및 검증 데이터 셋으로 활용한다.

*코드파일 실행순서
1. COLAB_FINAL.ipynb 실행
2. LOCAL_FINAL.ipynb 실행(1번을 통해 얻은 submission과 2번을 실행시켜 얻은 예측값 앙상블)

*COLAB_FINAL상 변수
-additional_1 = 2016년~2018년 외부데이터
-additional_2 = 2013년~2015년 외부데이터
-additional_3 = 2010년~2012년 외부데이터
-additional_4 = 2007년~2009년 외부데이터
