# Reference

https://dacon.io/competitions/official/17801/overview/description


# 데이터 설명

한국의 서울과 부산 지역 약 2,700여개 최근 2년간 아파트 경매물의 등기부, 임차, 감정가, 유찰 횟수, 낙찰가 등의 정보가 제공됩니다. 아파트 낙찰가를 예측해야 합니다. 

* 국토교통부 실거래가공개시스템(http://rt.molit.go.kr) 등 법적인 제약이 없는 외부 데이터(공공 데이터) 사용이 가능합니다.


# 파일 설명
1. Auction_master_train.csv – 서울/부산 지역의 낙찰가를 포함하여 경매 물건 아파트의 위치, 감정가, 경매 개시/종결일 등의 기본 정보(*최근2년)
2. Auction_master_test.csv – 경매 낙찰가를 제외하고 train.csv와 동일 
3. Auction_submission.csv – 예측한 낙찰가를 기입하여 제출
4. Auctiuon_regist.csv – 아파트에 대한 등기 정보
5. Auctiuon_result.csv – 경매일자, 감정가, 최저매각가격, 경매 결과 데이터.
6. Auctiuon_rent.csv – 해당 아파트에 임차인이 있는 경우, 전입/점유 여부, 보증금, 월세 등의 데이터.


자세한 설명은 reference를 참조하시면 됩니다.