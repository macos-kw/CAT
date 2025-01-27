## 프로젝트명: CAT(CryptoAutoTrading)

### 목표:
1. PyQt를 사용해서 mac os에서 업비트 모바일앱 기능 중 일부를 구현
2. mac os에서 자동매매 로직을 테스트한 후, 라즈베리파이에 배포하여 실제 환경에서 운영

### 목표 달성을 위한 접근 방식
- 1번 목표
  - [업비트 API 레퍼런스](https://docs.upbit.com/reference/)를 참고하여 먼저 구현해본다.
  - 만약 시간이 오래 소요된다면 [pyupbit](https://github.com/sharebook-kr/pyupbit) 라이브러리 도입 고려
- 2번 목표
  - 라즈베리파이에서 Task Scheduling System을 먼저 구현해본다.
## 개발 과정
