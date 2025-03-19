# spring-boot-web

## 로컬 환경

- OS `Window 10`
- Java `v18.0.2`
- IntelliJ IDE `Ultimate 2024.3.4.1`

## 프로젝트 구조

- main
    - java - 패키지 및 소스 파일
    - resources - 리소스 및 설정 파일
- test - 테스트 코드
- build.gradle - 프로젝트 정보(Vue나 React로 따지면 package.json 느낌)

## 프로젝트 빌드

```shell
./gradlew build

# 빌드 끝난 후
cd build/libs

# .jar 파일이 생긴 것을 확인
ls 

# 실행
java -jar 파일명.jar 
```