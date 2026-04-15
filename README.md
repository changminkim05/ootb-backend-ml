# 👕 OOTB 의류 사이즈 추천 시스템

![OOTB_Logo](/src/main/webapp/resources/assets/images/browser/LOGO.png)

---

## 📌 프로젝트 소개
회원가입 시 입력한 정보를 기반으로 사용자의 신체 치수를 예측하고,  
이를 활용하여 의류 구매 시 적절한 사이즈를 추천하는 서비스입니다.  

또한 사용자 후기를 반영하여 데이터를 보완함으로써  
추천 정확도를 지속적으로 개선할 수 있도록 설계되었습니다.

---

## 🗓 개발 기간
2024.07.02 ~ 2024.08.02 (약 1개월)

---

## 👨‍💻 담당 역할 (김창민)
- 사용자 데이터 기반 **신체 치수 예측 머신러닝 모델 개발**
- 추천 결과를 도출하는 **사이즈 추천 로직 구현**
- **백엔드와 머신러닝 모델 연동 처리**
- 추천 결과를 제공하는 **API 개발**

---

## 🛠 기술 스택

### Backend
- Java 1.6
- Spring Framework 5.0.7
- MyBatis

### ML
- Python (신체 치수 예측 모델)

### Database
- MySQL

### Infra
- Apache, Tomcat

### Collaboration
- Notion

---

## 🏗 프로젝트 구조
- 사용자 입력 데이터 → 신체 치수 예측 (ML)
- 예측 결과 기반 의류 사이즈 추천
- 사용자 후기 데이터를 통한 지속적 성능 개선

---

## 🚀 주요 기능
- 사용자 신체 치수 기반 의류 사이즈 추천
- 후기 데이터를 활용한 추천 정확도 개선
- 위시리스트 기반 선호 의류 추천
- 회원/비회원 기반 맞춤 입력 처리

---

## ⚠️ 트러블 슈팅

### 1. JSP EL 표현식 충돌 문제
JSP에서 JavaScript 템플릿 리터럴(`${}`) 사용 시 EL로 해석되는 문제 발생  

→ `${}` 앞에 `\`를 추가하여 JavaScript 구문으로 인식하도록 처리

---

### 2. 모달 함수 중복 호출 문제
`showModal`과 `closeModal` 이벤트가 중복 등록되어 의도치 않은 동작 발생  

→ 이벤트 리스너를 단일화하여 중복 호출 방지

---

## 🖼 주요 화면
![mainpage](/src/main/webapp/resources/assets/images/browser/mainpage.png)
![mypage](/src/main/webapp/resources/assets/images/browser/mypage.png)
![faqpage](/src/main/webapp/resources/assets/images/browser/faqpage.png)

---

## 👥 팀 구성
- 김창선 - PM, Back-end  
- 김창민 - 머신러닝, Back-end  
- 방찬혁 - Back-end, 크롤링, Database  
- 양준영 - Front-end, Back-end  
