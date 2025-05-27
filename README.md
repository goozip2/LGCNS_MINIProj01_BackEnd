# 💡 CSrrr: 스르르 – AI 기반 CS 면접 연습 및 커뮤니티 서비스

> **수행 기간**: 2025.05.15 ~ 2025.05.23  
> **참여 기관**: LG CNS AM Inspire Camp / WELAB SPACE  
> **주요 기술**: React, Spring Boot, MySQL, OpenAI GPT API, Spring Security, Docker

<br>

## 📌 서비스 개요
`# CS 면접 질문 자동 생성`	`# 실전 대비형 답변 훈련`	`# AI 기반 피드백 제공`
`# 정보 차단 모드`	`# 질문게시판 커뮤니티`

**CSrrr(스르르)**는 컴퓨터공학 면접(CS Interview)을 준비하는 개발자들을 위한 **AI 기반 면접 연습 플랫폼**입니다.  
사용자는 매일 새로운 질문에 답변하고, 다른 사용자와 소통하며 지식을 정리하고 확장할 수 있습니다.


### 🔗 CSrrr 배포 링크: [https://csrrr.site](https://csrrr.netlify.app/)


<br>

## 🎯 주요 기능

### ✅ CS 질문 자동 생성
- 매일 자정 새롭게 생성되는 **AI 기반 CS 질문** 제공 (OpenAI GPT API 활용)
- 사용자는 생성된 질문에 대해 답변을 작성하며 면접을 연습할 수 있음

### ✅ 답변 작성 및 저장
- 사용자는 자신의 답변을 에디터에서 작성 및 수정 가능
- **작성한 답변은 개인 피드에 저장**되어 관리 가능
- 답변 작성 전에는 해당 질문에 대한 커뮤니티 게시글, 해설 등의 정보를 제공하지 않음. **정보차단 모드를 통해 사용자의 순수한 답변 유도**

### ✅ AI 피드백
- 답변 상세 페이지에서 버튼 클릭 시, **AI 피드백 생성** 가능 (OpenAI GPT API 활용)
- 단순한 정답 여부가 아니라, **잘한 점, 보완할 점, 추가 학습 내용, 개선 포인트 등 구체적인 피드백**을 제공

### ✅ 커뮤니티 기능
- 각 질문에 대한 커뮤니티 게시판 제공
- 다양한 시각에서의 CS 접근 방식을 학습
- 댓글, 좋아요 등의 상호작용 가능

### ✅ 사용자 인증 및 권한 제어
- **Spring Security**를 이용한 회원가입/로그인
- 사용자 권한 기반 기능 제어 (예: 비로그인 사용자는 작성 불가)
- 모든 답변 기능에는 인증된 사용자 정보(UserDetails)가 반영되어 **세분화된 접근 제어** 가능

<br>

## 🛠️ 사용 기술 스택

![](https://velog.velcdn.com/images/goozip2/post/5c4d3c50-0ef7-42e8-8c7d-273ad2ba3e3b/image.png)

|분류       | 기술		                                    |
|------------|-----------------------------------------------|
| Frontend   | React, Axios, Vite, Netlify(배포)				|
| Backend    | Spring Boot, JPA             				|
| DB         | MySQL, Redis, AWS S3		                     |
| Infra      | Docker, Jenkins, Gradle, Nginx, AWS EC2, AWS RDS|
| AI 연동    | OpenAI GPT API                                |
| 인증       | JWT, Spring Security                          |
| 기타       | GitHub, Notion, Postman (API 테스트), Figma (UI 설계)|


<br>

## 📄 설계 산출물
### [Notion 요구사항 명세서 바로가기](https://www.notion.so/1f52184fcc7f81d498c2d6e6058f8112?v=1f52184fcc7f817ba478000c3ac696e6)

### [Notion API 명세서 바로가기](https://www.notion.so/API-1f52184fcc7f812db082d5c7945f1920)

### [Postman API 명세서 바로가기](https://documenter.getpostman.com/view/20776466/2sB2qaigqc)

### [ERDCloud ERD 바로가기](https://www.erdcloud.com/d/WdRQBihicGFeTwKLf)

<br>

## 📄 최종 산출물
### [GitHub upstream Repository 바로가기](https://github.com/lgcnsCampMprjTeam2)

### [CSrrr 최종보고서](https://docs.google.com/document/d/1L7VkclJI56tL3-E0kj-WHc1vq-5QVGc0B5yL_IRX9F0/edit?tab=t.0#heading=h.72kf9zvlplbj)

### [CSrrr 발표자료](https://www.canva.com/design/DAGoJMdqqZo/2uJExirbJrIxFjks3GHyPg/view?utm_content=DAGoJMdqqZo&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=hec2817124e)

<br>

## 📷 주요 화면
### 🖼️ 메인 화면
![](https://velog.velcdn.com/images/goozip2/post/0f948718-6671-4cd4-b5a7-5994706eb64b/image.png)

![](https://velog.velcdn.com/images/goozip2/post/9cee6779-45d1-4334-8d56-91108084cc09/image.png)

### 🖼️ 마이페이지 화면
![](https://velog.velcdn.com/images/goozip2/post/9836d755-183f-472e-8379-61b48c2d6919/image.png)


### 🖼️ CS 면접 연습 화면 (질문, 답변)
![](https://velog.velcdn.com/images/goozip2/post/43dea100-03a7-480b-b1d2-81d5613efb0f/image.png)

![](https://velog.velcdn.com/images/goozip2/post/35522e7a-34d9-4c99-a669-1e86caa91c5d/image.png)

![](https://velog.velcdn.com/images/goozip2/post/c9b6bf4c-9002-49f8-a61f-028de34f5247/image.png)

![](https://velog.velcdn.com/images/goozip2/post/7c99b78c-596f-4b32-b506-832d9f442a2a/image.png)

![](https://velog.velcdn.com/images/goozip2/post/7e844f9a-6abc-4761-88aa-3e49b0ec7b2e/image.png)

![](https://velog.velcdn.com/images/goozip2/post/89641bca-0ec3-4db1-9ca0-86a788865083/image.png)

![](https://velog.velcdn.com/images/goozip2/post/9d5ee18f-f66b-4395-b3da-e6e55034280b/image.png)

![](https://velog.velcdn.com/images/goozip2/post/5d77411f-36d0-4805-bbad-5df1f7f74c09/image.png)


### 🖼️ 사용자 질문 게시판 (커뮤니티)
![](https://velog.velcdn.com/images/goozip2/post/f816aadf-b71c-428d-adb2-80052ce4c85c/image.png)

![](https://velog.velcdn.com/images/goozip2/post/6991105c-3542-4555-9d59-e76cfd7d237b/image.png)

![](https://velog.velcdn.com/images/goozip2/post/fbe9d96f-53d3-4873-a511-80273f82035a/image.png)

![](https://velog.velcdn.com/images/goozip2/post/29e05dc4-db46-4de9-ad6f-7169a120fe60/image.png)

![](https://velog.velcdn.com/images/goozip2/post/5206c594-e49a-410a-af0a-78e6bd28f06d/image.png)


<br>

## 👥 팀원 구성

| 이름 | 역할 |
|------|------|
| 김수현 | BackEnd |
| 엄태범 | FrontEnd |
| 임지빈 | BackEnd |
| 정준희 | FrontEnd |
| 홍수민 | FullStack |
| 황세현 | BackEnd |


<br>

## 🚧 CSrrr 개발 중 기술적 고민과 개선 과정

### CS 질문 자동 생성 기능 구현 중 질문 중복 문제가 발생하였다.

- 모든 질문을 프롬프트에 포함할 경우, OpenAI API 토큰 낭비 우려가 있음
- 기존 질문을 포함하지 않을 경우, 질문 중복 생성 문제가 발생함

### 🧩 해결 방법
`DB 질문 테이블에 keyword 컬럼 추가!`

- 질문 생성 시, 핵심 키워드를 단일 단어 또는 짧은 구절로 입력받아 저장
- 다음 질문 생성 시, 모든 키워드를 프롬프트에 포함하여 기존 질문 정보를 전달

### ✅ 효과
- 프롬프트 길이를 최소화하여 API 토큰 낭비를 방지함
- 중복 질문 생성을 막아 기능의 신뢰도를 높임



<br>

## 📌 향후 개선 사항
- 질문 난이도 조절 기능 추가 (초급/중급/고급)
- 관리자 기능 추가 (신고 게시글/댓글 관리/질문 수정 등)
- 모바일 반응형 UI 개선
