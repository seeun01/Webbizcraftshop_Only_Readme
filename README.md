🌐 Webbizcraftshop : AWS 기반 SiteBuilder 서비스
---
### 프론트엔드 팀원 소개
|                               [김원진](https://github.com/oen0thera)                                |                                            [김세은](https://github.com/seeun01)                                            |  
|:-----------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------:|
|                                       wjsj1015@naver.com                                        |                                     ssky601@gmail.com                                      |                                      
|  <img src="https://github.com/user-attachments/assets/62480ce1-ae98-4e3b-be7a-7682c273f19c" width="150" height="150"> |  <img src="https://github.com/user-attachments/assets/5b8a526c-7a99-4041-b92d-792b220d5c2a" width="150" height="150"> |

### 📍 개요
다양한 콘텐츠로 홍보하고 싶은 기업들을 위한 고객 맞춤형 홈페이지 자동 생성 및 운영 서비스입니다. 

클라우드 기반의 혁신적인 플랫폼으로, AWS를 활용하여 손쉽게 고유한 웹사이트를 구축할 수 있습니다.

사용자는 URL을 직접 지정하고 이미지를 업로드하여 자신만의 웹사이트를 생성할 수 있습니다. 또한, 방문자 수, 방문 횟수, 스토리지 용량, 트래픽 등 주요 지표를 실시간으로 모니터링하여 비즈니스 성과를 신속하게 추적할 수 있습니다.

***※ 보안상의 이유로 코드는 공개되지 않습니다.***

20240722 ~ 비활성화

---
### 📍 주요 기능
| 기능 | 설명                                                                              |
|---|---------------------------------------------------------------------------------|
| 고유한 웹사이트 구축 | 사용자들은 총 3개의 웹사이트를 생성할 수 있으며, 각 웹사이트는 직접 지정한 고유한 URL과 업로드한 이미지를 통해 자신만의 웹사이트를 만들 수 있습니다. |
| 클라우드 기반 플랫폼 | AWS의 S3, Route 53, CloudFront, ACM을 활용하여 동적 도메인을 생성합니다.        |
| 방문자 및 방문 횟수 추적 | 각 웹사이트에 방문한 방문자 수와 방문 횟수를 실시간으로 추적할 수 있습니다.                                     |
| 스토리지 용량 모니터링 | AWS CloudWatch를 통해 각 웹사이트의 스토리지 용량을 실시간으로 모니터링하여 사용자가 데이터를 얼마나 저장하고 있는지를 파악할 수 있습니다. |
| 트래픽 제한 | Bucket4j와 Redis(Lettuce)를 활용한 AOP를 통해 각 웹사이트의 트래픽을 100MB 아래로 제한하여 서버 부하를 관리합니다. |
| 실시간 트래픽 모니터링 및 알림 | AWS CloudWatch를 통해 트래픽이 100MB를 넘으면 알림이 가도록 설정하여 실시간으로 모니터링하고 대응합니다. |
| 지속적인 통합 관리 | 사용자가 웹사이트를 생성하거나 수정할 때, 서비스 관리자의 승인을 받아 지속적인 통합 관리를 지원합니다. |

---
### 📍 활동
**시작일** <br>
*2024.05.03* <br>

**1차 출시** <br>
*2024.06.14* <br>

---
### 📍 결과물
**배포 사이트** <br>
*https://main.webbizcraft.shop* <br>

**시연 영상** <br>
[1차 출시][(https://drive.google.com/file/d/10inKFQjI8fsM7oqXdLQUS53h_G6_GTfK/view?usp=sharing)](https://github.com/user-attachments/assets/afc1390a-8a1d-4093-95f1-c6c8bc0712f7)

---

### 📍 간단 소개
![350303359-a560eb6d-cf25-41c7-b7c9-f2a68e3f0077](https://github.com/user-attachments/assets/e778db0c-dcf6-4d20-a988-9bb350ed5b6e)
![350303423-76072f34-c2c7-490c-8561-4922895039ed](https://github.com/user-attachments/assets/21b2e1bb-cd89-4180-84d7-8ee3091a53aa)
![350303447-0f77a459-8235-47fd-b9b6-3dfe0fb36213](https://github.com/user-attachments/assets/49f51f51-9e1e-4446-99b2-aeb7081ffef7)

---

### 📍 아키텍쳐 
![모바일앱협동조합 (5)](https://github.com/CloudService-mobile-app/Frontend_Only_Readme/assets/90389593/17846b57-66dc-4ad3-8f49-ea05a000750b)

---

### 📍 사용 기술스택
- Next.js

---


### commit message convention
- feat: 새로운 기능 추가
- fix: 버그 수정
- docs: 문서
- style: 포맷팅, 누락된 세미콜론 등
- refactor: 코드 리팩토링
- test: 테스트 관련
- chore: 기타 수정
- build: 빌드 시스템 또는 외부 의존성에 영향을 주는 변경
- remove: 파일을 삭제
