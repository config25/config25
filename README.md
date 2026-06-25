# Backend Developer                                      
                                                                                          
  <p align="center">                                                                                                                                                                                                                
    <b>저사양 환경에서의 성능 최적화부터 확장성 있는 구조까지, 동작하는 코드 너머의 문제를 해결하는 백엔드 개발자입니다.</b>                                                                                                        
  </p>                                                                                                                                                                                                                              
                                                                                                                                                                                                                                    
  ## 👋 About Me  

  - **운영 중인 결제 모듈** 단독 유지보수 — PG사 2회 재이관(KCP → 토스 → NicePay)을 거치며 멱등성 / 분산 락 / DLQ / 상태머신을 **PG-agnostic하게 추상화**
  - **저사양 서버 튜닝** — 1코어/1GB 환경에서 HikariCP·Tomcat·ioExecutor 튜닝 + `CallerRunsPolicy` 백프레셔로 OOM 방어
  - **멀티모듈 + DIP 설계** — domain이 인터페이스에만 의존하도록 분리, JPA Entity ↔ 도메인 POJO 매핑으로 LLM/스토리지 교체 가능한 구조 반복 적용

  ## 🌐 Open Source Contributions

  ### spring-projects/spring-batch

  | Issue | Description | Related PR |
  |-------|-------------|------------|
  | [#5366](https://github.com/spring-projects/spring-batch/issues/5366) | `ExitStatus#setExitException` breaks immutability contract | [#5367](https://github.com/spring-projects/spring-batch/pull/5367) |
  | [#5385](https://github.com/spring-projects/spring-batch/issues/5385) | `MongoStepExecutionDao#getLastStepExecution` filters and sorts all step executions in memory instead of pushing the filter/sort/limit down to MongoDB |[#5405](https://github.com/spring-projects/spring-batch/pull/5405) |

  ### spring-projects/spring-restdocs

  | Issue | Description | Related PR |
  |-------|-------------|------------|
  | [#1033](https://github.com/spring-projects/spring-restdocs/issues/1033) | `MockMvcRequestConverter` uses US_ASCII for URL decoding while encoding uses UTF-8 |[#1034](https://github.com/spring-projects/spring-restdocs/pull/1034) |
  | [#1038](https://github.com/spring-projects/spring-restdocs/issues/1038) | `WebTestClientRequestConverter` mishandles cookies whose value contains `=` | [#1040](https://github.com/spring-projects/spring-restdocs/pull/1040) |
  | [#1039](https://github.com/spring-projects/spring-restdocs/issues/1039) | `UriModifyingContentModifier.modifyContent` decodes with the request charset but re-encodes with the platform default |[#1043](https://github.com/spring-projects/spring-restdocs/pull/1043) |

  ### spring-projects/spring-data-jpa

  | Issue | Description | Related PR |
  |-------|-------------|------------|
  | [#4242](https://github.com/spring-projects/spring-data-jpa/issues/4242) | `QueryUtils.FUNCTION_PATTERN` fails to detect `COUNT(*) AS alias`, causing invalid `ORDER BY` alias rewriting in native queries |[#4249](https://github.com/spring-projects/spring-data-jpa/pull/4249) |


  ## 📊 Stats

  <p align="center">
    <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=config25&show_icons=true"/>
  </p>

  ## 🧰 Tech Stack

  <p>
  <img src="https://img.shields.io/badge/Java-17-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/Kotlin-purple?style=flat-square"/>
  <img src="https://img.shields.io/badge/Spring%20Boot-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Spring%20Security-brightgreen?style=flat-square"/>
  <img src="https://img.shields.io/badge/JPA-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/WebSocket-lightgrey?style=flat-square"/>
  <br>
  <img src="https://img.shields.io/badge/MySQL-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/MongoDB-green?style=flat-square"/>
  <br>
  <img src="https://img.shields.io/badge/AWS-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/Docker-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/GitHub%20Actions-black?style=flat-square"/>
  </p>

  ## 🏆 Achievements

  - 📱 **드르륵 (drr)** — iOS App Store 정식 출시 · 2025 한양대 캡스톤 디자인 **우수상**
  - 🥈 2025 9ITHON **우수상 (2위)** — RoomGenie
  - 🥇 2023 전국 대학생 SW창업 아이디어톤 **결선 진출**

  ## Experience

  * 🏢 **(주)퀀텀에듀솔루션 현장실습** (2026.01 ~ 2026.06)
    - **Unicast (https://unicast.kr) 구독 결제 모듈** — PayPal + 국내 PG 연동, PG사 2회 재이관(KCP → 토스 → NicePay) 대응
      - 방어로직: 멱등성 / 이중결제 방지 / 분산 락 / DLQ / 상태 전이 검증 / 웹훅 중복방지
      - GitHub Actions 기반 CI/CD 파이프라인 구축, PG사 가맹 심사 대응
    - **Impact Design Canvas** 풀스택 단독 개발 — Spring Boot · MariaDB · OpenAI
    - **CX-INNOVATOR** 디자인 씽킹 플랫폼 유지보수 — http://www.abl-cxinno.kr/main
      - 학생 정보 관련 화면/DB 추가, 팀원 탭·대표작성자 왕관 표시
      - PDF 보고서 연동 버그 수정, C-3 / F-1 / B-1 단계 기능 추가, chatbot / 문제여정지도 작업

  * 🌱 **구름톤 유니브 4기 백엔드** (2025.03 ~ 2025.09)
    - 백엔드 B팀 스터디장
    - 경기북부 해커톤 9ITHON, 구름톤 시즌톤 참여 — 9ITHON 2위(우수상)

  ## 🚀 Projects

  <details>
  <summary>💳 Unicast 결제 모듈 — PG 2회 재이관 대응 + 방어로직 추상화 (운영 중) 🔥</summary>

  > 영상 자막 추출·번역·더빙 디지털 콘텐츠 서비스의 **결제 모듈 단독 유지보수** 및 방어로직 보강

  - **Role**: 운영 중인 결제 모듈 단독 유지보수 및 방어로직 보강 (현장실습)
  - **Scope**: PayPal/국내 PG 결제 흐름, 웹훅 처리, 정기결제 스케줄러, PG 심사 대응 (서비스 본체 기능은 범위 외)
  - **Tech**: Spring Boot · Next.js · MongoDB(분산 락) · NHN KCP · 토스페이먼츠 · NicePay · PayPal · Webhook · DLQ · State Machine · GitHub Actions · Docker
  - **Service**: https://unicast.kr (운영 중)

  **Key Work**

  - **PG 2회 재이관(KCP → 토스 → NicePay) → 방어로직을 PG-agnostic하게 추상화**
    - **1차 (KCP → 토스)** : 초기에는 NHN KCP로 정기결제(배치키 발급 → 스케줄러 자동결제 → 구독 취소/배치키 삭제) 프론트+백엔드 전 구간을 구현했으나, KCP 측에서 **"정기과금(구독) 상품은 계약 검토 불가, 단건결제로만 계약 가능"**
  정책 회신을 받아 토스페이먼츠로 이관
    - **2차 (토스 → NicePay)** : 운영 정책 변화에 맞춰 NicePay로 재이관
    - **추상화 성과** : 두 번의 재이관을 거치며 멱등성·DLQ·분산 락·상태 전이 검증 로직을 **PG 어댑터 외부**로 분리. `Provider 락` · `빌링키 발급 + 첫 결제 원자성` · `사후조회 기반 네트워크 복구` 같은 안정성 장치를 PG-독립적으로
  재사용 가능하게 다듬음
  - **결제 방어로직 강화** — 운영 중 발견된 race condition / 누락 케이스에 대해 멱등성·분산 락·DLQ·상태 전이 검증 도입
  - **PG사 가맹 심사 대응** — 결제 플로우 보완, 약관/환불규정/통신판매업번호 등록
  - **CI/CD 파이프라인 신규 구축** — GitHub Actions 기반 자동 빌드·배포

### Troubleshooting

#### 1. 빌링키 발급 ↔ 첫 결제 원자성 확보 (`d7e9637`, `f9fedff`)

* **문제**

  * 초기 구조는 "빌링키 발급 → 다음 스케줄러 주기에 첫 결제" 방식이라 가입 직후 유료 기능 사용이 불가능했고, 결제 누락처럼 보이는 UX 문제가 존재

* **해결**

  * 빌링키 발급 직후 첫 결제를 동기 실행으로 변경
  * 발급·결제·검증 단계별 성공 여부를 기록해 실패 시 보상 처리(빌링키 만료 / 자동 취소 / DLQ 적재)
  * `nextBillingDate <= today` 기반 밀린 결제 복구 잡 추가
  * UTC 컨테이너 ↔ KST 운영 환경 차이로 청구일이 하루 어긋나던 문제를 `ZoneId.of("Asia/Seoul")` 명시로 해결

* **결과**

  * PG 재이관(KCP → 토스 → NicePay) 이후에도 동일 패턴 재사용 가능

---

#### 2. 결제 동시성 방어 — 멱등성 + 분산 락 + DLQ (`0ec22b4`)

* **문제**

  * 버튼 더블 클릭/재시도로 인한 이중 결제
  * 다중 인스턴스 스케줄러 동시 실행 시 전체 구독자 중복 청구 가능
  * webhook 처리 실패 메시지 유실 위험 존재

* **해결**

  * MongoDB unique index + TTL을 공통 primitive로 사용
  * `IdempotencyKey` : `(memberId + operation)` 유니크 인덱스 + 24h TTL
  * `SchedulerLock` : `_id` 유니크 제약 기반 분산 락 + 30분 TTL
  * `PaymentDeadLetter` : 실패 메시지 격리 후 지수 백오프 재시도 및 운영자 수동 개입 지원

* **비고**

  * 멱등성과 DLQ는 단일 인스턴스에서도 필수
  * 분산 락은 다중 인스턴스 스케일아웃 대비 선제 설계

---

#### 3. 구독 상태 전이 검증 — 상태 머신 가드 도입 (`0ec22b4`)

* **문제**

  * webhook 중복 수신이나 코드/운영 개입으로 인해 비논리적인 상태 전이(CANCELLED → SUSPENDED 등)가 가능
  * 상태 변경 규칙이 코드 곳곳에 흩어질 위험 존재

* **해결**

  * `SubscriptionStatus` enum에 허용 전이 규칙 정의
  * 상태 변경은 `transitTo()` 도메인 가드를 반드시 통과하도록 제한(raw setter 제거)
  * `activate()`는 멱등 처리해 중복 ACTIVATED webhook 흡수

* **결과**

  * 상태 전이 규칙을 도메인 내부로 캡슐화해 비정상 상태 조합 차단
  * webhook/운영/서비스 코드 등 어떤 입력 경로에서도 동일 규칙 강제 가능


  ---

  🔗 [Unicast](https://unicast.kr) · [API Docs](https://api.unicast.kr/swagger-ui/index.html#/) · [GitHub](https://github.com/config25/v2)

  </details>

  <details>
  <summary>🎨 Impact Design Canvas — AI 기반 성과 설계 교육 플랫폼</summary>

  > 교육 현장에서 학습 성과를 설계하고 관리하는 AI 기반 플랫폼

  - **Role**: 풀스택 단독 개발
  - **Period**: 2026.01 ~ 2026.02
  - **Tech**: Spring Boot, Spring Security(JWT), MariaDB, OpenAI API, GitHub Actions

  **Key Features**
  - **6단계 캔버스 워크플로우** — Impact Check → Identity → Flow → Quick Win → Build Win → Review로 학습자의 성과 설계를 단계별 가이드
  - **AI 자동 리포트 생성** — 팀별 캔버스 데이터를 OpenAI GPT-4.1로 분석하여 비전/미션/SWOT 등 종합 리포트 산출
  - **강사용 통합 관리** — 수업/팀(최대 6×10명) 관리, 학생 진행도 추적, 벌크 PDF 다운로드

  **Troubleshooting**
  - **OpenAI 응답 지연 → 톰캣 스레드 누수** : `CompletableFuture` 4-fan-out 병렬화 + executor(60s) / HTTP read(50s) **cascade 타임아웃**으로 백그라운드 스레드 정리 보장, fallback 응답으로 장애 격리
  - **1코어 / 1GB RAM 메모리 압박** : 힙 256MB · HikariCP 5 · Tomcat 30 · ioExecutor 풀 5 + 큐 50(`CallerRunsPolicy`)로 **백프레셔 설계**, 무제한 큐의 OOM 위험 차단
  - **storage·external 강결합 위험** : domain 레이어가 인터페이스(`Repository`, `AiClient`, `ExternalFileClient`)에만 의존하도록 **DIP 적용**, JPA 엔티티 ↔ 도메인 모델(POJO) 분리로 LLM 제공자/스토리지 교체 가능

  🔗 [back](https://github.com/config25/Impact-design-back) · [front](https://github.com/config25/Impact-design-front) · [API Docs](http://iptdesign.mycafe24.com/docs/index.html) · [WEB](http://iptdesign.mycafe24.com)

  </details>

  <details>
  <summary>💬 드르륵 (AI 메신저) — SNS + AI 기반 실시간 채팅 서비스 🏆</summary>

  > 친구와의 대화를 AI가 학습하여, AI 클론을 통해 친구의 답변을 예측해보는 메신저 서비스 (iOS 출시)

  - **Role**: 백엔드 개발 · 팀 5인
  - **Period**: 2024.09 ~ 2025.06
  - **Tech**: Kotlin, Spring Boot 3, WebSocket(STOMP), MySQL, MongoDB, Spring Security(JWT), NCP Object Storage, OpenAI, Docker, GitHub Actions

  **Key Features**
  - **3종 채팅방 통합 아키텍처** — Direct(1:1) / Group / AI 채팅방을 별도 도메인으로 분리하되, 메시지·시퀀스·읽음 처리 로직은 공통 추상화
  - **AI 클론 응답 파이프라인** — 사용자 대화 패턴을 OpenAI에 위임, 부재 상황에서 AI가 본인 대신 응답
  - **실시간 메시지 시퀀싱** — MongoDB 기반 채팅방별 sequence/읽음 상태 관리, STOMP `/topic` + `/user/{id}` 이중 채널로 멀티 디바이스 동기화
  - **피드(SNS) ↔ 채팅 연동** — 친구 피드에 댓글을 달면 자동으로 1:1 채팅방으로 전송되는 cross-domain 인터랙션

  **Architecture**
  - **5개 멀티모듈** (api / domain / storage / external / common) + REST Docs 전용 모듈, 의존 방향: `api → domain ← storage / external`
  - **DDD를 무겁게 적용하지 않고, Service(단일 책임) / Facade(유스케이스 오케스트레이션) / Aggregator(이종 데이터 조립) 3계층으로 절제** — 예: `DirectChatRoomAggregator`로 채팅방 + 최신 메시지 결합
  - **DIP 적용** — domain은 `Repository`·`ExternalAiClient`·`ExternalPushNotificationClient` 인터페이스에만 의존, JPA/Mongo Entity ↔ 도메인 모델 분리

  **Troubleshooting**

  - **이기종 DB(MySQL + MongoDB) 트랜잭션 의도적 배제 → Saga 스타일 조합**
    : 채팅방 상태(MySQL)·메시지 로그(MongoDB)·외부 알림(FCM/Expo)이 한 유스케이스에서 같이 변경됨. `@Transactional`을 걸면 **MySQL만 롤백되고 Mongo·푸시는 남는** 가짜 안정감만 주는 문제 → Facade에서 트랜잭션을 빼고, 각 작은
  service만 자신의 저장소 트랜잭션을 책임지도록 **경계 축소**. 실패 시 `chatErrorMessages()`를 같은 알림 채널로 흘려보내 클라이언트가 오류 상태를 인지·재시도하는 **eventual consistency 패턴**으로 전환.

  - **시퀀스 증가 race condition** (`5e49963`)
    : 채팅방 존재 여부 확인 없이 sequence를 먼저 증가시키다 보니, 삭제된 방에 대해 시퀀스만 증가하는 유령 상태가 발생 → `increaseDirectChatRoomSequence` 호출 전에 채팅방 존재 검증을 선행하도록 Facade 로직 재배치, 시퀀스 카운터의
   무결성 회복.

  - **MongoDB 인덱스 전략 재설계** (`4ec7f92`)
    : 초기 partial index(`{chatRoomId, type, message}`)는 조건이 까다로워 채팅 로그 범위 조회 / 키워드 검색 둘 다 못 잡아먹음 → ① 범위 조회용 **복합 인덱스** `{chatRoomId: 1, sequence: -1}`, ② 메시지 본문용 **text 인덱스**
  `{message: 'text'}` 두 가지로 분리. 페이지네이션과 키워드 검색 모두 인덱스 사용.

  - **MySQL 핫패스 인덱스 부재** (`33b1acb`)
    : 1:1 채팅방 목록 조회(`userAId/userBId × status`), 친구 즐겨찾기 조회 등 핫패스가 풀스캔 → `direct_chat_room`에 (userA/userB, status) 복합 인덱스 3종, `friend_ship`에 `(user_id, favorite)` 인덱스 추가로 응답 시간 개선.

  - **STOMP 핸드셰이크 인증 흐름 정비** (`0e8a3d2`, `ca8e2e8`)
    : 핸드셰이크 시점에는 HTTP 헤더에 JWT가 없는 경우가 있어 인증 누락 → `CustomHandshakeHandler` + `StompChannelInterceptor`에서 **CONNECT 프레임 시점**에 `Authorization` 헤더 검증, JWT에서 추출한 `userId`를 `Principal`로
  주입해 이후 메시지 핸들러가 일관되게 접근.

  - **이미지 트래픽 절감** (`42ded85`)
    : 채팅 첨부 이미지 원본 그대로 NCP 업로드 → 대역폭/모바일 데이터 부담 → Scrimage 기반 **WebP 변환 파이프라인** 도입, 업로드 단계에서 손실 압축 적용.

  🔗 [GitHub](https://github.com/Chewing-Chat) · [API Docs](https://config25.github.io/config25/drr.html) · [App Store](https://apps.apple.com/kr/app/%EB%93%9C%EB%A5%B4%EB%A5%B5-drr/id6742639598)

  </details>

  <details>
  <summary>🧹 RoomGenie — AI 이미지 기반 방 정리 서비스 🏆</summary>

  > AI가 방 사진을 분석하여 정리 방법을 제안하는 서비스

  - **Role**: 백엔드 개발 · 팀 5인
  - **Period**: 2025.05 ~ 2025.07
  - **Tech**: Java 17, Spring Boot 3.5, Spring Security(JWT), JPA/MySQL, AWS S3, OpenAI GPT-4 Vision, YOLO, LAMA, NCP Sens(SMS)

  **Key Features**
  - **3종 AI 파이프라인** — YOLO(객체 감지) → LAMA(인페인팅)로 "정리된 방" 시뮬레이션 이미지 생성 + GPT-4 Vision으로 단계별 정리 가이드 제공
  - **AI 기반 미션 자동 검증** — before/after 이미지를 GPT-4 Vision으로 비교, 응답 토큰(`[RESULT:SUCCESS]`) 파싱으로 미션 상태머신 자동 전이
  - **휴대폰 OTP 2단계 인증** — NCP Sens HMAC-SHA256 + Caffeine 캐시 기반 OTP 검증 후 JWT 발급

  **Architecture**
  - **6개 멀티모듈**(api/domain/storage/external/common/api-docs) 계층 분리
  - **DIP 적용** — domain이 `ExternalAiClient`/`ExternalFileClient` 인터페이스에만 의존, JPA Entity ↔ Domain POJO 분리로 LLM·스토리지 교체 가능
  - **DDD Value Object** — `UserId`, `MissionId`, `PostId`로 식별자 타입 안전성 확보
  - **Facade 패턴**으로 AI 분석·미션 검증·이미지 생성 유스케이스 오케스트레이션

  **Troubleshooting**
  - **LAMA 인페인팅 가장자리 잔상** : YOLO bounding box를 그대로 mask로 사용하니 객체 경계에 흔적이 남는 문제 → 박스를 20px 확장 + `fillRoundRect` + AntiAliasing으로 **마스크 후처리** 적용하여 자연스러운 배경 복원 달성
  - **LAMA 서버 multipart 직렬화 실패** : 기본 `RestTemplate`이 binary mask + form 파라미터 동시 전송을 처리하지 못함 → `FormHttpMessageConverter` / `ByteArrayHttpMessageConverter` 를 등록한 **전용 RestTemplate 분리**로 해결
  - **Private S3 ↔ GPT-4 Vision 연동 불가** : 비공개 버킷이라 OpenAI가 이미지 URL을 직접 fetch 할 수 없는 문제 → S3에서 다운로드 후 **Base64 data URL** 로 변환해 전달, 보안과 AI 호출을 모두 만족
  - **OpenAI 429 장애 격리** : `HttpClientErrorException.TooManyRequests` 를 별도 캐치하여 `AI_RATE_LIMIT_EXCEEDED` **도메인 예외로 래핑**, 사용자에게 명확한 재시도 메시지 노출

  🔗 [GitHub](https://github.com/9ITHON/9-RoomGenie-BE) · [API Docs](https://config25.github.io/config25/)

  </details>

  <details>
  <summary>🌱 FutureFinder — 청년 맞춤형 금융·진로 통합 플랫폼</summary>

  > 청약·자산·취업·경제정보를 한 곳에 모아 청년에게 맞춤형 인사이트를 제공하는 통합 플랫폼

  - **Role**: 백엔드 개발 · 팀 5인
  - **Period**: 2025.08 ~ 2025.09 (이후 개인 리팩토링 진행)
  - **Tech**: Java 17, Spring Boot 3.5, Spring Security(JWT), JPA/MySQL(RDS), AWS S3, WebFlux WebClient, OpenAI

  **Key Features**
  - **홈 대시보드 통합 집계** — KRX 주식 급등락 Top3 + 네이버 경제 뉴스 + 공공기관 채용 공고를 단일 엔드포인트(`GET /api/home`)로 묶어 제공, `HomeFacade`로 이종 외부 데이터 조립
  - **주거 금융 관리 + AI 챗봇** — 청약 계좌·입금 내역·현재/관심 거주지 관리 + OpenAI 기반 주거 금융 Q&A 챗봇, 사용자별 대화 이력 영속화로 컨텍스트 연속성 확보
  - **AI 맞춤 취업 추천** — 학력·대외활동·수상 이력을 입력으로 OpenAI에 위임, 사용자 프로필 기반 추천 대외활동·채용 공고 산출
  - **경제 사전 + 카카오 OAuth** — 한국은행 ECOS 기반 경제 용어 검색·스크랩·인기 단어, 카카오 소셜 로그인 + JWT Access/Refresh 이중 토큰

  **Architecture**
  - **5개 멀티모듈**(api / domain / external / storage / common) 계층 분리, 의존 방향: `api → domain ← storage / external`
  - **CQRS 스타일 도메인 구현** — 서비스를 `Appender`·`Reader`·`Updater`·`Validator`·`Remover`로 분해해 단일 책임 강제
  - **Facade 오케스트레이션** — `HomeFacade`(이종 데이터 집계)·`AccountFacade`(회원/OAuth)·`AcademicFacade`로 유스케이스 조립, 컨트롤러는 얇게 유지
  - **DIP 적용** — domain은 `ExternalOAuthClient`·`ExternalNewsClient`·`ExternalStockClient`·`OpenAIService` 인터페이스에만 의존, 외부 벤더(카카오/네이버/ECOS/KRX/OpenAI) 교체 가능
  - **Value Object** — `UserId` 등 식별자 타입 안전성 + JPA Entity ↔ 도메인 모델 분리

  **Troubleshooting**

  - **외부 API 호출 폭증·지연 → TTL 캐시 레이어 도입** (`c07de21`)
    : 홈 대시보드 한 번 호출 시 KRX·네이버·공공채용 API가 동시에 트리거되어 응답 지연이 누적되고, 일일 쿼터 한도까지 위협. 키워드·날짜 단위로 응답이 거의 동일함에도 매 요청마다 외부를 직접 때리는 설계가 원인.
    → 외부 클라이언트 앞단에 **`TtlCache` 레이어**를 도입해 동일 키 요청을 메모리에서 흡수, 외부 호출 빈도와 응답 시간을 동시에 절감.

  - **External 모듈 800여 줄 중복 제거** (`c07de21`)
    : 6개 외부 API 클라이언트가 각자 HTTP 전송·JSON 파싱·HTML 메타 스크래핑·캐싱 로직을 **개별 보유**해, `ExternalNewsClientImpl`이 ~400줄까지 비대해지고 동일 버그를 여러 파일에서 반복 수정.
    → 공통 책임을 `ArticleMetaScraper` / `GovApiJsonParser` / `ExternalClientUtils` / `TtlCache` **4개 유틸로 추출**하고 설정값을 `*Properties` 클래스로 분리. **News -309 / JobAI -254 / Recruitment -176 / Stock -102 줄** 슬림화.

  - **컨트롤러 비대화 — 도메인 로직 누수 해소** (`c07de21`)
    : `HouseController` / `JobController`에 비즈니스 분기·DTO 조립·Repository 직접 호출이 박혀 있어 **재사용·단위 테스트가 모두 불가능**.
    → 로직을 `HouseService` / `JobService`로 이동, 컨트롤러는 인증·요청 검증·응답 변환만 담당하는 얇은 계층으로 정리(컨트롤러 -130여 줄). 이후 `HomeFacade` 같은 조합 유스케이스에서 동일 서비스를 재사용 가능해짐.

  🔗 [GitHub](https://github.com/9oormthon-univ/2025_SEASONTHON_TEAM_85_BE)

  </details>

  ## 📫 Contact

  [![Blog](https://img.shields.io/badge/Blog-grey?style=flat-square)](https://velog.io/@yhkim0525/posts)
  [![Email](https://img.shields.io/badge/Email-yhkim052556@gmail.com-blue?style=flat-square)](mailto:yhkim052556@gmail.com)
