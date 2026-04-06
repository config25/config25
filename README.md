# Backend Developer                                                                                                                                                                                                                                                                                                                                                                                             
  <p align="center">                                                                                                                                                                                     
    <b>저사양 환경에서의 성능 최적화부터 확장성 있는 구조까지, 동작하는 코드 너머의 문제를 해결하는 백엔드 개발자입니다.</b>                                                                               </p>                                                                                                                                                                                                   
                                                                                                                                                                                                         
  ## 👋 About Me                                        

  1GB 메모리 서버에서 JVM 튜닝을 해본 경험부터, 멀티모듈 구조 설계와 AI 파이프라인 연동까지 — "동작하는 코드" 너머의 문제를 고민합니다.
  Spring 생태계 기반 백엔드 개발과 클라우드 인프라에 관심이 많습니다.

  ## 📊 Stats

  <p align="center">
    <img src="https://github-readme-stats.vercel.app/api?username=config25&show_icons=true" height="150"/>
    <img src="http://mazassumnida.wtf/api/v2/generate_badge?boj=yhkim0525" height="150"/>
  </p>

  ## 🌐 Open Source Contributions

  ### spring-projects/spring-batch

  | Issue | Description | Related PR |
  |-------|-------------|------------|
  | [#5366](https://github.com/spring-projects/spring-batch/issues/5366) | `ExitStatus#setExitException` breaks immutability contract |[#5367](https://github.com/spring-projects/spring-batch/pull/5367) |

  ## 🧰 Tech Stack

  <p>
  <img src="https://img.shields.io/badge/Java-17-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/Kotlin-purple?style=flat-square"/>
  <img src="https://img.shields.io/badge/Spring Boot-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Spring Security-brightgreen?style=flat-square"/>
  <img src="https://img.shields.io/badge/JPA-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/WebSocket-lightgrey?style=flat-square"/>
  <br>
  <img src="https://img.shields.io/badge/MySQL-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/MongoDB-green?style=flat-square"/>
  <br>
  <img src="https://img.shields.io/badge/AWS-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/Docker-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/GitHub Actions-black?style=flat-square"/>
  </p>

  ## 🏆 Achievements

  * 🥇 2023 전국 대학생 SW창업 아이디어톤 **결선 진출**
  * 🥈 2025 한양대 캡스톤 디자인 **우수상**
  * 🥈 2025 9ITHON **우수상 (2위)**

  ## Experience

  * 🏢 (주)퀀텀에듀솔루션 현장실습 (2025.09 ~ 2026.02)
  * 🌱 구름톤 유니브 4기 백엔드

  ## 🚀 Projects

  <details>
  <summary>🎨 Impact Design Canvas — AI 기반 성과 설계 교육 플랫폼</summary>

  > 교육 현장에서 학습 성과를 설계하고 관리하는 AI 기반 플랫폼

  - **Role**: 풀스택 단독 개발
  - **Period**: 2025.09 ~ 2026.02
  - **Tech**: Spring Boot, MariaDB, GitHub Actions CI/CD

  - **Focus**
    - CQRS(Reader/Appender) 패턴 기반 도메인 계층 설계
    - 역할 기반 인증 체계 구현 (Spring Security + JWT)
    - 1GB 메모리 서버 환경에서 JVM/HikariCP/Tomcat 튜닝 (힙 512MB, 커넥션 풀 5개 등)

  🔗 [back](https://github.com/config25/Impact-design-back)
  🔗 [front](https://github.com/config25/Impact-design-front)
  🔗 [API Docs](http://iptdesign.mycafe24.com/docs/index.html)

  </details>

  <details>
  <summary>💬 드르륵 (AI 메신저) — SNS + AI 기반 실시간 채팅 서비스</summary>

  > 친구와의 대화를 AI가 학습하여, 부재중에도 AI 클론이 대신 응답하는 메신저 서비스(iOS 출시)

  - **Role**: 백엔드 개발 · 팀 4인
  - **Period**: 2024.09 ~ 2025.06
  - **Tech**: Kotlin, Spring Boot, WebSocket, MongoDB, MySQL

  - **Focus**
    - WebSocket + STOMP 기반 실시간 채팅 아키텍처 설계
    - MySQL(사용자/관계) + MongoDB(채팅 메시지) 다중 DB 구조 설계
    - 멀티모듈 기반 서버 구조 및 AI 클론 응답 파이프라인 연동

  🔗 [GitHub](https://github.com/Chewing-Chat)
  🔗 [API Docs](https://drr.kro.kr/docs/index.html)

  </details>

  <details>
  <summary>🧹 RoomGenie — AI 이미지 기반 방 정리 서비스</summary>

  > AI가 방 사진을 분석하여 정리 방법을 제안하는 서비스

  - **Role**: 백엔드 개발 · 팀 4인
  - **Period**: 2025.05 ~ 2025.07
  - **Tech**: Spring Boot, Java, JPA, S3, OpenAI, YOLO, LAMA

  - **Focus**
    - 6개 멀티모듈(api/domain/storage/external/common/api-docs) 기반 계층 분리
    - Facade 패턴으로 AI 분석·미션 검증·이미지 생성 유스케이스 오케스트레이션
    - YOLO(객체감지) + LAMA(인페인팅) + GPT Vision 3종 AI 파이프라인 연동
    - CompletableFuture 기반 파일 업로드 병렬 처리

  🔗 [GitHub](https://github.com/9ITHON/9-RoomGenie-BE)

  </details>

  <details>
  <summary>🌱 FutureFinder — 청년 맞춤형 금융·진로 통합 플랫폼</summary>

  > 청년 정책·금융 데이터를 통합하여 맞춤형 추천을 제공하는 플랫폼

  - **Role**: 백엔드 개발 · 팀 5인
  - **Period**: 2025.08 ~ 2025.09
  - **Tech**: Spring Boot, JWT, AWS, OpenAI

  - **Focus**
    - 5개 멀티모듈(api/domain/storage/external/common) 계층 분리 설계
    - 6개 외부 API 연동 (카카오 OAuth, 네이버 뉴스, 한국은행 ECOS, KRX, 공채, OpenAI)
    - TTL 캐싱 기반 외부 API 응답 최적화
    - CQRS 스타일(Appender/Reader/Updater/Remover) 도메인 구현

  🔗 [GitHub](https://github.com/9oormthon-univ/2025_SEASONTHON_TEAM_85_BE)

  </details>

  ## 📫 Contact

  [![Blog](https://img.shields.io/badge/Blog-grey?style=flat-square)](https://your-blog-url)
  [![Email](https://img.shields.io/badge/Email-yhkim052556@gmail.com-blue?style=flat-square)](mailto:yhkim052556@gmail.com)
