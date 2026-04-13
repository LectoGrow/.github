# 강사 역량 강화 솔루션 LectoGrow

## 프로젝트 소개 

강의 녹음과 자료를 업로드하면 AI가 음성과 슬라이드를 교차 분석하여 강사에게 피드백을 제공하는 강사 역량 강화 솔루션입니다.

## 라이브 링크

https://lectogrow-web.vercel.app?_vercel_share=c3kJYArHU7tWsqibayW3KCClR25hkMdX

## 레포지토리 링크

lectogrow-web: https://github.com/LectoGrow/lectogrow-web </br>
lectogrow-ai: https://github.com/LectoGrow/lectogrow-ai


## 기술 스택

**FullStack**: Next.js, TypeScript </br>
**AI**: FastAPI, Python, OpenAI </br>
**Infra**: EC2, SQS, supabase

## 아키텍쳐

<img width="3680" height="1880" alt="image" src="https://github.com/user-attachments/assets/62e986e5-b866-4248-a212-e24a4313e202" />

## 주요기능

강의 업로드
- 강의 녹음 파일(mp3)과 슬라이드(PDF)를 업로드
- 업로드 후 분석이 백그라운드에서 자동 실행

발표 전달력 분석
- 말하기 속도 측정
- 반복 표현 감지
- 핵심 내용 누락 구간 식별
- 강점 구간 하이라이트
- 피드백 제공

슬라이드 커버리지 분석
- 슬라이드별 설명 충분도 평가 (충분 / 부족 / 미언급)
- 전체 슬라이드 커버리지 현황 시각화

AI 개선 제안
- 슬라이드별 내용 보완 제안
- 예시 추가 및 구조 개선 추천

종합 리포트 대시보드
- 커버리지 수치, 전달력 이슈, 제안 수 요약
- 슬라이드 이미지 + 분석 결과 통합 뷰

## 테스트 시나리오

1. 회원가입 혹은 테스트 아이디를 통해 로그인
```
Emali address: test+clerk_test@example.com
Password: clerk_test
```
2. 강의 업로드 클릭
3. 테스트용 녹음 파일 및 강의자료 파일 업로드 </br>
[digital_literacy.mp3](https://github.com/user-attachments/files/26676052/digital_literacy.mp3)</br>
[digital_literacy.pdf](https://github.com/user-attachments/files/26676050/digital_literacy.pdf)

4. 분석 리포트 보기

