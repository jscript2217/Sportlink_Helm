# 공식 OpenJDK 17 베이스 이미지 사용
FROM openjdk:17-jdk-slim

# 컨테이너 안 Workdir 설정
WORKDIR /app

# 컨테이너에 복사할 jar 파일 설정
COPY sportsLink-0.1.1-SNAPSHOT.jar /app/sportsLink-0.1.1-SNAPSHOT.jar

# 기본 8080 포트
EXPOSE 8080

# jar 파일 실행
CMD ["java", "-jar", "/app/sportsLink-0.1.1-SNAPSHOT.jar"]