# Discommu
디스코드와 웹을 연동한 게시판(개발중)

## 링크
+ [봇](https://discord.com/api/oauth2/authorize?client_id=761495487215042570&permissions=0&scope=bot)
+ [웹](https://discommu.ga)
+ [API](https://api.discommu.ga/graphql)

## 메인 아이디어
봇에서 게시판을 사용할 수 있고 웹에서도 게시판을 사용할 수 있다
그리고 봇과 웹에서 같은 데이터베이스를 공유해 같은 데이터를 볼수 있다
디스코드와 연동해서 굳이 계정을 만들지 않아도 되고 디스코드를 사용하는 많은 사람한테 말하고 싶을때 쓰면 된다

## 참가자
@kiki7000 (메인 개발자, 제작자), @pikokr (서브 개발자)

## 개발 스택
### 동일
+ 데이터베이스: MongoDB (Atlas 사용)

### 백엔드
+ 언어: Node.js
+ 라이브러리: express + apollo-server + type-graphql
+ 형식: GraphQL

### 프런트엔드
+ 언어: React.js
+ 라이브러리: TailwindCSS

### 봇
+ 언어: Python
+ 라이브러리: discord.py