# ML
한국어 소개 글이 아래에 나와있습니다. ( Editing... )

The Korean introduction is above, and the English introduction follows below.

# 프로젝트 소개
### 프로젝트 제목 
가격대가 높은 브랜드 카페의 매장 개수가 많은 지역의 경제적 수준이 더 높을까?

### 프로젝트 요약
 지역 경제수준을 파악하는 것은 정책 결정에 필수적이며, 투자 유치에도 중요한 역할을 한다. 이를 통해 지역 주민의 생활 수준과 사회적 필요를 이해하고, 효과적인 지원을 계획할 수 있다. 지역의 경제수준을 파악할 수 있는 수단에는 여러가지가 있다. 지역내총생산(GRDP)을 통해 파악을 하는 방법도 있지만 그 지역의 상권이나 학군을 보면 그 지역의 경제수준을 파악할 수 있다. 따라서 남녀노소 모두가 이용하는 카페를 기준으로 그 지역의 경제 수준을 파악한다. 우리나라에는 굉장히 많은 카페가 있지만 각 매장 음료 가격대별로 브랜드를 정하여 프로젝트를 진행하려고 한다.
 대표적으로 한국의 매머드 커피, 이디야 커피, 투썸플레이스, 스타벅스 네 브랜드의 카페 위치를 파악하고 그 지역의 지역수준을 알아볼 지표를 만든다. 부동산 매매가 데이터를 지역수준으로 가정하여 가격대가 높은 브랜드의 매장 개수가 많은 지역의 지역 수준이 높은지 알아본다.

### 사용한 데이터
1. 네 브랜드의 카페 위치를 크롤링하여 정보를 가져왔다. (2024년 11월 28일 기준)
 스타벅스 매장 목록 사이트

 https://www.starbucks.co.kr/store/store_map.do 

 매머드 커피 매장 목록 사이트
 
 https://www.mmthcoffee.com/sub/store.html?sido=%EC%84%9C%EC%9A%B8&gugun1= 

 이디야 커피 매장 목록 사이트
 
 https://www.ediya.com/contents/find_store.html
 
 투썸플레이스 커피 매장 목록 사이트
 
 https://mo.twosome.co.kr/so/storeList.do

2. '서울 열린데이터 광장'에서 서울시 부동산 실거래가 정보 데이터를 활용했다.
 가지고 있는 카페 위치 데이터가 2024년 데이터밖에 없기때문에 부동산 데이터도 2024년 데이터만 사용했다.

 https://data.seoul.go.kr/dataList/OA-21275/S/1/datasetView.do
 
※ 다른 깃(Jiyoun22/BDA)과 달리 다른 부동산 거래 정보를 사용하였다. BDA 프로젝트는 도서관을 실제로 사용하는 주민들이 주 대상이기 때문에 집값데이터를 사용하였지만 이번 프로젝트의 주 대상은 상권과도 연관이 있기때문에 빌딩과 같은 상가 거래 정보도 포함된 데이터를 사용했다.

# 데이터 처리 과정





