# 다기능 스마트 조명 기기의 제작<br>(Production of Multi-Functional Smart Lighting Device)

- 기여자: 이승진, 조준호
- 프로젝트 수행 기간
  - 1차: 2021. 6. 21. ~ 2021. 7. 9.
  - 2차: 2021. 7. 19 ~ 2021. 8. 5.

## 배경
- 코로나19로 인해 비접촉 기술에 대한 관심이 높아지면서 '스마트 홈'이 주거 시설 분양 시장 트렌드로 자리 잡아가고 있다.
- 최신 기술을 활용해 각종 실내 기기 등을 스마트폰으로 제어할 수 있도록 하는 등 편리함을 중요시하고 있다.

## 목표
- 스마트폰, 태블릿 등 모바일 기기로 조명을 제어할 수 있도록 한다.
- 조명 색상을 사용자가 지정한 색상으로 자유롭게 변경할 수 있도록 구현한다.
- 사용자가 개개인의 성향에 맞추어 조명을 활용할 수 있도록 한다.

## 제품 설계
### 구조도
![구조도(최종)](https://user-images.githubusercontent.com/91407433/152562616-9cb45ee6-e707-42b5-bc99-4f0c16f9a453.png)
![아두이노_설계도](https://user-images.githubusercontent.com/91407433/152562810-2a43c93b-2618-4875-81f6-db2237567ad0.png)
> 4개의 조명틀은 각각 18cm × 20cm × 5cm 규격으로 모델링

### 주요 재료 목록
- 아두이노 우노 R3 초보자 키트 스텝 2 / RS-015814
- 아두이노 보드 전원 공급용 9V 1A 어댑터
- 아두이노 블루투스4.0 BLE HM-10 모듈 / HM10 Arduino BLE
- 아두이노 미니 소형 적외선 PIR 인체감지 모션센서 / Arduino PIR Sensor
- 네오픽셀 RGB LED 스트립 5M 5V 방수타입 DM2950
- 신도리코 3D프린터 PLA 리필 필라멘트 / 신도_PLA_White

## 제품 구현
### 제품 외관
![외관](https://user-images.githubusercontent.com/91407433/152563664-bf8acd09-56c3-4293-950a-8b5695c82ffc.jpeg)

### 블루투스 연결

### 제품 기능
#### 밝기 조절
#### 자동 밝기
#### 인체 감지
#### 단색 모드
#### 무지개 모드
#### 그라데이션 모드
#### 커스텀 모드
#### 알람 모드

## 개선사항 및 향후 연구 방향
- 블루투스 통신과 Wi-Fi 통신 기술을 모두 사용할 수 있도록 구현
- 야외에서 간이 안전 조명으로 활용할 수 있도록 건전지 커넥터 연결
- 벽면에 부착할 수 있도록 외형 모델링
- 장시간 사용 시에도 발열이 일어나지 않도록 전원 설계
- 더욱 다양한 기능의 추가 및 사용자 자유도 향상

## [부록] 초기 프로토타입
