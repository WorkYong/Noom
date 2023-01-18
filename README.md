## 개요

줌을 클론코딩한 실시간 채팅 및 화상 통화 앱입니다.

- 개발기간: 2022.12.14 - 2022.12.23 (9일)
- 개발인원: 박정용

## 사용 스택
![JavaScript Badge](https://img.shields.io/badge/Javascript-F7DF1E?style=for-the-badge&logo=Javascript&logoColor=white)&nbsp;
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=Express&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/Socket.io-4479A1?style=for-the-badge&logo=MySQL&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/WebRTC-85EA2D?style=for-the-badge&logo=Swagger&logoColor=white"/>&nbsp;


## 🏥 프로젝트 실행 방법

- 사전에 Git, node, MySQL이 설치되어있어야 합니다.

```shell
# 레포지토리 클론
$ git clone https://github.com/WorkYong/Noom

# 접속
$ cd Noom

# 패키지 설치
$ npm install

# 프로젝트 실행
$ npm run dev

# server start : http://localhost:3000
```



## 구현 기능에 대한 소개

### 1. 실시간 채팅기능
---
- 사용자가 원하는 방을 입력하여 들어갑니다.
- 방의 들어가서 이름을 입력합니다. 익명도 가능합니다.
- 채팅을 할 수 있습니다.
- 방을 나가게되면 나갔다고 알려줍니다. (예시: xxx사용자 left)


### 2. 화상기능 및 통화기능
---

- 사용자가 원하는 방의 이름을 입력하여 들어갑니다
- 마이크 및 웹캠 권한요청이 옵니다.(승인 안해주시면 사용 불가능)
- 서로 사용자끼리 화상으로 대화 할 수 있습니다.

