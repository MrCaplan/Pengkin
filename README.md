# 돌봄 사각지대에 놓인 사회적약자를 위한 상황인지형 감정케어 로봇 Pengkin 🤖

## 1. 개요
### 1.1 주제 선정 배경 
- 사회적 관계 부족
- 헬스케어 관심 및 중요성 증가
- 돌봄 사각지대에 놓인 사람들 (아동, 노인, 장애인)

###  1.2 프로젝트 설명 
- 펭귄 + Kind = Pengkin
- 상황인지형 감정케어 로봇 펭킨은 아두이노 센서 및 라즈베리파이를
활용하여 돌봄사각지대에 놓여진 소외계층들을 정서적 및 신체적으로
보살핌으로써 삶의 질을 제고하고 주 돌봄자에게 효율적인 보탬을
도모하고자 기획함

### 1.3 프로젝트에서 나의 역할 
- PM

### 1.4 프로젝트 기간 
- 6 Mar 2024 ~ 6 Sep 2024
<img src="https://github.com/MrCaplan/Pengkin/blob/main/pictures/%E1%84%80%E1%85%A1%E1%86%AB%E1%84%90%E1%85%B3%E1%84%8E%E1%85%A1%E1%84%90%E1%85%B3.png" width="800" height="200"/>

## 2. 프로토타입 및 회로도 
### 2.1 프로토타입 및 초기 디자인 
<img src="https://github.com/MrCaplan/Pengkin/blob/main/pictures/%E1%84%91%E1%85%B3%E1%84%85%E1%85%A9%E1%84%90%E1%85%A9%E1%84%90%E1%85%A1%E1%84%8B%E1%85%B5%E1%86%B81.png" width="100" height="200"/> <img src="https://github.com/MrCaplan/Pengkin/blob/main/pictures/%E1%84%91%E1%85%B3%E1%84%85%E1%85%A9%E1%84%90%E1%85%A9%E1%84%90%E1%85%A1%E1%84%8B%E1%85%B5%E1%86%B82.png" width="100" height="200"/> 

### 2.2 화면 설계도
<img src="https://github.com/MrCaplan/Pengkin/blob/main/pictures/%E1%84%92%E1%85%AA%E1%84%86%E1%85%A7%E1%86%AB%E1%84%89%E1%85%A5%E1%86%AF%E1%84%80%E1%85%A8%E1%84%83%E1%85%A9.png" width="600" height="500"/> 

### 2.3 회로도 
<img src="https://github.com/MrCaplan/Pengkin/blob/main/pictures/%E1%84%87%E1%85%A1%E1%84%8F%E1%85%B1%E1%84%80%E1%85%AE%E1%84%83%E1%85%A9%E1%86%BC%E1%84%92%E1%85%AC%E1%84%83%E1%85%A9%E1%84%85%E1%85%A9.png" width="300" height="250"/> <img src="https://github.com/MrCaplan/Pengkin/blob/main/pictures/%E1%84%80%E1%85%A9%E1%86%BC%E1%84%80%E1%85%B5%E1%84%8C%E1%85%B5%E1%86%AF%E1%84%8E%E1%85%B3%E1%86%A8%E1%84%8C%E1%85%A5%E1%86%BC%E1%84%92%E1%85%AC%E1%84%85%E1%85%A9%E1%84%83%E1%85%A9.png" width="300" height="250"/>

## 3. 프로젝트 내용 
### 3.1 SW 주요기능 - Android 공기값 측정
- 아두이노에서 얻은 가스 값을 App 메인화면에 띄운 뒤, 
가스수치가 이상치를 가질때(400이상)
보호자에게 가스누출 경고 문자 전송. 
  - Cf.) 보호자 전화번호는 사용자가 회원가입을 할 때 
입력한 firebase에 저장된 값을 사용








