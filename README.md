# Hi there 👋
___

# Hi there! I'm hojong.
I am a new data analyst who is interested in deriving insights through data analysis.⌨

We will always do our best without stopping to develop.🔥
___

## My Skills
<div>
    <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" />
    <img src="https://img.shields.io/badge/Rstudio-white?style=for-the-badge&logo=Rstudio&logoColor=blue" />
    <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
    <img src="https://img.shields.io/badge/spss-blue?style=for-the-badge&logo=spss&logoColor=white" />
</div>

___

## My Project

#### 1. 노인복지시설 최적입지선정
* 분석 배경
  * 점점 고령화 인구가 증가하면서 노인복지시설의 부족함으로 인한 문제가 대두되고 있어 노인복지시설 건축이 가장 시급한 지역을 알기 위해 분석

* 분석툴
  * 파이썬
    - pandas, geopandas 패키지를 활용해 데이터 분석
    - folium 패키지를 활용해 히트맵 시각화
  * SPSS
    - 군집분석을 위해 Elbow-Method, Silhouette 계수를 추출하여 최적 군집 수 결정
    - K-means, Gaussian, Agglomerlative 군집분석 진행

* 분석절차
  1. 데이터 수집: 공공데이터포털인 열린데이터광장과 빅데이터캠퍼스에서 노인 관련 데이터 수집
  2. 데이터 전처리: 법정동명을 행정동명으로 통일화, MIN-MAX 정규화를 통해 데이터 표준화
  3. 데이터 분석: 히트맵을 통해 행정동별 데이터 시각화 후 군집 분석 진행, 각각의 군집분석 결과의 교집합인 행정동을 최적입지로 선정
  4. 결론: 최적입지로 선정된 행정동 중 인구와 현재의 노인복지시설 개수를 고려하여 최종입지선정
  5. 기대효과: 점점 늘어날 것으로 추정되는 고령화 인구에 대비해 미리 노인복지시설을 건축하여 미래 노인의 삶의 질 향상

* 분석결과
  - 각각의 군집분석을 통해 추출된 행정동 중 교집합에 해당하는 21개 행정동 추출, 이 중 노인복지시설이 1개 이하인 행정동 9개를 추출하여 최적입지로 선정

* 프로젝트 한계점
  - 네개의 노인복지시설을 모두 합한 후 분석을 진행하여 도출된 결과이기 떄문에 해당하는 행정동에 어떤 노인복지시설이 필요한지에 대한 한계점
  - 분석에서 고려한 변수들로 최적입지를 선정하기엔 분석의 타당도가 떨어진다는 한계점
 
* 파이썬 코드
  - [히트맵 파이썬코드](https://github.com/hanhojong/project/blob/main/heatmap%20code.ipynb)
  - [노인복지시설개수 heatmap]()
  - [부동산시세 heatmap]()
  - [노인인구 heatmap]()
  - [대중교통편의지수 heatmap]()

___

#### 2.  카카오톡 텍스트분석을 통한 생활습관개선
* 분석 배경
  * 대한민국 사람들이 가장 많이 사용하는 '카카오톡'에 사람들의 생활습관 및 대화습관이 녹아있다 생각하여 카카오톡 텍스트 분석을 통해 평소의 문제점을 확인하기 위해 분석

* 분석툴
  * 파이썬
    - numpy, pandas 패키지를 활용해 데이터 분석
    - matplotlib, seaborn, wordcloud 패키지를 활용해 데이터 시각화

* 분석절차
  1. 데이터 수집: '카카오톡 내보내기' 기능을 이용해 카톡방 텍스트 추출
  2. 데이터 전처리: 추출된 텍스트 파일을 엑셀을 활용하여 분석 가능하도록 전처리 진행
  3. 데이터 분석: 가장 활발히 대화가 이루어지는 시간, 대화 빈도수 등 분석 결고 도출
  4. 결론: 비속어 사용 빈도수, 시간 별 대화 빈도수 등을 통해 사람들의 안좋은 대화 및 생활습관 확인
  5. 기대효과: 분석을 통해 발견한 안좋은 대화 및 생활 습관을 개선함으로서 생활의 질 향상

* 분석결과
  - 대화가 가장 활발한 시간, 카톡 전송 횟수 등 다양한 데이터 분석을 통해 저를 포함한 팀원들이 늦은 시간까지 활동하는 것을 확인
  - 느낌표 사용 횟수, 자주 웃는 순위 등을 통해 팀원들의 메신저에서의 대화 습관 확인

* 프로젝트 한계점
  - PC 카카오톡과 핸드폰 카카오톡의 내보내기 기능을 통해 추출받은 데이터의 양식이 달라 각각 따로 볼 수 밖에 없는 한계점
  - 워드클라우드의 큰 의미없는 단어를 모아놓는 불용어사전 제작 부분에서 사람들마다 사용하는 텍스트가 달라 표준화된 불용어사전 제작의 한계점

* 파이썬 코드
  - [텍스트분석 파이썬코드](https://github.com/hanhojong/project/blob/main/kakaotalk%20text%20analysis.ipynb)
  - [워드클라우드 파이썬코드](https://github.com/hanhojong/project/blob/main/wordcloud.ipynb)

___

#### 3. 스크린골프장 상권분석
* 주제선정 배경
  * 2023년 9월에 저희집이 인수한 스크린 골프장 신규 이벤트 기획을 위해 주변 상권을 저격하는 알맞는 이벤트를 기획하기 위해 분석

* 분석개요
  1. 데이터 수집: 서울 상권 데이터와 골프장 관련 데이터 수집
  2. 데이터 전처리: 서울 상권 영역과 추정매출 데이터의 공통 변수 조인을 통해 데이터 도출 후 금천구 데이터 추출
  3. 데이터 분석: 상관관계분석, 주성분분석, 회귀분석을 통해 최종결론 도출
  4. 결론 및 기대효과: 금천구 상권에 맞는 다양한 이벤트 도출

* 파이썬 코드
  * [상권분석 파이썬코드](https://github.com/hanhojong/project/blob/main/commercial%20analysis.ipynb)
