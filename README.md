# 🚀 Fastcampus Clone Project

Spring Boot 기반의 웹 어플리케이션 프로젝트  
> **개발기간:** 개인 프로젝트 (2025.07 ~ 2026.01)

---

## 📖 프로젝트 개요

본 프로젝트는 Fastcampus 강의를 참고하여 개발된 **Spring Boot 기반 웹 애플리케이션**입니다.  
RESTful API 설계, 계층형 아키텍처 구현, 예외처리, 보안, 데이터베이스 연동 등 백엔드 핵심 개념을 실습 및 구현하였습니다.

---

## 🗂️ 프로젝트 목록

| 번호 | 프로젝트명 | 설명 |
|------|------------|------|
| 01 | Hello Spring Boot | 가장 기본적인 스프링 부트 프로젝트 생성 및 실행 |
| 02 | REST API | RESTful API 설계 및 컨트롤러 구현 |
| 03 | Exception Handling | 글로벌 예외 처리 방법 학습 |
| 04 | Validation | 유효성 검증 로직과 @Valid 사용법 |
| 05 | MemoryDB CRUD | 메모리 기반 Repository 사용 예제 |
| 06 | Docker Setup | docker-compose로 DB 구성 및 실행 |
| 07 | JPA | 엔티티, 리포지토리, JPA 기본 개념 |
| 08 | MemoryDB to JPA | 기존 메모리 DB 코드를 JPA로 마이그레이션 |
| 09 | Simple Board | 게시판 기능 구현 (목록, 상세, 등록 등) |
| 10 | Filter & Interceptor | 요청 필터링과 인터셉터 동작 구현 |
| 11 | CRUD Example | 전체적인 CRUD 기능 종합 연습 |

## 🚀 주요 기능

- 🗄 **Spring Boot 기반 백엔드 서버 구현**
- 🗃 **RESTful API 설계 및 계층형 아키텍처 적용**
- ⚙️ **JPA를 활용한 DB 연동**
- 🔐 **Exception Handling 및 Validation 처리**
- 🔑 **보안 설정 및 인증 처리**
- 🧪 **JUnit 기반 테스트 코드 작성**

---

## 🛠️ 기술 스택

| 구분 | 사용 기술 |
| :--- | :--- |
| **Backend** | Spring Boot, Spring Web, Spring Data JPA |
| **Database** | MySQL (or H2) |
| **ORM** | JPA, Hibernate |
| **Build Tool** | Gradle (or Maven) |
| **Testing** | JUnit, Mockito |
| **IDE** | IntelliJ IDEA |
| **Version Control** | Git, GitHub |


---

## 🖥️ 시스템 아키텍처

```bash
[ Client ]
     ↓
[ Spring Boot Controller ]
     ↓
[ Service Layer ]
     ↓
[ Repository (JPA) ]
     ↓
[ Database (MySQL/H2) ]

```

## ✨ 프로젝트 회고
Spring Boot 전반적인 프로젝트 구조 설계 경험 확보

RESTful API 설계 및 HTTP 통신 흐름 이해

JPA를 통한 ORM 매핑 실습

예외처리 및 Validation 설계 능력 향상

테스트코드 작성 경험 강화
