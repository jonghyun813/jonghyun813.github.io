# Beat the Brick Project

### 프로젝트 소개

아래 그램과 같이 로봇과  Arduino Uno, 다양한 센서를 활용하여 경기장 내에 존재하는 장애물을 경기장 밖으로 밀어내는 프로젝트이다.

<img src="../assets/images/2024-05-04-Beat the Brick Project/스크린샷 2024-05-04 155100.png" alt="스크린샷 2024-05-04 155100" style="zoom: 25%;" />

<img src="../assets/images/2024-05-04-Beat the Brick Project/스크린샷 2024-05-04 155118.png" alt="스크린샷 2024-05-04 155118" style="zoom: 25%;" />

사용한 센서

- Line Finer : 경기장 내에 존재하는 선을 탐지하여 선 위에 로봇이 존재할 경우 뒤로 이동하기 위해 사용하였다.
- Ultrasonic Sensor : 로봇의 앞에 존재하는 물체까지의 거리를 측정하기 위한 센서. 로봇 앞에 놓인 물체가 장애물이 아니라 벽일 수 있기에, 두 개의 센서를 위, 아래로 배치하여 현재 로봇 앞에 벽이 있는 지, 장애물이 있는 지 구분할 수 있도록 하였다.



### Demos

![demo_vid1](https://github.com/jonghyun813/Beat-the-Brick/assets/66056087/7956ae20-9925-43e4-a2d6-090497394164)



![demo_vid2](https://github.com/jonghyun813/Beat-the-Brick/assets/66056087/f71362c0-4e80-4817-b6b0-62fe589aace0)



