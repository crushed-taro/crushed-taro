<h1>안녕하세요, 백엔드 개발자 신성균입니다.</h1>

Java · Spring 기반 백엔드 개발자입니다. C++·C# 장비 제어 개발 6년을 거쳐 웹 백엔드로 전향했고,  
OCR 웹 시스템 개발·운영과 학회·협회 웹 서비스 유지보수·구축, 서버 운영을 맡아 왔습니다.  
기능을 만드는 데서 끝내지 않고, 원인은 로그와 데이터로 추적하고 배포는 되돌릴 수 있게 준비하는 개발을 지향합니다.

## About Me
- Java · Spring 기반 웹 서비스 개발과 운영 (Spring Boot, Spring MVC, MyBatis, JPA)
- 결제 연동과 장애 대응: 결제 장애 원인 규명·당일 복구, 결제 중복 저장 방지
- 서버 운영과 보안: Linux · Tomcat · Nginx 운영, SSL 인증서 관리, 서버 침해 대응
- Docker · Docker Compose · AWS EC2 기반 배포 경험
- RabbitMQ · SSE · WebSocket 기반 실시간 처리 경험

## Experience
- **2026.08 ~ 현재** · 학회·협회 웹 서비스 유지보수와 신규 구축, 서버 운영, 국가 R&D 과제(감염질환 가이드라인 AI) 개발
- **2025.04 ~ 2026.03** · Spring Boot 기반 OCR 웹 시스템 개발과 운영
- **2015.09 ~ 2021.07** · C++ · C# 기반 생산설비·테스트 장비 제어 프로그램 개발

## Main Projects

### [DeepLine](https://github.com/crushed-taro/deepline)
사용자 관리, 근태, 전자결재 기능을 통합한 웹 기반 ERP 시스템 (개인 프로젝트)
- 기획, 설계, 개발, 배포 전 과정을 단독 수행
- Spring Security + JWT 인증/인가, RabbitMQ + SSE 실시간 알림, STOMP WebSocket 1:1 채팅
- 결재 상세 조회 N+1 문제 해결로 SELECT 6회 → 1회, Redis 캐시로 평균 응답 80ms → 15ms
- Docker Compose · Nginx로 Linux 서버에 배포

### [Django Portfolio](https://github.com/crushed-taro/django-portfolio)
Docker Compose로 AWS EC2에 배포해 운영한 포트폴리오 사이트 (개인 프로젝트)
- Django(Gunicorn) · Nginx · Certbot 컨테이너 분리 구성
- Nginx Reverse Proxy, HTTPS 인증서 발급과 자동 갱신
- 운영 중 자동 스캔 요청을 접속 로그로 확인하고 Nginx에서 차단

### [TravelAnchor](https://github.com/Final-Project-TravelAnchor/TravelAnchor)
여행 메이트 모집 및 실시간 채팅 서비스 (팀 프로젝트 · 6명)
- PM으로 일정 관리와 기능 우선순위 조정
- 모집 공고 CRUD, WebSocket 기반 실시간 채팅, 외부 API 연동

## Tech Stack
- **Backend**: Java, Spring Boot, Spring MVC, Spring Security, JPA, MyBatis
- **Database**: MySQL · MariaDB, PostgreSQL, Redis
- **Infra / DevOps**: Linux, Tomcat, Nginx, Docker, Docker Compose, AWS EC2
- **Realtime / Messaging**: RabbitMQ, SSE, WebSocket
- **Frontend**: React, TypeScript, JSP
- **Tools**: Git, GitHub, IntelliJ, Vim

## Links
- **Blog**: https://crushed-taro.tistory.com

## Problem Solving
[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=97crushed_taro)](https://solved.ac/profile/97crushed_taro)
