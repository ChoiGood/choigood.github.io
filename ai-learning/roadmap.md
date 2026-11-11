---
layout: default
title: "AI Learning Roadmap - 12주 AI 학습 계획"
date: 2026-11-12
categories: [AI Learning]
tags: [AI, Learning Roadmap, Python, LLM, RAG, AI Agent]
permalink: /ai-learning-roadmap/
---

# AI Learning Roadmap - 12주 AI 학습 계획

## 1. 학습을 시작하는 이유

지금까지 ChatGPT와 같은 생성형 AI를 활용해 코드를 작성하거나 오류를 분석하고, 프로젝트의 문제를 해결하는 데 도움을 받아 왔다.

태양광 발전량 예측 프로젝트에서는 AI를 활용해 데이터 전처리와 모델 개선 방향을 탐색했고, Unity 게임 개발 과정에서는 코드 작성과 디버깅 등에 활용했다.

하지만 AI를 활용해 본 경험과 AI가 어떻게 동작하는지 이해하고 직접 시스템을 개발할 수 있는 능력은 다르다고 생각했다.

앞으로는 AI를 단순히 사용하는 것에서 한 걸음 더 나아가, AI의 기본 원리를 이해하고 실제 프로그램과 서비스를 개발할 수 있는 역량을 기르고자 한다.

## 2. 최종 학습 목표

이번 학습의 최종 목표는 AI 활용, AI 응용 프로그램 개발, AI 시스템 제작을 단계적으로 경험하는 것이다.

### 목표 1. AI를 이해하고 효과적으로 활용하기

- AI와 머신러닝, 딥러닝의 기본 개념 이해
- LLM의 작동 원리 이해
- Prompt Engineering과 Context Engineering 학습
- AI의 답변을 검증하고 평가하는 습관 형성

### 목표 2. AI 응용 프로그램 개발하기

- Python 기초 및 프로그램 구조 학습
- HTTP, REST API, JSON 이해
- LLM API를 활용한 프로그램 개발
- 대화 기록과 응답 형식 관리

### 목표 3. AI 시스템 직접 제작하기

- RAG의 구조와 검색 방식 이해
- 외부 도구를 사용하는 Tool Calling 학습
- AI Agent와 Workflow의 차이 이해
- 오류 처리, 평가, 보안 및 안정성 고려
- 여러 기능을 결합한 AI 미니 프로젝트 제작

## 3. 12주 학습 로드맵

| 기간 | 학습 주제 | 주요 학습 내용 | 결과물 |
|---|---|---|---|
| 1~2주 | AI와 LLM 기초 | LLM, Token, Transformer, Prompt Engineering, Context Engineering | 프롬프트 실험 기록 |
| 3~4주 | Python과 AI API | Python, HTTP, REST API, JSON, API Key, 대화 상태 관리 | 간단한 AI 도우미 |
| 5~6주 | RAG | Embedding, Chunking, Vector Search, 검색 결과 평가 | 문서 기반 질의응답 프로그램 |
| 7~8주 | Tool Calling과 Agent | 함수 호출, 도구 연결, Workflow, Agent, MCP 기초 | 여러 도구를 사용하는 AI 도우미 |
| 9~10주 | 평가와 안정성 | 테스트, 정확도 평가, 환각, Prompt Injection, 개인정보, 로그 | AI 평가 및 개선 보고서 |
| 11~12주 | 종합 프로젝트 | API, RAG 또는 Tool Calling, 평가, 오류 처리 통합 | GitHub 공개 미니 프로젝트 |

## 4. 주차별 학습 내용

### 1단계. AI와 LLM의 이해 (1~2주)

AI가 어떤 원리로 동작하고, 어떻게 질문해야 원하는 결과를 얻을 수 있는지 학습한다.

- AI, 머신러닝, 딥러닝, 생성형 AI의 관계
- LLM과 다음 토큰 예측 원리
- Token과 Context Window
- Transformer와 Attention
- Prompt Engineering
- Context Engineering
- AI 답변 검증 및 평가

**학습 결과물:** 프롬프트 실험 기록과 LLM 작동 원리 정리

### 2단계. Python과 AI API 활용 (3~4주)

AI를 실제 프로그램에서 호출하고 활용하는 방법을 학습한다.

- Python 문법과 자료구조
- 함수, 클래스, 예외 처리
- HTTP와 REST API
- JSON 데이터 처리
- API Key와 환경변수 관리
- LLM API 호출
- 대화 기록 및 응답 관리
- 구조화된 출력 처리

**학습 결과물:** Python 기반 간단한 AI 도우미

### 3단계. RAG 시스템 개발 (5~6주)

AI가 외부 문서를 참고해 답변할 수 있도록 검색 기능을 결합하는 방법을 학습한다.

- RAG의 개념과 전체 구조
- 문서 수집과 전처리
- Chunking
- Embedding
- Vector Search
- 검색 결과와 답변 품질 평가
- 출처를 포함한 답변 생성

**학습 결과물:** 문서를 기반으로 질문에 답하는 프로그램

### 4단계. Tool Calling과 AI Agent (7~8주)

AI가 단순히 답변을 생성하는 것을 넘어 외부 도구를 활용하도록 만드는 방법을 학습한다.

- Tool Calling과 Function Calling
- 함수 및 외부 도구 연결
- AI Workflow
- Agent의 개념과 동작 방식
- 상태 관리와 오류 처리
- MCP의 기본 개념

**학습 결과물:** 검색이나 계산 등의 도구를 사용할 수 있는 AI 도우미

### 5단계. AI 시스템의 평가와 안정성 (9~10주)

AI 시스템을 실제로 사용할 때 발생할 수 있는 문제를 파악하고 개선하는 방법을 학습한다.

- 테스트 케이스 작성
- 답변 품질과 정확도 평가
- 비용과 응답 속도 측정
- Hallucination 대응
- Prompt Injection과 보안
- 개인정보 보호
- 로그와 모니터링
- 사람의 검토가 필요한 상황 구분

**학습 결과물:** AI 시스템 테스트 및 개선 보고서

### 6단계. 종합 미니 프로젝트 (11~12주)

앞서 학습한 내용을 하나의 프로그램으로 통합한다.

- 프로젝트 주제 선정
- 시스템 구조 설계
- LLM API 연결
- RAG 또는 Tool Calling 적용
- 예외 처리와 검증 기능 추가
- 테스트 및 개선
- README와 사용 방법 작성
- GitHub에 프로젝트 정리

**학습 결과물:** 직접 개발한 AI 미니 프로젝트

## 5. 하루 학습 시간과 진행 방식

하루 최소 1시간 30분 이상 학습하는 것을 목표로 한다.

| 학습 단계 | 시간 | 내용 |
|---|---:|---|
| 개념 학습 | 20분 | 핵심 개념과 원리 이해 |
| 예제 확인 | 20분 | 공식 문서와 예제 코드 살펴보기 |
| 실습 | 40~60분 | 직접 작성하고 실행하며 확인 |
| 검증 | 15분 | 결과 비교, 오류 확인, 추가 질문 |
| 학습 기록 | 10분 | 블로그에 배운 내용과 회고 정리 |

개념만 공부하거나 코드를 무작정 따라 하는 방식보다는 개념을 이해한 뒤 직접 실습하고 결과를 확인하는 방식을 유지한다.

일주일에 6일은 학습과 실습을 진행하고, 하루는 복습과 정리에 활용한다.

## 6. 학습 기록 원칙

매일 학습한 내용을 GitHub 블로그에 기록한다.

단순히 개념을 복사해서 정리하는 것이 아니라 직접 공부하고 시도한 내용을 중심으로 작성한다.

- 학습한 개념과 원리
- 직접 작성한 프롬프트와 코드
- 실습 과정과 결과
- 오류와 해결 과정
- AI가 제안한 내용 중 직접 검증한 부분
- 학습하면서 느낀 점과 다음 과제

특히 AI를 활용한 실습에서는 실제 사용한 프롬프트와 개선한 프롬프트를 함께 기록해 나중에 비교할 수 있도록 한다.

## 7. 12주 이후의 학습 방향

12주 학습을 마친 후에는 다음 세 방향으로 학습을 확장하고자 한다.

1. **AI Engineering:** 머신러닝과 딥러닝의 수학적 원리, 모델 학습 및 최적화
2. **AI Application Development:** LLM API, RAG, Agent, MCP를 활용한 응용 프로그램 개발
3. **Game Development + AI:** Unity 게임 개발과 AI를 결합한 기능 및 개발 도구 제작

최종적으로는 AI를 효과적으로 활용하는 능력뿐 아니라, 필요한 AI 시스템을 직접 설계하고 개발할 수 있는 역량을 갖추는 것을 목표로 한다.

---

**Learning Progress:** Roadmap established  
**Current Stage:** Week 1 - AI와 LLM의 기초