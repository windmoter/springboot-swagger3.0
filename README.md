# maven 설치
https://velog.io/@dingdoooo/Java-VScode-Java-%EC%97%B0%EA%B2%B0%ED%95%98%EA%B8%B0
다운로드 : https://maven.apache.org/download.cgi
    - apache-maven-3.8.8-bin.zip (sha512, asc)
시스템 변수 - 편집 클릭

변수 이름 : mvn, 변수 값 : maven path

# Swagger Introduction & Examples
 SwaggerSpringDemoApplication.java 실행


# UI
http://localhost:8081/swagger-ui/index.html

# Maven
mvn install -f "d:\app\springboot-swagger3.0\springboot-swagger3.0\pom.xml"
compile -> 컴파일 수행

test -> 컴파일 수행 후 테스트 클래스 수행

package -> 컴파일을 수행하고 컴파일한 소스를 packaging 양식에 맞춰 프로젝트 내 지정한 경로 디렉토리에 생성

install -> package 한 것에 추가적으로 로컬 repository에 배포

deploy -> install 한 것에 추가적으로 원격 repository에 배포

clean -> maven build 시 생성된 모든 것들을 삭제

site -> target, site에 문서사이트 생성 
