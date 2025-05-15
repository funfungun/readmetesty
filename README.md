뻔뻔
gimgeon8249
온라인

주강사_김신록 — 2025. 1. 20. 오후 6:44
비동기 처리 + Promise와 Javascript 모듈 시스템 강의 내용, 예제 코드 올려드립니다.
첨부 파일 형식: archive
3.async.zip
9.46 KB
첨부 파일 형식: archive
4.module.zip
8.32 MB
주강사_김신록 — 2025. 1. 21. 오후 3:20
스프린트 미션 1  내용이 나와 있는 문서 공유드립니다.
## 1

- class 키워드를 이용해서 Product 클래스와 ElectronicProduct 클래스를 만들어 주세요.
  - Product 클래스는 name(상품명) description(상품 설명), price(판매 가격), tags(해시태그 배열), images(이미지 배열), favoriteCount(찜하기 수)프로퍼티를 가집니다.
  - Product 클래스는 favorite 메소드를 가집니다. favorite 메소드가 호출될 경우 찜하기 수가 1 증가합니다.
  - ElectronicProduct 클래스는 Product를 상속하며, 추가로 manufacturer(제조사) 프로퍼티를 가집니다.
확장
sprint-mission-1.md
4KB
주강사_김신록 — 2025. 1. 21. 오후 3:35
fetch, axios 강의 교안 및 코드입니다.
첨부 파일 형식: archive
5.fetch-axios.zip
753.24 KB
주강사_김신록 — 2025. 1. 21. 오후 3:42
스프린트 미션 1  내용이 나와 있는 문서(1차 수정본) 공유드립니다.
## 1

- class 키워드를 이용해서 Product 클래스와 ElectronicProduct 클래스를 만들어 주세요.
  - Product 클래스는 name(상품명) description(상품 설명), price(판매 가격), tags(해시태그 배열), images(이미지 배열), favoriteCount(찜하기 수)프로퍼티를 가집니다.
  - Product 클래스는 favorite 메소드를 가집니다. favorite 메소드가 호출될 경우 찜하기 수가 1 증가합니다.
  - ElectronicProduct 클래스는 Product를 상속하며, 추가로 manufacturer(제조사) 프로퍼티를 가집니다.
확장
sprint-mission-1.md
4KB
주강사_김신록 — 2025. 1. 31. 오전 8:51
유닉스 커맨드 강의 교안입니다.,
첨부 파일 형식: archive
6.unix-command.zip
2.59 KB
주강사_김신록 — 2025. 1. 31. 오전 10:17
스프린트 미션 1 코드입니다.
첨부 파일 형식: archive
sprint-mission-1.zip
9.74 KB
주강사_김신록 — 2025. 2. 3. 오전 9:53
Git을 활용한 버전 관리 교안입니다.,
첨부 파일 형식: archive
7.git.zip
3.77 KB
주강사_김신록 — 2025. 2. 4. 오전 8:52
Git 협업하기(Github) 교안입니다.,
첨부 파일 형식: archive
8.github.zip
2.73 KB
주강사_김신록 — 2025. 2. 7. 오전 9:44
Git 보강 내용입니다.
## 보충 수업

- git pull과 git fetch

  - fetch: 원격 저장소의 최신 변경 사항을 가져옴
  - pull: 원격 저장소에서 최신 변경 사항을 가져온 후, 자동으로 내 로컬 브랜치와 병합
확장
topic-plus.md
4KB
오늘 이론 평가 전 같이 살펴볼 기술블로그 링크도 공유드립니다.
https://techblog.woowahan.com/2553/
주강사_김신록 — 2025. 2. 10. 오전 9:50
Express 웹 서버 구축 첫번째 교안입니다.
# Express 웹 서버 구축

## 학습 개요

- Node.js 소개
- Express 소개
확장
1-express-init.md
4KB
주강사_김신록 — 2025. 2. 10. 오후 5:41
app.js, mock.js, request.http 파일 압축한 것입니다.
첨부 파일 형식: archive
express.zip
2.79 KB
주강사_김신록 — 2025. 2. 11. 오전 8:53
오늘 학습할 몽고DB와 배포 교안입니다.
### 5. 데이터베이스와 ORM

- 데이터베이스
  - 데이터를 저장해 두는 곳
  - 데이터베이스와 소통하려면 **쿼리 언어 사용 (나중에 배울 내용 — 과정 후반부 쯤에)**
  - SQL, NoSQL 등이 있음
확장
2-mongodb.md
6KB
주강사_김신록 — 2025. 2. 11. 오전 10:40
mongoDB 실습에 활용할 시드 데이터입니다.
const data = [
  {
    title: "파이썬 공부",
    description: "프로그래밍 시작하기 in Python 토픽 끝내기",
    isComplete: false,
    createdAt: "2023-03-23T06:34:11.617Z",
확장
seedData.js
1KB
주강사_김신록 — 2025. 2. 13. 오전 8:52
오늘 2교시부터 진행할 관계형 데이터베이스 교안입니다.
# ORM을 활용한 관계형 데이터베이스와 서버 연동

## 학습 개요

- 관계형 데이터베이스
- DBMS
확장
2-postgres-prisma.md
11KB
주강사_김신록 — 2025. 2. 13. 오후 2:54
실습 진행한 도서 대여 시스템 ERD 입니다.
# ERD task

## 도서 대여 시스템

- 비즈니스 명세
확장
erd-task.md
2KB
주강사_김신록 — 2025. 2. 13. 오후 3:24
prisma 실습입니다.
{
  "dependencies": {
    "@prisma/client": "^5.4.2",
    "dotenv": "^16.3.1",
    "express": "^4.18.2",
    "is-email": "^1.0.2",
확장
package.json
1KB
주강사_김신록 — 2025. 2. 14. 오전 11:02
prisma seed 파일입니다.
export const USERS = [
  {
    id: "b8f11e76-0a9e-4b3f-bccf-8d9b4fbf331e",
    email: "honggd@example.com",
    firstName: "길동",
    lastName: "홍",
확장
mock.js
30KB
import { PrismaClient } from "@prisma/client";
import { USERS } from "./mock.js";

const prisma = new PrismaClient();

async function main() {
확장
seed.js
1KB
주강사_김신록 — 2025. 2. 17. 오전 9:57
오늘 함께 구현할 데이텀 모델의 ERD 입니다.
# User, Product, Order

```mermaid
  erDiagram
    USER {
        STRING id PK
확장
erd-order.md
2KB
주강사_김신록 — 2025. 2. 17. 오후 2:25
새로운 mock, seed
export const USERS = [
  {
    id: 'b8f11e76-0a9e-4b3f-bccf-8d9b4fbf331e',
    email: 'honggd@example.com',
    firstName: '길동',
    lastName: '홍',
확장
mock.js
42KB
import { PrismaClient } from '@prisma/client';
import {
  USERS,
  USER_PREFERENCES,
  PRODUCTS,
  ORDERS,
확장
seed.js
2KB
주강사_김신록 — 2025. 2. 17. 오후 5:45
order.http

###
GET http://localhost:3000/orders/a03b7801-d6d9-456d-ba3e-0e73750bc6b2

###
POST http://localhost:3000/orders
확장
order.http
1KB
주강사_김신록 — 2025. 2. 17. 오후 6:55
현재 저의 스키마 파일입니다.
첨부 파일 형식: unknown
schema.prisma
2.34 KB
주강사_김신록 — 2025. 2. 18. 오전 9:37
현재까지의 프로젝트 파일입니다. @NB_1기_김승희
첨부 파일 형식: archive
comazon-practice.zip
47.52 KB
주강사_김신록 — 2025. 2. 18. 오후 12:50
prisma 마무리 이후 진행할 Express 핵심 기능 교안과 시작 파일들입니다.
첨부 파일 형식: archive
express-core-features.zip
14.60 KB
주강사_김신록 — 2025. 2. 18. 오후 5:13
const products = [
  {
    id: 1,
    name: "MacBook Pro",
    price: 2500000,
    reviews: [
      { id: 1, user: "민준", rating: 5 },
      { id: 2, user: "서연", rating: 4 },
    ],
  },
  {
    id: 2,
    name: "Logitech MX Keys",
    price: 120000,
    reviews: [
      { id: 3, user: "지후", rating: 5 },
      { id: 4, user: "하윤", rating: 3 },
    ],
  },
];
주강사_김신록 — 2025. 2. 19. 오전 11:20
router를 활용하여 comazon을 리팩토링한 것입니다.
첨부 파일 형식: archive
comazon-router.zip
50.62 KB
주강사_김신록 — 2025. 2. 19. 오후 12:57
multer 실습시 사용할 요청입니다.

POST http://localhost:3000/files
Content-Type: multipart/form-data; boundary=Boundary01234567890123456789

--Boundary01234567890123456789
Content-Disposition: form-data; name="attachment"; filename="hello.txt"
Content-Type: text/plain

Hello!
--Boundary01234567890123456789--
주강사_김신록 — 2025. 2. 28. 오전 11:35
https://www.digitalocean.com/community/tutorials/node-js-architecture-single-threaded-event-loop
오늘 한시에는 이 아티클을 보면서 Node.js 아키텍쳐에 대해 이해해보는 시간을 가지려 합니다.
이를 이해하고 초급 프로젝트를 진행하시면 더욱 의미가 있을 것으로 생각합니다.
Node JS Architecture - Single Threaded Event Loop | DigitalOcean
Technical tutorials, Q&A, events — This is an inclusive place where developers can find or lend support and discover new ways to contribute to the community.
이미지
주강사_김신록 — 2025. 3. 13. 오후 1:17
https://product.kyobobook.co.kr/detail/S000001033125

전반적인 IT 리터러시 향상을 위해서 이 책 한번씩 보셔도 좋을거 같습니다.
주강사_김신록 — 2025. 3. 18. 오전 9:43
오늘 학습할 유저 기능과 인증 시스템의 이해 교안입니다. 권한 문제가 있어 다시 올렸습니다.
https://codeit.notion.site/1ba6fd228e8d800b970cd1869e701f50 
Codeit on Notion
유저 기능과 인증 시스템의 이해 | Notion
학습 개요
유저 기능과 인증 시스템의 이해 | Notion
주강사_김신록 — 2025. 3. 18. 오후 12:50
Express 유저 기능 구현 교안입니다.
https://codeit.notion.site/Express-1ba6fd228e8d80869c79dd35da877b1c
Codeit on Notion
Express 유저 기능 구현 | Notion
학습 개요
Express 유저 기능 구현 | Notion
주강사_김신록 — 2025. 3. 18. 오후 3:37
수업 시간에 잠깐 설명드렸던 번역 확장 프로그램 관련 소개 영상입니다.
필요하신 분들 보시고 설치하셔도 좋을거 같습니다.
https://www.youtube.com/watch?v=aoRIwvC85Vg
YouTube
월텍남 - 월스트리트 테크남
"이거"깔고 영어만 나오면 환장하면서 누릅니다 ㅋㅋㅋ...안하면 손해
이미지
주강사_김신록 — 2025. 3. 20. 오후 3:17
수업시간에 함께 진행한 유저 기능 개발 최종 코드입니다.
.env와 node_modules 폴더는 제외했습니다.
첨부 파일 형식: archive
express-user-system-final.zip
41.50 KB
주강사_김신록 — 2025. 3. 25. 오후 1:03
타입스크립트 기본기 교안입니다.
https://codeit.notion.site/Typescript-1c06fd228e8d80bbb9b9e1d6b0937eaa
Codeit on Notion
Typescript 기본기 | Notion
학습 개요
Typescript 기본기 | Notion
주강사_김신록 — 2025. 3. 26. 오후 4:52
https://codeit.notion.site/Typescript-1c06fd228e8d803e9644cce0e088dc03

타입스트립트 적용 및 유효성 검사 교안입니다.
Codeit on Notion
Typescript 적용 및 유효성 검사 | Notion
학습 개요
Typescript 적용 및 유효성 검사 | Notion
주강사_김신록 — 2025. 3. 27. 오후 3:56
https://codeit.notion.site/Restful-API-1c26fd228e8d80eab8dbeb32354cf313?pvs=4

Restful API 설계화 및 문서화 교안입니다.
Codeit on Notion
Restful API 설계화 및 문서화 | Notion
학습 개요
Restful API 설계화 및 문서화 | Notion
typescript express 적용 코드입니다.
첨부 파일 형식: archive
typescript-express-guide.zip
30.17 KB
주강사_김신록 — 2025. 3. 28. 오전 8:56
코드레벨 아키텍쳐 및 디자인 패턴 교안입니다.
https://codeit.notion.site/1c36fd228e8d808ab672c431549d6346
Codeit on Notion
코드레벨 아키텍쳐 및 디자인 패턴 | Notion
학습 개요
코드레벨 아키텍쳐 및 디자인 패턴 | Notion
주강사_김신록 — 2025. 4. 4. 오전 8:49
SQL로 하는 데이터 분석 교안입니다.
https://codeit.notion.site/SQL-1ca6fd228e8d800a8e36c13e15931a2c
Codeit on Notion
SQL로 하는 데이터 분석 | Notion
수업 자료
SQL로 하는 데이터 분석 | Notion
주강사_김신록 — 2025. 4. 10. 오후 5:58
https://codeit.notion.site/SQL-1ca6fd228e8d8008a4bfe055fda11d24
Codeit on Notion
SQL로 하는 데이터 관리 | Notion
학습 개요
SQL로 하는 데이터 관리 | Notion
주강사_김신록 — 2025. 4. 14. 오전 9:57
데이터베이스 모델링 교안입니다.
https://codeit.notion.site/1d46fd228e8d8070b8a7f43921b925c8?pvs=4
Codeit on Notion
데이터베이스 모델링 | Notion
학습 개요
데이터베이스 모델링 | Notion
주강사_김신록 — 2025. 4. 25. 오후 2:31
깃헙에서 PR을 요청할 때는 잘못된 수정은 없는지 체크하는 습관을 들이는게 좋습니다!
주강사_김신록 — 2025. 5. 13. 오후 4:51
웹소켓에 대한 이해 교안입니다.
https://codeit.notion.site/1f16fd228e8d8029abc2e7cc77d7c0f0?pvs=4
codeit on Notion
웹소켓에 대한 이해 | Notion
학습 개요
웹소켓에 대한 이해 | Notion
주강사_김신록 — 어제 오전 8:47
웹소켓을 활용한 실시간 데이터 통신 구현 교안입니다.

https://codeit.notion.site/1f26fd228e8d804f92c0c9aa81235091?pvs=4
codeit on Notion
웹소켓을 활용한 실시간 데이터 통신 구현 | Notion
학습 개요
웹소켓을 활용한 실시간 데이터 통신 구현 | Notion
주강사_김신록 — 어제 오전 9:24
첨부 파일 형식: archive
ws-echo-example.zip
21.08 KB
주강사_김신록 — 어제 오전 10:35
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>채팅 테스트</title>
확장
index.html
1KB
const messageList = document.getElementById('message-list');
const messageForm = document.getElementById('message-form');
const userInput = document.getElementById('user-input');
const messageInput = document.getElementById('message-input');
const systemMessage = document.getElementById('system-message');
const joinButton = document.getElementById('join-button');
확장
script.js
4KB
.chat-container {
  margin: 0 auto;
  max-width: 480px;
  width: 100%;
}
확장
style.css
1KB
주강사_김신록 — 어제 오후 2:08
첨부 파일 형식: archive
socketio-chat-example.zip
24.23 KB
주강사_김신록 — 어제 오후 4:44
스프린트 미션 8 진행하며서 활용할 index.html 코드입니다. 
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
확장
socket-client-test.html
2KB
주강사_김신록 — 오후 3:23
# Panda Market API

## 환경 변수 설정

`.env.example` 파일을 참고해서 필요한 환경 변수를 설정해 주세요.
확장
README.md
6KB
﻿
# Panda Market API

## 환경 변수 설정

`.env.example` 파일을 참고해서 필요한 환경 변수를 설정해 주세요.

## 설치

의존성 패키지를 설치합니다.

```
npm install
```

Prisma와 데이터베이스를 준비합니다.

```
npx prisma generate
npx prisma migrate dev
```

## 실행

`npm dev`로 개발 모드로 실행할 수 있습니다.

## 코드 구현 설명

### 엔드포인트 목록

- articlesRouter
  - `POST /articles`: 게시글 생성
  - `GET /articles`: 게시글 목록 조회
  - `GET /articles/:id`: 게시글 상세 조회
  - `PATCH /articles/:id`: 게시글 수정
  - `DELETE /articles/:id`: 게시글 삭제
  - `POST /articles/:id/comments`: 게시글에 댓글 작성
  - `GET /articles/:id/comments`: 게시글의 댓글 목록 조회
  - `POST /articles/:id/likes`: 게시글 좋아요
  - `DELETE /articles/:id/likes`: 게시글 좋아요 취소
- productsRouter
  - `POST /products`: 상품 등록
  - `GET /products`: 상품 목록 조회
  - `GET /products/:id`: 상품 상세 조회
  - `PATCH /products/:id`: 상품 수정
  - `DELETE /products/:id`: 상품 삭제
  - `POST /products/:id/comments`: 상품에 댓글 작성
  - `GET /products/:id/comments`: 상품의 댓글 목록 조회
  - `POST /products/:id/favorites`: 상품 좋아요
  - `DELETE /products/:id/favorites`: 상품 좋아요 취소
- commentsRouter
  - `PATCH /comments/:id`: 댓글 수정
  - `DELETE /comments/:id`: 댓글 삭제
- notificationsRouter
  - `PATCH /notifications/:id/read`: 알림 읽음 처리
- usersRouter
  - `GET /users/me`: 내 정보 조회
  - `PATCH /users/me`: 내 정보 수정
  - `PATCH /users/me/password`: 내 비밀번호 변경
  - `GET /users/me/products`: 내가 등록한 상품 목록 조회
  - `GET /users/me/favorites`: 내가 좋아요한 상품 목록 조회
  - `GET /users/me/notifications`: 내 알림 목록 조회
- authRouter
  - `POST /auth/register`: 회원가입
  - `POST /auth/login`: 로그인
  - `POST /auth/logout`: 로그아웃
  - `POST /auth/refresh`: 토큰 재발급
- imagesRouter
  - `POST /images/upload`: 이미지 업로드

### Notification 모델

```ts
interface Notification {
  id: number;
  userId: number;
  read: boolean;
  type: 'NEW_COMMENT' | 'PRICE_CHANGED';
  payload: object;
  createdAt: Date;
  updatedAt: Date;
}
```

- 이벤트 타입과 페이로드를 포함하고 있습니다.
- 페이로드는 `articleId`나 `productId`와 `price` 같은 해당 이벤트를 클라이언트가 처리하는데 필요한 데이터를 담고 있습니다.

### NotificationsService

- Notification을 생성, 수정하는 책임을 갖습니다.
- Notification을 생성하면 SocketService에 해당 Notification을 전달합니다.

### SocketService

- Socket.IO 연결을 관리합니다.
- 미들웨어에서 액세스 토큰을 확인하고 인증을 처리합니다.
  - 인증에 성공하면 해당 소켓을 `userId`를 기준으로 room에 join시킵니다.
  - 하나의 사용자가 여러 브라우저 탭 등에서 접속 가능하기 때문에, `userId` room에는 여러 소켓이 join할 수 있습니다.
- `sendNotification()` 함수에서는 `userId`를 가지고 해당하는 room에 메시지를 보냅니다.

### 전체적인 동작 순서

알림이 발생하면(예: 댓글, 가격 변경 등)

→ 해당 서비스가 NotificationsService에 Notification 생성 요청

→ NotificationsService가 DB에 알림 저장

→ 저장된 알림을 SocketService로 전달

→ SocketService가 해당 사용자에게 실시간으로 알림 전송

## Notification 테스트

`/public/socket-client-test.html` 파일에 Socket.IO 클라이언트를 테스트할 수 있는 프론트엔드 코드가 구현되어 있습니다.
`http://localhost:3000/public/socket-client-test.html`로 접속할 수 있습니다.

### socket-client-test.html

- JWT 토큰을 인풋에 입력하고 버튼을 누르면, Socket.IO 클라이언트로 `http://localhost:3000` 으로 접속합니다.
- `notification`라는 이벤트를 메시지로 받으면 콘솔에 받은 메시지를 출력합니다.

### 테스트 시나리오

- 준비하기
  - User 1 회원가입
  - User 1으로 로그인
  - socket-client-test.html에서 User 1으로 접속
  - (테스트를 위해 액세스 토큰은 기록해 둡니다.)
  - User 2 회원가입
  - User 2로 로그인
  - socket-client-test.html에서 User 2로 접속
  - (테스트를 위해 액세스 토큰은 기록해 둡니다.)
- 게시물 댓글 알림 테스트
  - User 1이 게시물 등록
  - User 2가 게시물 댓글 등록
  - User 1의 소켓 클라이언트에서 메시지가 잘 오는지 확인
  - User 2의 소켓 클라이언트에서는 오는 메시지가 없도록 확인
- 상품 가격 알림 테스트
  - User 1이 상품 등록
  - User 2가 상품 좋아요
  - User 1이 상품 가격 수정
  - User 2의 소켓 클라이언트에서 메시지가 잘 오는지 확인
  - User 1의 소켓 클라이언트에서는 오는 메시지가 없도록 확인
README.md
6KB
