## 👋 명혜성 — 백엔드 개발자

서비스의 성장과 궤를 같이하는 백엔드 개발자입니다.
Java · Spring Boot로 웹 서비스를 만들어 18개월간 실사용자 대상으로 운영했고, 성장 단계에 맞춰 AWS · Kubernetes 인프라까지 함께 다룹니다.


## 📈 백엔드 성과

- **18개월 실사용자 운영** — Crane 예약 서비스 · 누적 사용자 약 190명 · 누적 예약 약 1,700건
- **쿠폰 비정상 실패 89.0% → 0%** — 낙관적 락 실패의 원인을 MySQL 데드락으로 규명 · 개선 후 재실험 · TRIPLAN
- **조회 처리 초당 0.8 → 85건** — 조회 경로의 같은 행 쓰기 · 느린 커밋 규명, 조회수 지연 반영 · 재실험(실험 브랜치 검증) · Crane
- **예약 알림 누락률 약 10% → 1%** — 발송 · 수신 대조로 수신 경로 결함 3건 수정(부하 주입 기준) · Crane

## ☁️ 인프라 성과

- **DB 무중단 이전 단독 수행** — 운영 중인 PostgreSQL을 RDS로, 컷오버 중 에러율 0% · 데이터 유실 0건 · Devths
- **배포 반영 약 20분 → 5~8분** — 이미지 · GitOps(ArgoCD) 전환(공동) · Devths
- **관측 · 알림** — PLG 대시보드 7개 · 2단계 Discord 알림(공동) · Devths

## 🤖 개인 AI 인프라 (2026.08 ~ 운영 중)

- [local-llm-setup](https://github.com/Hyeseong-Myeong/local-llm-setup) — 폐쇄망 대응 로컬 LLM 스택. 게이트웨이 뒤 용도별 모델 라우팅 · PLG 관측
- [hyeseongkit](https://github.com/Hyeseong-Myeong/hyeseongkit) — 여러 AI 툴 사이의 작업 상태를 잇는 세션 허브(CLI · MCP, NAS 운영)

<br />

## 📂 프로젝트

| 프로젝트 | 한 줄 요약 | 대표 성과 |
|---|---|---|
| [Crane](https://github.com/CraneWebProject/Crane_Web_Backend_v3) · 2024.06 – 2025.12 | 동아리 예약 서비스 — 백엔드 · 프론트 · 인프라 전체, Kafka 알림 · 배치 · MSA 전환 | 18개월 실사용자 운영 |
| [TRIPLAN](https://github.com/SCDY-OSNM/triplan_backend) · 2025.01 – 2025.03 | 여행 계획 · 예약 웹 — Spring Cloud MSA 골격 · Gateway JWT 인증 · 쿠폰 · 검색 | 쿠폰 비정상 실패 89.0% → 0%(재실험) |
| [Devths](https://github.com/Hyeseong-Myeong/9-team-Devths-CLOUD) · 2026.01 – 2026.03 | 개발자 취업 AI 플랫폼 — 클라우드 인프라(EC2 → 3-Tier → K8s) · GitOps · 관측 | DB 무중단 이전 단독 · 에러율 0% |

📄 포트폴리오: <!-- 확인 필요: 포트폴리오 PDF 공개 링크 -->

<br />

## 🛠️ Tech Stack

**Backend**

<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" /> <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" /> <img src="https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" /> <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" /> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
<!-- FastAPI: 리뷰 C-5 로 skills.yaml 굵은 표시를 해제하면 이 배지도 삭제 -->

**Infra · Observability**

<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" /> <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" /> <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" /> <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" /> <img src="https://img.shields.io/badge/Loki-F5A623?style=for-the-badge" /> <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" />

**AI**

<img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" />

그 밖에 쓴 것: Kotlin · WebFlux · Spring Cloud Gateway · JPA · QueryDSL · Redis · Elasticsearch · Docker · Helm · ArgoCD · Jenkins · GitHub Actions · k6 · Locust · React · LangGraph · ChromaDB · MCP

<br />

## 🎓 Education

- **카카오 테크 부트캠프 3기** · 클라우드네이티브 과정 (2025.09 – 2026.03 수료)
- **순천향대학교** 사물인터넷학과 졸업 (2018.03 – 2024.02)

## 📫 Contact

<a href="mailto:dev.hyeseong@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a> <a href="https://velog.io/@hyeseong-int/posts"><img src="https://img.shields.io/badge/Velog-20C997?style=for-the-badge&logo=velog&logoColor=white" /></a>
