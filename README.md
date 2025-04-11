# 🧠 Coding Test Study Platform

## 🔍 프로젝트 개요
IT 동아리 내에서 코딩 테스트 문제 풀이를 효율적으로 공유하고 검색할 수 있는 웹 플랫폼입니다. 기존 노션 기반 공유 방식의 불편함을 해결하고자 시작했으며, 실시간 문제 검색 및 코드 저장, 공유 기능을 제공합니다.

## 🚀 기술 스택
- **Frontend:** React.js, React Router, React Query, Styled Components
- **Backend:** Python Django, MySQL (with solved.ac API 연동)
- **기타:** GitHub, Notion

## ⚙️ 주요 기능
- 실시간 문제 검색 (solved.ac API 기반)
- 코드 업로드 및 팀원 간 공유
- 문제 필터 및 즐겨찾기 기능
- 사용자 편의 중심의 UI 구성

## 📌 프론트엔드 성능 최적화
- `useDebounce`로 검색 시 비동기 요청 최소화
- React Query를 통한 데이터 캐싱 및 상태 관리
- `React.memo`로 불필요한 렌더링 방지
- 코드 스플리팅 적용 (React Router Lazy)

## 📈 성과 및 해결한 문제
- 기존 크롤링 방식의 서버 과부하 문제를 API 연동으로 해결
- 실시간 검색 속도 3배 이상 향상
- API 요청 최적화로 UX 개선
- 팀 내 API 명세 정의 및 프론트-백 통신 구조 설계

## 👨‍👩‍👧‍👦 협업 방식
- GitHub Issues 및 PR 리뷰를 통한 코드 관리
- API 명세 문서 공동 작성 및 버전 관리

