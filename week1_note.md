# Week 1 실습 노트



### 업무기록 노션 정리 페이지
[**1주차. 개발환경 세팅 - 최종업무보고**](https://www.notion.so/1-2257d817ab0a80ebb635f206c137195c?source=copy_link)


## 업무 정의

**[개발환경 세팅] '총 로그인 수 조회 API서비스'를 직접 구축하기 위한 개발환경 세팅하기.**

- Spring(5ver.), jdk, IntelliJ, java, spring Framework, mybatis, Tomcat, Spring MVC, API PING
- DB : mariaDB, DBeaver 
(DB의 경우 보통 AWS RDS url로 제공, 본 프로젝트에서는 localDB사용을 위해 mariaDB사용)

## ✅ Task To-do
- [x]  0.Github 리포지토리 생성 및 버전 관리 환경 세팅
- [x]  1.IntelliJ 설치 / JDK 설치
- [x]  2.MariaDB, DBeaver 설치 및 DB Connection
- [x]  3.Spring MVC 환경설정 & API PING
- [x]  4.datasource & mybatis 연동
 

- [x]  JDK, java 셋팅, Tomcat 알아보기
- [x]  Spring vs Spring Boot 의 차이점 간단하게 알아보기
- [x]  셋팅을 위해 알아야되는 개념들 전부 알아보기
- [ ]  API, Batch, Admin의 개념에 대해 간단하게 알아보기
- [ ]  완독할 스프링 책 고르고, 공부 시작

**업무 진척도 100%**

### 1️⃣ 학습한 개념
- Github 연동 및 버전 관리
- Spring, Spring MVC, Spring Boot의 개념과 차이
- Tomcat
- java, JDK 세팅
- MariaDB, DBeaver, AWS RDS url 방식
- API PING
- Datasource 와 MyBatis
- Jetty

### 2️⃣ 실습 기록
- Git을 이용해 로컬/원격 저장소 연결 및 버전관리 환경 세팅 완료
- IntelliJ - Ultimate 설치 완료
- Java, JDK 세팅 (javac 21.0.6), 관련 확장팩 설치 완료
- MariaDB, DBeaver 설치 및 DB connection 완료
  (statistic 데이터베이스 + 3개 테이블 생성 완료)
- Spring MVC 환경설정 & API PING 설정
- DataSource, MyBatis 연동

### 3️⃣ 어려웠던 점
- 세팅 관련하여 알아야될 기술과 프로그램이 많아서 공부가 오래걸렸습니다.
- 기존에 anaconda에 MySQL이 설치되어 있어서, MariaDB 설치 시, 문제를 찾고 해결했습니다.
- maven project 생성 시, maven 설치 및 버전에 맞는 dependency, properties 설치하기
- jetty, maven, ping controller간의 관계와 정확히 어떤 코드로 어떤 원리로 작동하는 것인지 이해도가 많이 부족
- Datasource, mybatis 연동 시 Controller 설정 오류 해결
- datasource.xml 파일에 MariaDB 유저정보 (username, password) 추가로 503 오류 해결

### 4️⃣ 개선/다음 학습 내용
- API, Batch, Admin 개념에 대해 공부하기
- 개발작업 시작 시, git issue 활용해보기

### ❓멘토님께 질문할 내용
세팅과정을 모두 정확히 이해하고 각 프로그램이 어떤 목적의 어떤 기능을 하는지, 그리고 의존성 등 다 공부하고 이해하는게 좋을까요?

이후에 Spring boot를 사용하게 되면 이 세팅과정은 다 자동화되는 것으로 알고있는데, Spring MVC 를 포함한 모든 세팅과정은 어느정도로 알고있어야 하나요? 