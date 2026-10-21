# 이승훈｜제작·데이터 분석 포트폴리오

[日本語](README.md) · [화면으로 보는 포트폴리오](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/ko/) · [생성 AI 활용 제작 기록](docs/ai-development-process.ko.md)

주변의 문제를 요구사항으로 정리하고, 생성 AI를 활용한 제작과 Python·SQL·Power BI 데이터 분석·검증을 결합해 왔습니다. 전체 12개 제작·분석·학습 기록과 사용 데이터, 처리 흐름, 확인 결과를 안내합니다.

## 먼저 볼 네 프로젝트

| 프로젝트 | 만든 것·본인 역할 | 확인할 자료 |
|---|---|---|
| **BassLab** | 기초 훈련과 연주 확인을 연결한 개인 앱. 문제·요구사항·조작 흐름·실제 동작 확인을 맡고 코드 구현은 생성 AI에 요청. | [실제 화면·개발 과정](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/ko/works/basslab.html) / [제작 기록](docs/ai-development-process.ko.md#basslab) |
| **금융 뉴스 RAG** | 뉴스 검색·ETF 가격 계산·설명을 나눈 개인 프로젝트. 2025년 목적 설정·수집·설계·구현·확인·발표까지 혼자 진행하고 생성 AI 활용. | [사용 데이터·처리 흐름](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/ko/works/financial-rag.html#materials) / [현재 실행 결과](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/ko/results/financial-rag.html) |
| **재무지표 ML·SQL** | PER·PBR 등 특징 설계, 분류 실험, 주가표 SQL 변환. 학부 작업과 2026년 AI 지원 재평가·재실행을 구분해 공개. | [분석 과정](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/ko/works/financial-ml.html) / [지표·SQL 대조](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/ko/results/ml-sql.html) |
| **모의경영 BI** | 팀 수업의 결과 8회분을 202행으로 정리해 최종 발표용 Power BI 제작. 전처리·BI 제작 및 견본을 활용한 분담·진행 확인 담당. | [입력 예시·배분·발표 영상](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/ko/works/business-simulation-bi.html) |

### BassLab 실제 화면

![BassLab 악보 입력 화면](assets/basslab/score-editor.png)

① 곡명·템포 설정 → ② 리듬·줄·프렛 입력 → ③ 저장한 악보를 연습·녹음으로 연결합니다. 앱 화면은 한국어입니다.

[기초 훈련 화면](assets/basslab/training.png) · [녹음 결과 화면](assets/basslab/recording-results.png) · [제작·동작 확인 기록](docs/ai-development-process.ko.md)

## 사용 데이터에서 결과까지

| 프로젝트 | 입력 → 처리 → 결과 |
|---|---|
| BassLab | 악보 JSON·녹음 → 예정 시각과 음 후보 대응 → 확인할 구간 다시 듣기 |
| 금융 뉴스 RAG | 뉴스 요약·ETF 가격 → 검색·재정렬·종목/날짜 연결·변화율 계산 → 출처가 붙은 보고서 |
| 재무지표 ML·SQL | 재무표·조정 주가 → 전처리·역수 등 특징·분류·비교 → 지표와 원자료를 따라갈 수 있는 평가표 |
| 모의경영 BI | 0~7기 결과 보고서 → 기업·브랜드·시장·기수 공통 표, 판매비율 배분 → Power BI·발표 영상 |

[데이터 예시·코드/수식·결과 모아보기](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/ko/examples.html)

현재 공개 RAG 검색·가격 결과는 2026년 생성 AI의 지원을 받아 저장 데이터로 다시 실행한 것입니다. 이 실행에서는 LLM을 호출하지 않았습니다. 제작 당시 LLM 구성과 별도 입력의 AI 시험은 상세 페이지에서 구분합니다.

2026년 ML 재평가(검증 2,973건)에서 랜덤포레스트 정확도 55.36%는 항상 비상승을 예측하는 기준 55.87%보다 낮았습니다. 균형 정확도는 55.71% 대 50%입니다. 사전 상승 F1 기준에서는 항상 상승 예측이 선택됐습니다.

## 전체 12개 제작·분석·학습 기록

| 작업 | 작업 성격·본인 역할 |
|---|---|
| [BassLab · 베이스 연습 도구](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/ko/works/basslab.html) | 본인: 문제·요구사항·조작 흐름·동작 확인. 코드 구현에 생성 AI 활용. |
| [금융 뉴스 RAG](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/ko/works/financial-rag.html) | 2025년 전 과정 단독 제작, 생성 AI 활용. 공개 결과는 2026년 AI 지원 재실행. |
| [재무지표 ML · SQL](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/ko/works/financial-ml.html) | 본인의 전처리·특징 설계·모델 실험. 2026년 AI 지원 재평가와 구분. |
| [모의경영게임 데이터 시각화 · Power BI](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/ko/works/business-simulation-bi.html) | 팀 수업. 본인: 전처리·Power BI 제작, 정리 견본·분담·진행 확인. |
| [금융 뉴스 개체명 인식](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/ko/works/financial-ner.html) | 수업 예제·생성 AI 코드 기반 실습. 본인: 태그 설계·라벨링. |
| [ETF 모멘텀 백테스트 파이프라인](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/ko/works/quant-pipeline.html) | ETF 가격 처리, 점수 계산, 보유·매매 기록을 연결한 개인 구현. |
| [주식 데이터 정제 · MySQL 적재](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/ko/works/stock-etl.html) | 본인의 주가표 변환·SQL 작업. 공개 적재·대조 기록은 2026년 재실행. |
| [자산배분 전략 구현 실험](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/ko/works/asset-allocation.html) | 학습 실험. 난수 데이터·리밸런스 조건·초기 11개월 미래값 참조 문제 명시. |
| [주식 · 재무 데이터 수집 도구](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/ko/works/stock-collection.html) | 온라인 자료를 참고한 수집·데이터베이스 구성 실습. |
| [A쇼핑 고객 행동 통계 분석](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/ko/works/ashopping.html) | 수업 데이터를 이용한 고객 행동 통계분석 과제. |
| [Docker · Kubernetes 배포 기초](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/ko/works/docker-k8s.html) | 강의 기반 컨테이너·배포 실습. |
| [코딩 문제 풀이 · 프로그래밍 학습](https://seunghun-data-portfolio.lsrrokmv.chatgpt.site/ko/works/coding-study.html) | 프로그래밍·문제 풀이 학습 기록. |

## 코드 공개 상태

아래는 이전에 공개한 코드 발췌입니다. 현재 앱 전체나 2026년 재검증 코드 전체와 같은 판은 아닙니다. 현재 화면·입력 예시·결과는 위 프로젝트 페이지에서 확인할 수 있습니다.

- [BassLab 이전 코드 발췌](https://github.com/lshrecon/basslab-portfolio)
- [금융 뉴스 RAG 이전 코드 발췌](https://github.com/lshrecon/financial-news-rag-portfolio)
- [재무지표 ML·SQL 이전 코드 발췌](https://github.com/lshrecon/financial-ml-sql-portfolio)

이 저장소는 작업 모음과 제작 과정을 정리한 자료입니다. 2026년 10월 21일 업데이트. 공개 자료 출처는 [sources.json](sources.json)에 기록했습니다.
