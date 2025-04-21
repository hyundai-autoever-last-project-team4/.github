# 🚛 Wherehouse - 차량 부품 창고 관리 시스템

![Wherehouse Banner](https://github.com/user-attachments/assets/b2790798-7692-4411-ad38-1b622994a253)

> 현대오토에버 모빌리티 SW스쿨 웹/앱 과정 최종 프로젝트

## 🔗 서비스 링크
📦 [Wherehouse Client](https://wherehouse.site/client)  
🧑‍💼 [Wherehouse Admin](https://wherehouse.site/admin)  
👷 [Wherehouse Web-View](https://wherehouse.site/web-view)  

---

## 📂 프로젝트 저장소
[![GitLab](https://img.shields.io/badge/GitLab-Project-red?style=flat&logo=gitlab)](https://gitlab.com/hyundai-autoever-last-project-team4)

## 📑 프로젝트 문서
📄 [프로젝트 PPT](https://drive.google.com/file/d/1lb1KvBnpnbqFqeLTHPQbQK23OlGyQOD1/view?usp=sharing)  
🎥 [시연 영상](https://www.youtube.com/watch?v=vIVot70bqFA)  

---

# 📌 프로젝트 소개
> **차량 부품의 입고부터 출고까지 전체 프로세스를 관리하고 운영할 수 있는 시스템**

- 대규모 창고 시스템을 **효율적으로 관리**하고 **실시간 모니터링**
- 사용자 역할별 **입고/출고/적치 프로세스 지원**
- 창고 현황을 **실시간 알림**을 통해 파악 가능

---

# 🏗️ 협업 및 개발 전략
## 🛠️ **백엔드 협업 전략**
- **MSA 프로젝트 설정** → [MSA 프로젝트 설정법](https://www.notion.so/MSA-d62bb21b80294723a0c555e50787c4c8?pvs=21)
- **코드 컨벤션 수립** → [Git commit 메시지 규칙](https://www.notion.so/git-commit-messages-40cb686d74d344cbb82c22d62fc8c657?pvs=21)
- **보안 전략** → [Spring Security 가이드](https://www.notion.so/Spring-Security-f234c925403e407580acfd685191133c?pvs=21)
- **API 문서화** → [Swagger 설정](https://www.notion.so/Swagger-PreAuthorize-1b7f2528fe7880019b40cfd2477b1b97?pvs=21)

## 🚀 **배포 및 CI/CD**
- **CI/CD 파이프라인 구축** → [GitLab CI/CD](https://www.notion.so/Gitlab-CI-CD-31160c7a4448483f92cabc8d68892d67?pvs=21)
- **AWS EKS 기반 쿠버네티스 배포** → [K8s Migration](https://www.notion.so/k8s-migration-19ef2528fe78808c81d5e4f4304868f7?pvs=21)
- **Rolling Update 전략 적용 (무중단 배포)**

## 🏗️ **기능 개발**
- 내부 **Queue + Thread 기반 사용자 히스토리 서비스 개선** ([링크](https://www.notion.so/199f2528fe7880e6bfd4dee5c8fecabd?pvs=21))
- **부하 테스트 및 분석** → [Jmeter 활용](https://www.notion.so/b25870567a2c4af5be1d1e8a731a8760?pvs=21)
- **API Gateway 구축** → [Spring Cloud + Reactor](https://www.notion.so/api-gateway-631f0cab1c4448e690701de210258cb6?pvs=21)
- **창고 실시간 알림 시스템** → [SSE 구현](https://www.notion.so/SSE-19ff2528fe78801181cbf6379e0293b3?pvs=21)
- **임시 사용자 생성 (Redis 활용)** → [자세히 보기](https://www.notion.so/19df2528fe7880adb5ebf6fd82eafebb?pvs=21)
- **입고 검증 알고리즘 적용** → [입고 요청 처리](https://www.notion.so/198f2528fe78807c8354d4201283219b?pvs=21)

---

# 🛠️ 트러블 슈팅
- 🔄 **Nginx Redirect 에러 해결** → [문제 해결](https://www.notion.so/NGINX-POST-GET-fb5c0d4c5164476db9155c9bfd78736a?pvs=21)
- 🔄 **Spring Security & WebFlux 충돌 해결** → [문제 해결](https://www.notion.so/Spring-Security-Context-at-web-flux-19bf2528fe7880c490a5f1f26ece5263?pvs=21)
- 🔄 **Docker Container 간 네트워크 문제 해결** → [문제 해결](https://www.notion.so/DOCKER-Docker-Container-7095b2e96d9b4a89bcb8c3653dfe8dec?pvs=21)

---

# ⚙️ 사용 기술 스택
| Backend | Infrastructure | Security | Database |
|---------|--------------|----------|-----------|
| Spring Framework `3.4.2` | AWS EKS | Spring Security | MySQL |
| Spring Cloud `2024.0.0` | GitLab CI/CD | OpenFeign | MongoDB Reactive |
| Spring Doc [MVC] `2.8.1` | Docker | Keycloak Oauth2 | Redis |
| Spring Doc [WebFlux] `2.2.0` | Kubernetes | JWT (jsonwebtoken:jjwt `0.11.5`) | |

---

# 🏢 협업 공간
📌 **노션** → [프로젝트 문서](https://www.notion.so/183f2528fe7880d7bc6ad2647331a94a?pvs=21)  
📌 **지라** → (Private, 스크린샷 참고)

![alt text](image.png)

---

# 🎯 프로젝트 목표
✅ **창고 관리의 자동화 및 최적화**

✅ **실시간 데이터 처리 및 모니터링**

✅ **확장성 높은 MSA 아키텍처 구축**

✅ **안정적인 CI/CD 파이프라인 적용**

---

🚀 **Wherehouse**, 효율적인 창고 관리의 새로운 기준을 만듭니다!


