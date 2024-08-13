# K-CCRC 최적 입지 선정
초고령 사회에서 발생하는 노인 복지센터의 포화와 병원 예약 문제를 해결하는 것이었습니다.
이 문제에 접근하기 위해 저희 팀은 한국토지주택공사의 K-CCRC 사업 계획을 참고하여, 최적의 인프라와 병원 접근성 제공 가능 지역을 선정하는 데 중점을 두었습니다.

저는 팀에서 데이터 수집,처리,모델링,시각화 역할을 맡았습니다. 15개의 공공 데이터 세트를 수집하고, 행정구역 코드를 활용하여 데이터를 정제하는 과정을 진행했습니다. 
데이터의 복잡성을 관리하기 위해 분산 팽창 계수(VIF)를 계산하여 다중공선성을 분석하고, 
주성분 분석(PCA)을 통해 차원을 축소하는 방법을 적용했습니다. 
또한, 낮은 정확도를 보이는 문제를 해결하기 위해 절편을 0으로 설정하고 다시 회귀 모델을 구축하는 방법을 도입함으로써 데이터 기반 의사결정에 더 신뢰할 수 있는 결과를 제공했습니다. 
또한, QGIS 툴을 공부하여 습득하고 적용함으로써 분석결과를 시각화하여 발표에 설득력을 높일 수 있었습니다.
또한 데이터를 정제하는 과정에서 제가 개발한 데이터 처리 자동화 함수는 인프라 피처를 각 행정구역 코드에 일치하게 배치할 수 있어 데이터 처리 시간을 기존 1시간에서 20분으로 단축시켰습니다. 
이러한 기술적 개선은 팀의 전반적인 작업 효율성을 크게 향상시켰고, 프로젝트의 성공적인 완료로 이어졌습니다.
최종적으로, 저희 팀은 본선에 진출하여 프로젝트 결과를 전국 대회에서 발표함으로써 성과를 인정받았습니다.
이 경험은 적절한 기법을 활용한 데이터 분석의 중요성과 데이터 사이언스의 힘을 깊이 이해하게 하였습니다.
# 구동모습
<p align="center"> 
  <img src="https://raw.githubusercontent.com/wnghdcjfe/IUtoon/develop/example.gif" width="300">
</p> 

# 프론트 메인 기술
 - 패러랙스스크롤
 - fadein Effect
 - sticky CSS
 - debounce search

# 계획
 - 스타수10 이상 : SVG 및 아이유 애니메이션 구현
 - 스타수20 이상 : lSA, KNN, AutoEncoder 등을 이용한 아이유곡 IP 기반 / 컨텐츠기반 추천시스템구현

# 링크
http://kundol.kr

# 담당 
 - 프론트엔드, 코드리팩토링 : 주홍철(큰돌)
 - 백엔드    : 남승원(선린고1) 

# 다음웹툰 UI 
<p align="center"> 
  <img src="https://github.com/wnghdcjfe/IUtoon/blob/develop/DAUMUI.gif" width="300">
</p> https://raw.githubusercontent.com/wnghdcjfe/IUtoon/develop/DAUMUI.gif
 
## 구동방법
 - 백엔드 : back-end/README.md참조
 - 프론트엔드 : front-backend/README.md참조

### 클라이언트 스펙
 - `React`  
 - `styled-components`
 - `React-apollo`
 - `graphql` 

### 백엔드 스펙  
 - `Node.js`
 - `Express.js`
 - `MongoDB & node.js Driver` 
 - `React-apollo`
 - `graphql`  

# 참고링크
 - https://brunch.co.kr/@kakao-it/279
 - https://twitter.com/allofiu 

# 참고자료
카카오아레나 음악 추천시스템 대회 태그자료 https://arena.kakao.com/
