# A comprehensive survey of data mining 세 장 요약

Data Mining 유형

- Data mining functions
- Data mining techniques
- Data mining algorithms
- Data mining domains

**Data mining functions**

Data mining 프로세스중에 발견할 패턴 또는 지식 유형 지정

- 주요 기능: 요약, 특성화 및 식별, 연관, 클러스터링, 분류, 이상치 분석, 회귀 및 추세 분석 등
(summarization, characterization and discrimination, association, clustering, classification, outlier analysis, regression and trend analysis, etc)

**Data mining techniques**

광범위한 Data mining 기술) ML, statistics, neural network, DB & data warehouse systems, genetic algorithms, fuzzy sets, visualization, etc.

**Data mining algorithms**

다양한 알고리즘) Apriori algorithm, 나이브 베이시안, k-Nearest Neighbour, k-Means, CLIQUE, STING 등

**Data mining domains**

각 도메인별로 하나 이상의 Data mining 응용 프로그램 존재

- 시계열 Data mining, Web mining, temporal data mining, 공간 data mining, 시공간 data mining, educational data mining, business, medical, science and engineering, etc

**Data mining applications**

하나 이상의 Data mining function을 사용할 수 있는 응용 프로그램 집합

- 예) 재무 데이터 분석, 장바구니 분석, 침입 탐지, 사기 탐지, 추천 시스템, 암 발견 등

대규모 DB 및 데이터 웨어하우스에서 다양한 미지의 패턴 추출을 위해 고유한 유형의 data mining 기능, 방법 및 기술 사용

- **summarization**, **characterization** and **discrimination**, **classification**, **regression** and **trend analysis**, **clustering**, **outlier analysis**, **association**, etc.

### 분야별 data mining 접근 방식

- Statistical approaches
- Machine learning
- Neural network
- Database systems and data warehouse
- Genetic algorithms
- Fuzzy sets
- Visualization

각 기술 관련 문헌 리스트 Table

![Untitled](A%20comprehensive%20survey%20of%20data%20mining%20%E1%84%89%E1%85%A6%20%E1%84%8C%E1%85%A1%E1%86%BC%20%E1%84%8B%E1%85%AD%E1%84%8B%E1%85%A3%E1%86%A8%20db15a83757124df5a4bebd6ad87cf332/Untitled.png)

**Statistical approaches**

Statistics: 데이터 기반으로 패턴 발견, 예측(통계에서는 regression이라고도 함) 모델 구축 시 사용

- 베이지안 네트워크, 상관 분석, 요인 분석, 판별 분석, 클러스터 분석, 회귀 분석 등 많은 통계 분석 도구 사용
- 대부분의 data mining에서 사용

Data mining 시 일반적으로 사용되는 statistical methods

- Bayesian network
- Correlation
- Regression
- Cluster analysis
- Discriminant analysis
- Factor analysis

**Machine learning**

Data Mining에서 ML의 중요성으로 인해 많은 data mining algorithm들이 ML에 뿌리두고 있음

ML의 두 가지 범주: Inductive(귀납) 및 deductive(연역) 

- deductive learning(연역적 학습): 시간에 따라 존재하는 사실과 지식을 다루고 오래된 지식에서 새로운 지식 생성
- inductive learning: 기존 지식으로 시작하는 대신 예제를 일반화

Meta-learning: 지적 방식으로 분리된 여러 학습 프로세스를 결합

- meta-learning architecture이 제시하는 두 가지 행위
    1. 정확한 final classification system(or final outcome)
    2. individual sequential learning algorithm보다 빨라야 한다.

네트워크 보안에서 ML의 적용: intrusion detection(ID, 침입 탐지) - 네트워크 보안 핵심 연구

- 비일반적인 액세스 또는 보안 네트워크에 대한 공격 식별 시 사용
- 이외 몇 가지 예시들

**Neural network**

ANN(Artificial neural network, 인공신경망): 생물학적 신경망과 유사한 인공 뉴런 또는 전기적 신호로 구성됨

- modern operations research tool로 중요한 역할
- 몇 가지 예시

**Database systems and data warehouse**

Database-oriented and data warehouse-oriented approaches: 모델 기반이 아닌 기존 데이터 모델을 사용하여 기존 데이터의 특성을 활용

- **대규모 데이터 세트** 처리 시 data mining 작업의 확정성과 효율성을 위해 DB 기술 적용
- 이 접근의 주요 방식
    - iterative database scanning for the attribute focusing(속성 포커싱을 위한 반복적인 DB 스캐닝)
    - attribute-oriented induction and frequent itemsets(속성향 귀납범과 빈발항목집합)

**Genetic algorithms**

genetic algorithms: 자연 생물학적 평가의 개념, 즉 선택, 번식, 돌연변이 및 적자생존의 과정 기반 알고리즘

- genetic algorithms 단점: solutions를 설명하기 어렵고 사용자가 특정 solution에 도달한 이유를 이해할 수 있는 통계적 측정 부재

**Fuzzy sets**

Fuzzy sets: membership function의 도움으로 계산된 possibility value 기반으로 degree of membership 정의

- classification 및 cluster analysis에 주로 사용
- 관련 연구 제시

**Visualization**

Visualization은 data set의 패턴 식별, 표현에 유용한 data mining 기술

- 데이터가 점, 선, 영역 등과 같은 객체로 변환되어 2차원 또는 3차원 공간에 표시
- visual examination을 통해 흥미로운 패턴 탐색 가능
- 관련 연구 제시

**Table 6)** **주요 기술 기반**으로 수행되는 **data mining 작업들**

![Untitled](A%20comprehensive%20survey%20of%20data%20mining%20%E1%84%89%E1%85%A6%20%E1%84%8C%E1%85%A1%E1%86%BC%20%E1%84%8B%E1%85%AD%E1%84%8B%E1%85%A3%E1%86%A8%20db15a83757124df5a4bebd6ad87cf332/Untitled%201.png)

### 데이타 마이닝 적용 사례

- Telecommunication sector
- Retail sector
- Financial data analysis
- Healthcare sector
- Fraud detection and crime prevention
- Customer relationship management(CRM)
- Recommender systems
- Online marketing/E-commerce

**Telecommunication sector**

data mining: 통신/모바일 서비스 제공자가

1. 마케팅 캠페인
2. 고객 유지
3. 고객 세분화 기반 고객 패키지
4. 최적의 통신 인프라 활용

등을 위한 전략 공식화 및 설계 시 활용

- classification & clustering) 마케팅 촉진을 위한 마케팅 캠페인 전략 수립
    - 클러스터링 후 분류를 통해 고객을 다양한 그룹으로 분류하여 유동 고객 예측
    - 식별된 고객 그룹 기반의 다양한 고객 그룹의 요구사항 기반으로 특정 패키지 공식화
    - 네트워크 사용 패턴 분석을 통해 활용도가 낮거나 과도하게 활용된 네트워크 인프라 식별하여 전체 인프라가 요구 사항에 따라 최적으로 활용 및 향상될 수 있도록 조성

**Retail sector**

1. 고객 구매 행동 예측
2. 장바구니 분석
3. 고객의 선택 예측
4. 진열대 제품 배치
5. 효과적인 제도 도입(쿠폰/할인)
6. 고객 세분화

소비자 구매, 장바구니 습관을 발견하기 위해 association analysis 사용

- 판매 데이터로부터 주어진 지지도와 신뢰도 기반으로 frequent itemsets 발견 → 판매 증가를 위해 제품 배치 수정
- 마케팅 캠페인: RFM(recency, frequency and monetary) 그룹화를 사용하여 설계 가능
    - 클러스터링을 활용한 판매 데이터 분석 ⇒ 최적의 상품 배치를 통해 매출 상승
- 판매 데이터) 클러스터링 및 분류를 사용하여 고객의 다양한 세그먼트 발견을 위해 분석됨
    - 다양한 마케팅 캠페인 및 promotions/offers는 고객 세그먼트에 맞게 사용자 지정할 수 있음
        - ‘구매 빈도는 낮지만 지출이 많은 고객’과 ‘구매 빈도는 높지만 금액이 적은 고객’은 다르게 취급

**Financial data analysis**

금융 데이터 분석을 위한 data mining

1. 대출 지불 예측
2. 고객 신용 정책 분석
3. 표적 마케팅을 위한 고객 세분화
4. 자금 세탁 및 기타 금융 범죄 탐지

attribute ranking 및 attribute selection의 도움으로 고객 지불 내역 분석하여

1. 신용 기록
2. 지불 대 소득 비율
3. 대출 기간

등 발견할 수 있음

- 위 예측은 은행/금융 기관의 대출 정책 결정, 점수에 따라 고객에게 대출 제공 시 도움

**Healthcare sector**

1. 만성 질환 식별 및 분석
2. 증상, (가능한) 원인 및 치료법 식별 및 발견
3. 확산되기 쉬운 고위험 지역 추적
4. 질병의 확산을 줄이기 위한 프로그램 설계
5. 환자의 지역 식별

클러스터링, 분류, association 등의 data mining 작업을 활용하여 imaging/lab sest data/reports/outlier detection 분석

- 만성 질환 식별/발견/예측 시 사용
- 증상 및 원인, 약물을 통해 위 질병 효과적인 치료 가능
- 분석 시, 질병의 확산에 취약한 고위험 지역 식별 및 추적을 위해 확장될 수 있음
    - 분석 바탕으로 지역에 대한 캠페인 설계하여 거주민들에게 질병과 예방 조치 알릴 수 있음
    - data mining, 증상, 원인 및 약물의 지속적인 비교를 사용하여 데이터 분석 수행 ⇒ 효과적인 치료 및 관련 부가 효과 창출 가능

**Fraud detection and crime prevention**

data mining을 활용한 이상치 발견

- 이상치는 데이터에서 드문 패턴 발견하여 식별 ⇒ 사기/범죄 활동
- 이상치 탐지 및 간헐적 패턴 마이닝 ⇒ 사기 식별, 예측하여 범죄 발생 예방

**Customer relationship management(CRM)**

1. DB 마케팅
2. 고객 확보 및 고객 유지 캠페인 등의 식별 및 예측

**Recommender systems**

recommender systems: 사용자가 관심 가질 수 있는 다양한 권장 사항을 stakeholders에게 제공

- 사용자 트랜잭션, 사용자 프로필, 키워드, 항목 간 공통 기능 조사하여 사용자에 대한 항목 추정
- ML, statistics, 정보 검색 등의 많은 data mining 기술 사용됨
    - 예) in 마케팅, 사용자가 과거에 문의한 항목과 유사한 항목을 추천하거나 사용자와 유사한 취향을 가진 다른 고객 선호도를 확인하여 추천

**Online marketing/E-commerce**

1. 전자 상거래 판매자가 웹에서 텍스트 마이닝을 활용하여 제품 최저 가격 발견
2. 대형 패스트 푸트 체인 판매자) 고객의 주문 패턴, 대기 시간, 주문 규모 등 연구 (고객 경험 향상을 위한 데이터 마이닝)
3. 온라인 미디어 서비스 제공업체) 시리즈, 영화를 더 인기있게 만들기 위한 방법 강구

**마무리**

대부분의 data mining system) 다양한 유형의 데이터, data mining 작업 및 응용 분야를 처리하는 방법의 조합 사용됨

- 다양한 data mining 작업 및 기술은 많은 회사들이 1. 지식을 얻고 2. 절차 및 운영을 수정하여 수익성을 높이는 데 도움이 된다.
- 숨겨진 패턴 및 추세 분석을 통해 기업의 의사 결정을 도움

아래 세 데이터 마이닝 분야에서 더 많은 관심이 필요함

1. unification, scalability and optimization of data mining algorithm/methods
2. cube-oriented multidimensional data mining
3. 확장 가능한 실시간 mining