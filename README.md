# Ontology Feedback Loop

## Core Idea

```text
Postman Experiment
-> Feedback
-> Refactoring
-> Portfolio Improvement
```

This repository records how ontology-based AI system ideas are tested, reviewed, improved, and converted into portfolio evidence.

It is not the repository for the final ontology structure itself.
That role belongs to [ontology](https://github.com/ai-agent-orchestrator/ontology).

This repository focuses on the improvement loop:

```text
market observation
-> ontology hypothesis
-> Postman experiment
-> result record
-> feedback
-> structure revision
-> portfolio improvement
```

## Why This Repository Exists

An AI Technical PM should not only present a finished idea.
The stronger evidence is the process of testing, observing, correcting, and improving the structure.

For this project, Postman is not just an API testing tool.
It is the learning instrument for building operational sense.

```text
I test normal requests.
I test risky requests.
I test repeated attacks.
I test cost blocks.
I test privacy masking.
I check reasonCode.
I check Prometheus metrics.
I update the portfolio based on evidence.
```

## Portfolio Feedback Loop

### Portfolio V1

```text
Postman 1st experiment
-> result record
-> feedback
-> portfolio v1
```

Purpose:

- Verify that the basic Legal Intake Form works.
- Check whether selected values are converted into a clear case summary.
- Test basic Fixed Guard scenarios.
- Confirm that reasonCode appears when a request is blocked.
- Record first evidence for the portfolio.

Expected experiments:

- Normal minimal legal intake request
- Jailbreak blocking
- Prompt injection blocking
- Legal harm blocking
- Secret/API key request blocking
- Privacy output masking
- Simple cost limit blocking

Output to be updated later:

- Postman screenshots
- Response examples
- reasonCode examples
- first README/portfolio summary

### Portfolio V2

```text
Postman 2nd experiment
-> missing guard / metric / UX improvement
-> feedback
-> portfolio v2
```

Purpose:

- Find weak points after the first experiment.
- Improve missing guard logic.
- Add or refine Prometheus metrics.
- Improve UX wording in the intake response.
- Check whether the system explains blocked requests clearly.

Expected experiments:

- Repeated risky request with the same sessionId
- Dynamic Guard score increase
- Cost Control with intentionally small token limits
- Privacy masking with names, phone numbers, resident registration numbers, account numbers, and emails
- Intake UX response quality check
- Metric count check after each blocked scenario

Output to be updated later:

- Before/after comparison
- Improved reasonCode table
- metric list
- UX feedback notes
- portfolio v2 summary

### Portfolio V3

```text
Postman 3rd experiment
-> presentation evidence cleanup
-> feedback
-> portfolio v3
```

Purpose:

- Organize final evidence for presentation.
- Show that the project is not just a chatbot, but an observable AI security architecture.
- Connect product value, ontology structure, security control, and metrics into one clear story.

Expected experiments:

- Normal intake flow from client input to chatbot summary
- Fixed Guard block example
- Dynamic Guard repeated attack block example
- Cost Control block example
- Privacy Output Guard masking example
- Prometheus metric evidence
- Audit/reasonCode evidence

Output to be updated later:

- Final Postman evidence set
- Mermaid security flow
- dashboard screenshot or metric capture
- portfolio v3 document
- presentation summary

## Feedback Loop Table

| Phase | Experiment | Feedback Focus | Portfolio Output |
| --- | --- | --- | --- |
| V1 | First Postman test | Does the basic structure work? | Initial evidence and basic portfolio |
| V2 | Second Postman test | What guard, metric, or UX is missing? | Improved structure and clearer evidence |
| V3 | Third Postman test | Is this presentation-ready? | Final portfolio story and evidence |

## Korean Version

## 핵심 개념

```text
Postman 실험
-> Feedback
-> Refactoring
-> Portfolio 개선
```

이 저장소는 온톨로지 기반 AI 시스템 아이디어를 실험하고, 피드백을 반영하고, 구조를 수정하고, 포트폴리오 증거로 발전시키는 과정을 기록합니다.

최종 온톨로지 구조 자체를 보여주는 저장소는 아닙니다.
최종 구조는 [ontology](https://github.com/ai-agent-orchestrator/ontology)에 정리합니다.

이 저장소는 개선 루프에 집중합니다.

```text
시장 관찰
-> 온톨로지 가설
-> Postman 실험
-> 결과 기록
-> feedback
-> 구조 수정
-> portfolio 개선
```

## 이 저장소의 역할

AI Technical PM은 완성된 아이디어만 보여주는 사람이 아닙니다.
더 강한 증거는 직접 실험하고, 관찰하고, 고치고, 구조를 개선하는 과정입니다.

이 프로젝트에서 Postman은 단순 API 테스트 도구가 아닙니다.
AI 보안 서버의 흐름을 몸으로 익히는 학습 도구입니다.

```text
정상 요청을 테스트한다.
위험 요청을 테스트한다.
반복 공격을 테스트한다.
비용 차단을 테스트한다.
개인정보 마스킹을 테스트한다.
reasonCode를 확인한다.
Prometheus metric을 확인한다.
증거를 바탕으로 포트폴리오를 개선한다.
```

## 포트폴리오 개선 루프

### Portfolio V1

```text
Postman 1차 실험
-> 결과 기록
-> feedback
-> portfolio v1
```

목적:

- Legal Intake Form의 기본 흐름이 동작하는지 확인합니다.
- 선택값이 사건 요약으로 정리되는지 확인합니다.
- 기본 Fixed Guard 시나리오를 테스트합니다.
- 차단된 요청에 reasonCode가 나오는지 확인합니다.
- 포트폴리오 1차 증거를 기록합니다.

결과물은 나중에 업데이트합니다.

### Portfolio V2

```text
Postman 2차 실험
-> 부족한 guard / metric / UX 보완
-> feedback
-> portfolio v2
```

목적:

- 1차 실험 후 부족한 부분을 찾습니다.
- guard 로직의 빈틈을 보완합니다.
- Prometheus metric을 추가하거나 정리합니다.
- intake 응답 문구와 UX를 개선합니다.
- 차단 사유가 사용자와 운영자에게 설명 가능한지 확인합니다.

결과물은 나중에 업데이트합니다.

### Portfolio V3

```text
Postman 3차 실험
-> 발표용 증거 정리
-> feedback
-> portfolio v3
```

목적:

- 발표용 최종 증거를 정리합니다.
- 이 프로젝트가 단순 챗봇이 아니라 관측 가능한 AI 보안 아키텍처임을 보여줍니다.
- 제품 가치, 온톨로지 구조, 보안 통제, metric을 하나의 이야기로 연결합니다.

결과물은 나중에 업데이트합니다.

## 핵심 메시지

```text
Postman 실험은 단순 API 호출 확인이 아니다.
정상 요청, 위험 요청, 반복 공격, 비용 차단, 개인정보 마스킹을 직접 검증하면서
AI 보안 서버의 흐름을 몸으로 익히는 학습 루프다.
```

## Related Repository

- [ontology](https://github.com/ai-agent-orchestrator/ontology)  
  Applied legal and medical ontology design for domain-aware AI intake systems.
