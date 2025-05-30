# 🌱 FastCampus Spring Boot Practice

이 저장소는 FastCampus의 백엔드 강의를 통해 학습한 Spring Boot 실습 코드들을 모아놓은 프로젝트입니다. 각 폴더는 강의별 주제에 따라 나뉘어 있으며, 핵심 개념과 기능 구현을 포함하고 있습니다.

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

## ✅ 사용 기술
- Java 11+
- Spring Boot
- Spring Data JPA
- Gradle
- H2 / MySQL
- Docker

## 💡 실행 방법

```bash
cd 01-hello-springboot/hello-springboot
./gradlew bootRun
