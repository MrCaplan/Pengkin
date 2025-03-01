# 돌봄 사각지대에 놓인 사회적약자를 위한 상황인지형 감정케어 로봇 Pengkin 🤖
## 프로젝트 시연 영상 
![Image](https://github.com/user-attachments/assets/1efcbd71-199c-4cc2-b824-92279112bca2)

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

## 3. 프로젝트 내용 - SW 주요기능
### 3.1 SW 주요기능 - Android [공기값 측정]
- 아두이노에서 얻은 가스 값을 App 메인화면에 띄운 뒤, 
가스수치가 이상치를 가질때(400이상)
보호자에게 가스누출 경고 문자 전송. 
  - Cf.) 보호자 전화번호는 사용자가 회원가입을 할 때 
입력한 firebase에 저장된 값을 사용

<img src="https://github.com/MrCaplan/Pengkin/blob/main/pictures/%E1%84%8B%E1%85%A2%E1%86%B81.png" width="200" height="400"/> <img src="https://github.com/MrCaplan/Pengkin/blob/main/pictures/%E1%84%8B%E1%85%A2%E1%86%B82.png" width="200" height="400"/> 
<img src="https://github.com/MrCaplan/Pengkin/blob/main/pictures/%E1%84%86%E1%85%AE%E1%86%AB%E1%84%8C%E1%85%A11.png" width="300" height="150"/> 

### 3.2 SW 주요기능 - Android [수동 조작]
- 버튼을 누르면 안드로이드 어플에서 아두이노로 블루투스 신호 값을 전송해 이 값으로 모터를 구동

<img src="https://github.com/MrCaplan/Pengkin/blob/main/pictures/%E1%84%89%E1%85%AE%E1%84%83%E1%85%A9%E1%86%BC%E1%84%8C%E1%85%A9%E1%84%8C%E1%85%A1%E1%86%A8%E1%84%92%E1%85%AA%E1%84%86%E1%85%A7%E1%86%AB.png" width="200" height="400"/> <img src="https://github.com/MrCaplan/Pengkin/blob/main/pictures/%E1%84%89%E1%85%AE%E1%84%83%E1%85%A9%E1%86%BC%E1%84%8C%E1%85%A9%E1%84%8C%E1%85%A1%E1%86%A8%E1%84%89%E1%85%B5%E1%86%AF%E1%84%92%E1%85%A2%E1%86%BC%E1%84%8C%E1%85%A1%E1%86%BC%E1%84%86%E1%85%A7%E1%86%AB.png" width="300" height="200"/> 

### 3.3 SW 주요기능 - 감정인식
- Haar cascade 분류기를 사용해 표정을 검출한 뒤 표정에 맞는 프롬프트를 생성

<img src="https://github.com/MrCaplan/Pengkin/blob/main/pictures/%E1%84%91%E1%85%AD%E1%84%8C%E1%85%A5%E1%86%BC%E1%84%80%E1%85%A1%E1%86%B7%E1%84%8C%E1%85%B5%E1%84%92%E1%85%AA%E1%84%86%E1%85%A7%E1%86%AB.png" width="500" height="200"/> 

### 3.4 SW 주요기능 - 자세감지
1. 사용자가 ＂집중모드”를 요청하고 30분 이상 앉아있을 경우 스트레칭 권유 (앉음 자세는 mediapipe로 분류)
<img src="https://github.com/MrCaplan/Pengkin/blob/main/pictures/%E1%84%8C%E1%85%A1%E1%84%89%E1%85%A6%E1%84%80%E1%85%A1%E1%86%B7%E1%84%8C%E1%85%B5.png" width="300" height="200"/> 
2. 사용자와 펭킨간의 대화가 3턴 이상 지나면 사용자의 감정에 따른 스트레칭 권유
<img src="https://github.com/MrCaplan/Pengkin/blob/main/pictures/%E1%84%8C%E1%85%B5%E1%86%B8%E1%84%8C%E1%85%AE%E1%86%BC%E1%84%86%E1%85%A9%E1%84%83%E1%85%B3.png" width="400" height="200"/> 

### 3.5 SW 주요 기능 – 대화형 AI
- Open ai의 gpt-3.5-turbo api를 사용하여 사용자와의 대화를 구축
<img src="https://github.com/MrCaplan/Pengkin/blob/main/pictures/%E1%84%80%E1%85%A1%E1%86%B7%E1%84%8C%E1%85%A5%E1%86%BC%E1%84%8F%E1%85%A9%E1%86%AB%E1%84%89%E1%85%A9%E1%86%AF.png" width="600" height="250"/>

## 4. 프로젝트 내용 - HW 주요기능
### 4.1 HW 주요 기능 - 공기질 측정 
- mq135 공기질 센서와 HC-06 블루투스를 활용해 
아두이노 보드에 연결하여 mq135에서 들어온 값을 읽고, 
읽은 값을 안드로이드에 전송함.

<img src="https://github.com/MrCaplan/Pengkin/blob/main/pictures/%E1%84%89%E1%85%A6%E1%86%AB%E1%84%89%E1%85%A5%E1%84%87%E1%85%AE%E1%84%8E%E1%85%A1%E1%86%A8%E1%84%89%E1%85%A1%E1%84%8C%E1%85%B5%E1%86%AB.png" width="200" height="200"/> <img src="https://github.com/MrCaplan/Pengkin/blob/main/pictures/%E1%84%89%E1%85%A6%E1%86%AB%E1%84%89%E1%85%A5%E1%84%8B%E1%85%A7%E1%86%AB%E1%84%80%E1%85%A7%E1%86%AF%E1%84%89%E1%85%A1%E1%84%8C%E1%85%B5%E1%86%AB.png" width="200" height="200"/>

### 4.2 HW 주요 기능 - 실시간 객체 추적
- ESP32-Cam 카메라 & tensorflow Api 사용
- COCO dataset을 사용해 사람을 인식 후 좌표 값을 구한 뒤 BoundingBox 의 가로 값이 400 이하 일 때 전진 하고, 400 이상 일 때 멈춤
- 중심 좌표를 구한 BoundingBox 값이 중심에서 200 이상 벗어난다면 오른쪽 또는 왼쪽 방향으로 추적

<img src="https://github.com/MrCaplan/Pengkin/blob/main/pictures/%E1%84%80%E1%85%A2%E1%86%A8%E1%84%8E%E1%85%A6%E1%84%8E%E1%85%AE%E1%84%8C%E1%85%A5%E1%86%A8.png" width="200" height="200"/> <img src="https://github.com/MrCaplan/Pengkin/blob/main/pictures/%E1%84%92%E1%85%A1%E1%84%83%E1%85%B3%E1%84%8B%E1%85%B0%E1%84%8B%E1%85%A5%E1%84%8B%E1%85%A7%E1%86%AB%E1%84%80%E1%85%A7%E1%86%AF%E1%84%89%E1%85%A1%E1%84%8C%E1%85%B5%E1%86%AB.jpg" width="200" height="200"/> 

## 5. Problem Shooting

### 5.1.1KT AI Makers kit 구매 후 모든 소프트웨어 직접 개발하며 많은 시간 소모
#### Q. 일반 라즈베리파이 보드를 안 사고 Kt AI Makers kit를 구매한 이유?
A. 오토런 사용을 위해서.

#### Q. 오토런이 뭔데?
A. Kt AI Makers kit의 노랑버튼을 터치 했을 때 블록코딩 작품이 자동으로 실행되는 기능.

#### Q. 굳이 블록코딩 써야되는 이유가 뭐였는데?
A.  표정 분석, 자세 인식, 사용자와 시스템 간의 대화를 파이썬 말고 블록코딩으로 구현한다면 보다 쉽게 개발 할 수 있을 것 같아 설계 단계에서 그리하기로 결정했었음. 그래서 부품이 오기 전까진 실제로 블록코딩으로 개발을 하고 웹상에서 테스트를 했었음.

### 5.1.2 케이블 연결 문제
오토런을 사용하려면 노트북과 코디니팩 간에 케이블이 항상 연결되어 있어야 하는데 그럼 로봇의 주행이 자유롭지 못할 것.

### 5.1.3 Latency 문제
그래서 오토런 말고 코디니팩이 결론적으론 라즈베리파이 보드를 사용하는거니, 노트북으로 원격 접속을 하여 블록코딩을 사용하기로 함. 하지만 이렇게 사용하니 속도가 너무 느려 원활한 대화가 이뤄지지 않았음.
























