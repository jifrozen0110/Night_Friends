# Night_Friends 
# 밤길 친구 안드로이드 앱
## 덕성여대 WISET ICT 팀프로젝트(2020)

### 개발 배경
#### 목적
#### 사용자가 늦은 밤에도 안심하고 귀가를 할 수 있을 뿐 아니라, 초행길이여도 그 지역에 대한 정보를 파악하고 경계함으로써 범죄 예방의 효과를 제공하기 위해 개발

### 특장점
#### - 경로 안내 시 안전을 우선시 하여 기존의 길 찾기 서비스와 차별화
#### - 경로 분석에서 더 나아가 사용자의 특성을 분석한 효율적인 밤길 친구 매칭 서비스를 제공 

### 프로젝트 개요
#### 개발 기간 : 20.03 ~ 20.10

#### 인원 : 4명

#### 사용 언어 : Java, php

#### 개발 환경 : Android Studio

### 오픈소스 활용 내역

### 오픈소스 활용 내역
#### 1. T map API
1) 지도,경로안내,POI API 사용
2) 경로 안내, 위치 검색, 안전지수 판단, 경로 이탈 등의 기능에 사용 
#### 2. 공공데이터포털 API
1) CCTV,가로등,유흥업소 위치 사용
2) CCTV,가로등,유흥업소의 위치를 얻어와 지도에 표시 및 안전지수 계산 시 사용
#### 3. 안전 Dream API
1) 안전지대 위치 사용
2) 안전지대의 위치를 얻어와 안전지수 계산 시 사용
#### 라이브러리 : tensorflow, firebase

### SW 기능
#### 1. CCTV,가로등의 정보를 API를 이용해 지도에 표시하여 사용자가 쉽게 파악할 수 있도록 도와줌.

![image](https://user-images.githubusercontent.com/62784314/103169911-52ae4380-4883-11eb-8019-593ffc61fee6.png)

#### 2. 사용자가 원하는 출발지와 목적지를 입력한 후 우선순위를 선택하면 그에 맞는 길을 안전 우선 경로로 추천 

![image](https://user-images.githubusercontent.com/62784314/103169917-56da6100-4883-11eb-83b4-b8d1a18d6bcd.png)

#### 3. 길찾기를 수행하면 여러 경로에 대한 안전지수를 계산하여 보여줌
![image](https://user-images.githubusercontent.com/62784314/103169920-593cbb00-4883-11eb-86c7-7bc87aeee5ea.png)

#### 4. 비슷한 경로를 가진 사용자를 추천하며, 사용자들을 지도에 나타내어 직접 선택할 수 있게 함.
![image](https://user-images.githubusercontent.com/62784314/103169922-5b9f1500-4883-11eb-9c38-b58e731256cf.png)

#### 5. 선택한 사용자와 연결되어 채팅을 진행 
![image](https://user-images.githubusercontent.com/62784314/103169924-5d68d880-4883-11eb-9946-580d62db4adb.png)

#### 6. 긴급상황 발생 시 단말기의 볼륨 Down 버튼을 4번 누르고 5초 이내 취소하지 않으면 112로 자동 신고 
![image](https://user-images.githubusercontent.com/62784314/103169926-5fcb3280-4883-11eb-9ab9-3c130123e7e9.png)

#### 7. 사용자가 원하는 경로를 선택하면 길 안내와 동시에 자동적으로 녹화가 진행
![image](https://user-images.githubusercontent.com/62784314/103169927-622d8c80-4883-11eb-9a99-11d129c70cfa.png)

#### 8. 경로 안내 시작 후 사용자가 정해진 경로를 이탈하면 알림 발생. 해당 알림을 취소하지 않으면 보호자에게 알림 발송.
![image](https://user-images.githubusercontent.com/62784314/103169929-63f75000-4883-11eb-91c0-ee6f08ec4a5b.png)






