# Day 1 - AWS EC2 서버 생성 실습

## 오늘 목표
- AWS EC2 인스턴스 생성
- SSH로 서버 접속
- Nginx 웹서버 설치 및 실행

## 상태
- 실습 예정

- 실습 완료

AWS EC2 인스턴스 생성

SSH 접속

Nginx 웹서버 설치

웹서버 접속 테스트

수행한 작업
1.AWS Academy 계정으로 로그인

2.EC2 인스턴스 생성 (Amazon Linux 2023, t2.micro)

3.SSH(22번), HTTP(80번), HTTPS(443번) 포트 오픈

4.SSH로 EC2 서버 접속 (vockey.pem 사용)

5.서버 패키지 업데이트 (sudo yum update -y)

6.Nginx 설치 및 실행

sudo yum install nginx -y

sudo systemctl start nginx

7.퍼블릭 IP로 접속 → Nginx 기본 페이지 확인 완료

