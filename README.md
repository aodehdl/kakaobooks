# kakaobooks
카카오 검색 API 를 이용해 책 검색 서비스 개발 / 로그인기반 / 책검색/ 북마크 / 검색 히스토리 /  책 상세 페이지 / 

### 서비스 스펙
1. Java 8 버전을 사용
1. framework - spring-boot
1. server - Spring-boot 에서 제공하는 내부서버(Tomcat) 사용 
1. Database - h2 (maven dependency)
1. code style - google code style

### Back-end 추가 모듈(라이브러리)
1. httpclient - for RestAPI connected

### Front-end 추가 모듈(라이브러리)
1. jquery-3.2.1 - Front-end framework.
1. Bootstrap 4-beta - 화면 구성을 위해 CSS만 이용
1. bootpag - jQuery plugin for dynamic pagination


### 설치

```
$ git clone https://github.com/jeedy/kakaobooks.git
$ cd kakaobooks

```

### 실행(로컬)

```
$ export JAVA_HOME="`/usr/libexec/java_home -v '1.8*'`"
$ mvn clean compile
$ mvn spring-boot:run
$ curl -v localhost:8000
```


### 테스트 (Junit)

```
$ export JAVA_HOME="`/usr/libexec/java_home -v '1.8*'`"
$ mvn clean compile test
```


### 배포용 (Jar 압축)

```
$ export JAVA_HOME="`/usr/libexec/java_home -v '1.8*'`"
$ mvn clean compile
$ mvn pakage
$ cd target
```


문의: <kk59491@gmail.com>