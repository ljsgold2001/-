# 5장

- 소프트웨어개발 방법론
  - 개발 유지보수 등에 필요한 여러가지 일들을 효율적으로 수행하려는 과정에서 기법 및 도구를 체계적으로 정리하여 표준화함
  - 소프트웨어개발 방법론은 생산성 향상과 품질향상이다.
    - 구조적방법론
    - 정보공학방법론
    - 객체지향방법론
    - 컴포넌트기반방법론
    - 애일 방법론
    - 제품계열방법론
- 구조적 방법론
  - 정형화된 분석절차에따라 요구사항을 파악하여 문서화하는 처리중심의 방법이다.
  - 쉬운코드 및 검증이 가능한 프로그램 코드를 생성하는것이 목적이다.
  - 분할정복(divide and conquer)
    - 타당성검사 ->계획->요구사항단계 ->설계단계 ->구현단계->시험단계@@->운용/유지보수단계
- 정보공학방법론
  - 정보시스템 개발을 위해 계획 분석 설계 구축에 정형화된 기법을 연관성있게 통합및 적용하는 자료중심 방법론
    - 계획수립 - 업무영역분석 -업무시스템설계 - 업무시스템구축
- 객체지향방법론
  - 엔티티를 기계의 부품처럼 하나의 객체로 만들어 부품을 조립하듯이 객체를 조립해서 필요한 소프트웨어를 구현
  - 문제점은 위기의 해결책이다.
  - 구성요소로는 객체 클래스 메시지등이있다.
  - 캡슐화, 정보은닉, 추상화, 상속성, 다형성
    - 요구분석 - 설계 - 구현 -테스트및 검증 - 인도단계
- 컴포넌트기반(CBd)
  - 기존의 시스템이나 소프트웨어를 구성하는 컴포넌트를 조합하여 하나의 어플리케이션을 만드는 방법론
  - 재사용이 가능하여 시간과 노력을 절감한다.
  - 유지보수 최소화하고 생산성 및 품질을 향상
    - 개발준비-분석-설계-구현-테스트-전개-인도
- 애자일방법론
  - 요구사항에 유연하게 대응하기위해서 일정한 주기를 반복하면서 개발과정을 진행한다.
  - 소규모프로젝트 고도로 숙달된 개발자, 급변하는 요구사항
  - XP ,스크럼, 칸반 , 크리스탈
  - 스토리 ->(계획 - 개발 - 승인테스트)(반복)
- 제품계열방법론
  - 특정제품에 적용하고 싶은 공통된 기능을 정의하여 개발한다.
  - 임베디드 소프트웨어를 만듬
    - 영역공학 : 영역분석, 영역설계, 핵심자산
    - 응용공학 : 요구분석, 제품설계 , 제품구현
    - 이들의 연계를 위해서는 요구사항 아키텍처 조립생산이 필요하다.
- 소프트웨어 비용산정
  - 개발규모를 소요되는 인원, 자원, 기간등으로 확인하여 실행가능한 계획을 수립하기위해 필요한 비용을 산정하는것이다.
  - 비용을 너무 높게하면 효율성이저하 , 비용을 너무 낮게 정하면 부담이 가중되고 품질의 저하
    - 상향식 비용산정
    - 하향식 비용산정
- 소프트웨어의 비용을 결정하는 세가지 요소
  - 프로젝트 요소
    - 제품 복잡도 - 문제점들의 난이도
    - 시스템크기  
    - 요구되는 신뢰도 -일정기간 내 주어진 조건하에서 프로그램이 필요한 기능을 수행하는 정도
  - 자원요소
    - 인적자원 - 개발 관련자들이 갖춘 능력 혹은 자질
    - 하드웨어 자원 - 필요한 장비
    - 소프트웨어 자원 -언어분석기 , 문서화 도구 등
  - 생산성요소
    - 개발자 능력 - 전문지식, 경험 , 이해도 ,책임감, 창의력
    - 개발기간 - 소프트웨어를 개발하는 기간
- 하향식 비용 산정 기법
  - 전문 지식이 많은 개발자들이 참여한 회의를 통해 비용을 산정하는 비과학적인 방법이다.
    - 프로젝트 전체비용을 산정한 후 작업별로 비용을 세분화한다.
  - 전문가 감정기법과 델파이 기법이 있다.
    - 전문가 감정기법
      - 경험이 많은 두명 이상의 전문가에게 비용 산정을 의뢰한다.
      - 가장편리하고 신속
      - 다른요소들이 있다는 것을 간과할 수 있다.
      - 개인적이고 주관적이다.
    - 델파이 기법
      - 많은 의견을 종합해서 산정한다.
      - 한명의 조정자와 여러전문가로 구성
      - 순서
        - 시스템 정의서와 비용 내역을 기록할 서식을 준비한다.
        - 익명으로 비용을 산정한다.
        - 조정자는 반응을 요약하여 배포한다.
        - 산정자들은 결과를 다시 익명으로 산정한다.
        - 의견이 일치할때까지 반복한다.
- 상향식 비용 산정 기법
  - 세부적인 작업 단위별로 비용을 산정한 후 집계하여 전체 비용을 산정하는 기법이다
    - LOC 기법
    - 개발 단계별 인월수 기법(effort per task)
      - LOC 기법
        - 비관치, 낙관치, 기대치를 측정하여 예측치를 구하고 비용을 산정하는 기법
        - 예측치 = a +4m +b/6
        - 노력 = 개발기간 X 투입인원 =LOC/1인당 월평균 생산코드라인수
        - 개발비용 = 노력 X 단위비용(1인당 인건비)
        - 개발기간 = 노력 X 투입인원
        - 생산성  =LOC/노력
      - 개발 단계별 인월수 기법
        - LOC기법의 보안으로 필요한 노력을 생명주기의 각 단계별로 산정한다
- 수학적 산정기법
  - 상향식 비용 산정기법이다.
  - 경험적 추정모형, 실험적 추정모형이라고도한다.
  - 개발 비용 산정의 자동화를 목표로한다.
  - COCOMO모형
    - 보헴(bohem)이 제안한 것으로 LOC에 의한 비용산정 기법이다.
    - 유연성이 높다.
    - 같은 프로젝트라도 성격에 따라서 다르게 산정된다.
    - 비용산정결과는 프로젝트를 완성하는데 필요한 노력(man-month)로 표현된다.
  - COCOMO의 소프트웨어 개발 유형
    - 원시 프로그램의 규모에 따라 조직형, 반분리형, 내장형으로 나눌수 잇다.
    - 조직형
      - 중,소 규모의 소프트웨어 
      - 5만라인 이하의 소프트웨어개발
    - 반분리형
      - 조직형과 내장형의 중가으로 트랜잭션, 운영체제 , DB관리등 
      - 30만 라인 이하의 소프트웨어 개발
    - 내장형
      - 최대 규모의 트랜잭션 처리시스템이나 운영체제
      - 30만 이상의 소프트웨어 처리
  - COCOMO 모형의 종류
    - 기본형, 중간형, 발전형
    - 기본형
      - 소프트웨어의 크기와 개발유형만을 이용하여 비용을 산정
    - 중간형
      - 기본형의 COCOMO의 공식을 토대로 사용하지만 4가지 15가지 요인에 의해 비용을 산정한다.
      - 제품의 특성
      - 컴퓨터의 특성
      - 개발요원의 특성
      - 프로젝트 특성
    - 발전형
      - 중간형 COCOMO를 보완하여 만들어진것으로 자세하고 정확하게 노력을 산출한다.
      - 소프트웨어 환경과 구성요소가 사전에 정의되어 있어야하면 개발과정의 후반부에 등장한다.
    - Putnam모형
      - 생명주기 전과정동안에 사용될 노력의 분포를 가정하는 것이다.
      - 생명주기 예측모형
      - 대형 프로젝트의 노력 분포 산정에 이용된다.
      - 개발기간이 늘어날 수록 프로젝트 적용 인원의 노력이 감소한다.
    - FP(기능점수 모형)
      - 소프트웨어의 기능을 증대시키는 요인별로 가중치를 부여하고 요인별 가중치를 합산하여 총 기능점수를 산출
    - 푸트남이나 COCOMO는 LOC를 기반으로 산정하지만 기능점수모형은 FP를 이용해서 산정한다.
    - 비용산정의 자동화도구
      - SLIM : rayleigh-Norden곡선과 putnam예측모델을 기초로하는 자동화 추정도구
      - ESTIMACS : 다양한 프로젝트와 개인별 요소를 수용하도록 FP모형을 기초로하여 개발된 자동화추정도구



# GRADE B

- ISO/IEC 12207
  - 소프트웨어 생명주기 표준을 제공한다.
    - 기본 생명주기
    - 지원 생명주기
    - 조직 생명주기
- CMMI
  - 성숙도를 평가하는 모델
  - 초기 - 관리 - 정의 - 정량적관리 - 최적화
    - 초기 : 작업자의 능력이 성공여부
    - 관리 : 특정한 프로젝트 내부의 프로세스 정의 및 수행
    - 정의 : 조직의 표준 프로세스를 활용
    - 정량적관리 : 프로젝트를 정량적으로 관리 및 통제
    - 최적화 : 역량 향상을 위해 지속적인 프로세스 개선
- SPICE
  - 생산성의 향상을 위해 소프트웨어 프로세스를 평가 및 개선하는 국제 표준으로 공식명칭 ISO/IEC 15504
  - 기관스스로하는것
  - 5개의 프로세스범주와 40개의 세부 프로세스
    - 고객 공급자 범주
      - 소프트웨어를 개발해서 고객에게 전달
    - 공학 범주
      - 명세화, 구현 ,유지보수
    - 지원
      - 소프트웨어가 생명주기에서 다른프로세스에 의해 이용된다.
    - 관리
      - 생명주기에서 관리자에의해 사용되는 프로세스
    - 조직
      - 업무 목적 수립과, 업무 목표달성
  - 6단계
    - 불완전 - 수행- 관리 - 확립 - 예측 - 최적화
      - 불완전
        - 구현되지 않거나 목적을 달성하지 못함
      - 수행
        - 목적이 달성된 단계
      - 관리
        - 산출물 인도
      - 확립
        - 원칙에 기반한 프로세스 수행
      - 예측
        - 목적 달성을 위해 통제, 일관되게 수행
      - 최적화
        - 지속적인 개선