# career-goal

# 요구사항
- [x] KYS(Known Your Self)를 작성한다.
    - [x] Key Strength 를 작성한다.
    - [x] Read.me 를 작성한다.
    - [x] Goal을 작성한다.
- [x] 되고싶은 개발자(Goal)가 되기 위한 gap 분석을 한다..
    - [x] Goal 작성 : 위에서 완성된 Goal중 원하는 하나를 선택한다.
    - [x] 필요역량 작성 : 되고싶은 개발자(Goal)가 되기 위해 필요 역량을 작성한다.
    - [x] 나의 상태 작성 : 지금 나는 어떤 역량을 가지고 있는지 작성한다.
    - [x] Gap 분석 : 되고싶은 개발자(Goal)가 되기 위해 가지고 있는 역량과 앞으로 습득해야할 역량을 작성한다.
    - [x] To-Do List : 되고싶은 개발자(Goal)가 되기 위해 어떤 것들이 필요할지 작성한다.

  
## 이름
김재한
## KYS 작성
### Key Strength
- Java 7, 8, 17
- Spring, JPA
- DDD
- Kubernetes
- eCommerce
### Read.me 작성
- 일 정산 금액이 평균 10억이 되는 정산 서비스를 마이크로서비스로 분리하여 개발 하였습니다.
- Java와 Spring 기반으로 커머스 서비스를 주문/정산 파트의 개발 및 운영을 담당 기존의 레거시 구조에서 마이크로서비스로 전환하는 업무를 하고 있습니다.

### Goal 설정
- 레거시 시스템에서 마이크로서비스까지 복잡도가 높은 서비스를 안정적으로 설계할 수 있는 테크리더
- 트래픽이 지금보다 10배 이상 늘어나도 안정적인 서비스가 운영될 수 있는 아키텍처로의 구성 및 설계
## Gap 분석
### Goal
- 레거시 시스템에서 마이크로서비스까지 복잡도가 높은 서비스를 안정적으로 설계할 수 있는 테크리더
### 필요역량
- Java 개발역량
- Spring Boot 역량
- JPA 역량
    - QueryDsl
- Spring Security
    - JWT
    - Oauth 2.0
- Spring Batch
- 동시성 처리
- 대용량 Transaction을 무결성을 지키면서 처리 할 수 있는 역량
    - Transaction Propagation, Isolation
    - SAGA pattern
    - DB Transaction
- Kubernetes 기반의 시스템 안정성이 높은 아키택쳐 구성
    - 안전한 배포를 위한 기술 : Blue/green deploy, gitOps
    - Istio
    - APM
- TDD
  - Junit5, Mock
- DDD
- 리더십
### 나의 상태
- Java 개발역량
- Spring Boot 역량
- JPA 역량
  - QueryDsl
- Spring Security
  - JWT
  - Oauth 2.0
- Spring Batch
- 동시성 처리
- 대용량 Transaction을 무결성을 지키면서 처리 할 수 있는 역량
  - Transaction Propagation, Isolation
  - SAGA pattern
  - DB Transaction
- Kubernetes 기반의 시스템 안정성이 높은 아키택쳐 구성
  - 안전한 배포를 위한 기술 : Blue/green deploy, gitOps
  - Istio
  - APM
- TDD
  - Junit5, Mock
- DDD
- 리더십
### Gap 분석
- Java : stream과 최신 자바에 대해서 익숙해 질 필요가 있음
- TDD : NEXTSTEP의 TDD 클린 코드 과정을 수강하고, 테스트 코드를 짜려고 노력하나 아직까지 레거시 소스에는 적용하지 못하고 있음
- DDD : NEXTSTEP의 교육과정을 들었지만 아직 활용하는데 있어서 부족한 것 같음
- Kubernetes의 구조 및 동작 원리 스터디
- 내가 생각하는 내 역량 : 하나의 개발자의 역할을 넘어 리더로서 성장하려면 방향 제시, 일정 산정, 업무 분배, 팀원과의 소통 능력을 길러야 할 것 같습니다.
### To-Do List
- Modern Java In Action : stream을 자주 쓸 기회가 없어서 연습이 학습이 필요할거 같습니다.
  - PC, Mobile를 구성하는 프로젝트는 Java 8, 정산 시스템은 Java 17을 사용하니 stream을 사용하는 환경에서는 최대한 활용 해보기
- Spring Batch : 마감 및 정산을 분리 하면서 사용은 했지만 명확한 숙련도를 올리기 위한 스터디가 필요
  - 정산서비스에서 이미 Tasklet 방식을 이해를 위해 Chunk 배치도 만들어 사용해 보기
  - 스프링 배치를 쓰지 않는 구성원들에게 설명해 줄 수 있는 문서 만들기
- 핵사고날 아키택쳐 : 만들면서 배우는 클린 아키텍처를 다시 읽어보고 기존에 만든 정산 서비스에 적용 해보기
- CKA 자격증 취득하기 : Kubernetes의 이해를 위해 단기 목표로 잡고 스터디 진행 예정
- 리더십 역량 기르기
  - 좋은 동료가 되기 : 이직하기 전 읽은 함께 자라기를 다시 한번 읽어 보고 지금의 나는 어떤 모습인가 생각해 보기
  - 담당 업무 문서화 : 신규 입사자 또는 팀 내의 파트에서 인원 교환시 업무에 적응 할 수 있는 가이드 작성
  - Ownership 가지기 : 현재 메인으로 맡고 있는 정산 서비스에 대해서 좀 더 주도적으로 업무를 수행하면 좋을거 같습니다. (ex: 코드 리뷰, 개선 사항을 먼저 제시)
  - 팀 도메인 위키 만들기

