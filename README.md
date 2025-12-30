# SPRING PLUS
## 📌 프로젝트 소개
Spring Plus 개념을 학습하여 기존 과제에 JPA 최적화 (N+1, JPQL), Spring Security, QueryDSL등을 적용한 실습 프로젝트입니다.
<br/>
<br/>

## 🛠 기술 스택

### Backend
- **Language**: Java 17
- **Framework**: Spring Boot 3.5
- **ORM**: Spring Data JPA (Hibernate)
- **Database**: MySQL
- **Security / Auth**: Spring Security, JWT
- **Build Tool**: Gradle
- **IDE**: IntelliJ IDEA
- **API Test**: Postman

<br>

## ⚙️ 구현 기능 및 리팩터링
### JWT 인증/인가 적용
- Spring Security + JWT 기반 인증으로 기존 Filter/Argument Resolver 구조 개선, 권한 관리 유지
  
### JPA 최적화 & N+1 문제 해결
- fetch join, QueryDSL 활용으로 연관 엔티티 조회 최적화, 검색 성능 개선

### 동적 검색 구현 (JPQL/QueryDSL)
- 조건별 할 일 검색 기능 구현 (weather, 기간)

### AOP 로깅
- 로그 실행 시점을 @Before로 변경, 포인트컷 범위 단순화

### 테스트 코드 안정화
- 실패하던 테스트 수정 및 예외처리 보완으로 API 검증 안정화
<br/>

## 🤓 트러블슈팅 기록
[트러블슈팅 보러가기](https://remnantcjy.tistory.com/entry/%F0%9F%A4%93-Spring-%ED%94%8C%EB%9F%AC%EC%8A%A4-%EC%A3%BC%EC%B0%A8-%EA%B0%9C%EC%9D%B8-%EA%B3%BC%EC%A0%9C-%ED%8A%B8%EB%9F%AC%EB%B8%94%EC%8A%88%ED%8C%85-%F0%9F%92%A5)

