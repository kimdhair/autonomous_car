# autonomous_car team project
## 1. 프로젝트 개요
- 주제
  - 라즈베리 파이를 활용한 자율 주행 시스템 제작
    
- 목표
  - 머신 러닝으로 차선 인식 주행 및 횡단보도 인식
    
- 개발 환경
  - 라즈베리파이
  - VScode using SSH
  - Python
    
- 주요 기능
  - 차선 인식
  - 횡단보도 인식
  - PID 제어

<img src = "https://github.com/kimdhair/autonomous_car/blob/main/%EC%BD%94%EC%8A%A4%20%EB%B0%8F%20%EC%99%84%EC%84%B1%EC%82%AC%EC%A7%84/outside_car.jpg?raw=true" width="30%"><img src = "https://github.com/kimdhair/autonomous_car/blob/main/%EC%BD%94%EC%8A%A4%20%EB%B0%8F%20%EC%99%84%EC%84%B1%EC%82%AC%EC%A7%84/inside_car.jpg?raw=true" width="30%"><img src = "https://github.com/kimdhair/autonomous_car/blob/main/%EC%BD%94%EC%8A%A4%20%EB%B0%8F%20%EC%99%84%EC%84%B1%EC%82%AC%EC%A7%84/course2.jpg?raw=true" width="30%"></img>

## 2. 데이터 수집 및 모델 제작
- 데이터 수집 및 라벨링
  - openCV를 활용해 각 상황에 대한 데이터에 라벨링을 붙여 직점 수집 (231개)
    
- 데이터 정제
  - 도로 이미지에 관심 구역을 설정하여 모델의 정확도를 높임
    
- 모델 제작
  - 학습 데이터, 검증 데이터, 테스트 데이터를 각각 64%, 16%, 20%로 나눠서 모델 학습

## 3. 통신 및 HW
- HW
  - 라즈베리파이 4B+, 파이 카메라 OV5647, 모터 드라이버 L9110S를 이용하여 제작
    
- 통신
  - SSH 통신을 이용해 라즈베리 파이와 통신 환경 구축

## 4. 시연 영상 링크
https://drive.google.com/file/d/1pmVItlkeg6JMmfP2Wy0x7VWMdyAWHmYB/view
