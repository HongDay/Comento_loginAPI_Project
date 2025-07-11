# Week 2 실습 노트



### 업무기록 노션 정리 페이지
[**2주차. API문서 초안 작성 - 중간업무보고**](https://www.notion.so/2-22a7d817ab0a80928752c192b7e8f0b2?source=copy_link)

[**정리된 개인 기술 블로그1**](https://velog.io/@hongday/BE입문-REST-API와-HTTP)

[**정리된 개인 기술 블로그2**](https://velog.io/@hongday/BE-입문-오픈소스-API-명세서-둘러보기)

[**SW 활용 현황 API (초안)**](https://github.com/HongDay/Comento_loginAPI_Project/blob/API_first/SW_API_draft.pdf)


## 업무 정의

**[API 초안 작성]** FE 개발자와의 협업을 위한 SW 활용 현황 통계 API 가이드 초안 작성

- Restful API에 대한 학습 및 공공데이터 API 문서 및 제공된 인터페이스 가이드 참고하여 SW 활용 현황 통계 API 문서 초안을 작성
- SW활용률(접속자 수, 부서별 접속자 수, 로그인 요청 수, 게시글 작성 수)에 필요한 데이터가 무엇일 지 고민해보고 해당 내용에 맞게 문서를 작성(요청 파라미터 생각, 응답 데이터 포맷 고려)

## ✅ Task To-do
- [x]  REST, REST API, RESTful 학습
    - HTTP 통신
    - 브라우저에 URL 입력 후 요청하여 서버에서 응답하는 과정
- [x] 공공데이터 API 문서 및 제공된 인터페이스 가이드 숙지
- [x] 인터페이스 (API) 가이드 문서 초안 작성


**업무 진척도 100%**

### 1️⃣ 학습한 개념
- REST란?
- API란?
- RESTful이란?
- REST API 동작과정 
- REST API 구성요소
- HTTP 프로토콜 기본
- 브라우저 URL 입력, 서버 요청, 서버 응답의 일련과정

### 2️⃣ 실습 기록
- REST, REST API, RESTful 학습 완료
- 6개의 샘플 API 문서 및 제공된 인터페이스 가이드 숙지 완료
- SW 접속자 통계를 주제로 API 문서 초안 작성 완료

### 3️⃣ 어려웠던 점
- HTTP 방식에서, request시 parameter와 바디, 헤더 각각의 기능의 차이를 이해하는 데 시간이 조금 걸렸습니다.
- 각 HTTP method를 이해하고 API로의 구현을 생각하는 과정이 조금 tricky 했습니다.


### 4️⃣ 개선/다음 학습 내용
- 파라미터 종류, 헤더, 바디와의 차이점, URL기재 방식의 차이 등등 이해한 개념 정리.
- 초안 API 문서 피드백 반영 및 정리.

### ❓멘토님께 질문할 내용
요청시, “URL 파라미터”(경로 파라미터, 쿼리 파라미터)로서 필요한 데이터, “바디”로서 필요한 데이터, “헤더”(헤더 파라미터)에 필요한 데이터(인증토큰, id등) 은 어떻게 구분해서 기재하는게 적합할까요?
