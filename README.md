# 한화생명 보험 상담 AI 챗봇

Claude API를 활용한 한화생명 보험 상담 웹 챗봇입니다.

## 기능

- **고객 상담 모드**: 자연어로 보험 상품 안내, 맞춤 추천, 보험료 조회, 상품 비교
- **사내 업무 모드**: 인수심사 기준, 보험금 청구 절차, 민원 처리 규정 검색

## 사용법

1. `index.html`에서 `YOUR_ANTHROPIC_API_KEY` 부분을 실제 Anthropic API 키로 교체
2. `index.html` 파일을 브라우저에서 열기

## 기술 스택

- HTML / CSS / JavaScript (단일 파일)
- Claude API (Sonnet 4) - 스트리밍 응답
- 보험상품 데이터: products.json (8개 상품, 5개 고객 시나리오, FAQ, 사내규정)
