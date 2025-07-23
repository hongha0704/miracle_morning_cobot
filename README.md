🛏️ Miracle Morning & Good Night
===
협동로봇을 활용한 출퇴근 시간 물품 정리 및 세팅 자동화   
ROKEY B-1조 협동-1 Project (ROS2를 활용한 로봇 자동화 공정 시스템 구현 프로젝트)
---

### 🔗 출처 및 라이선스

이 프로젝트는 **두산로보틱스(Doosan Robotics Inc.)**에서 배포한 ROS 2 패키지를 기반으로 합니다.  
해당 소스코드는 [BSD 3-Clause License](https://opensource.org/licenses/BSD-3-Clause)에 따라 공개되어 있으며,  
본 저장소 또한 동일한 라이선스를 따릅니다. 자세한 내용은 `LICENSE` 파일을 참고하시기 바랍니다.

> ⚠️ 본 저장소는 두산로보틱스의 공식 저장소가 아니며, 비공식적으로 일부 수정 및 구성을 포함하고 있습니다.  
> 공식 자료는 [두산로보틱스 공식 홈페이지](http://www.doosanrobotics.com/kr/)를 참고해 주세요.   
> github (https://github.com/DoosanRobotics/doosan-robot2)
---

### 🔨 개발환경
본 프로젝트는 Ubuntu 22.04 (ROS2 humble) 환경에서 개발되었습니다.   
&nbsp;

### 🦾 작업공간
<img src="https://github.com/user-attachments/assets/3e4ca422-712e-4b70-a4cf-7b6686e1667a" width="50%" height="50%" title="px(픽셀) 크기 설정" alt="project_workspace"><img src="https://github.com/user-attachments/assets/ff60e7be-27b8-427a-9b39-d78ca8c5dc56" width="50%" height="50%" title="px(픽셀) 크기 설정" alt="project_workspace"></img>   
&nbsp;

### 💻 코드 실행

#### **Robot Control Node**
code: [robot_control_node.py](rokey_project/rokey_project/robot_control_node.py)
```bash
ros2 run rokey_project robot_control_node
```

#### **Raspberry Pi**
code: [feedback_node.py](rokey_project/rokey_project/feedback_node.py)
```bash
ros2 run rokey_project feedback_node
```
&nbsp;

### 📷 시연 영상
https://youtube.com/shorts/E0jw0PagxaY

---

&nbsp;

## 목차

#### [1. 📘 프로젝트 개요](#1--프로젝트-개요-1)   
#### [2. 👥 프로젝트 팀 구성 및 역할분담](#2--프로젝트-팀-구성-및-역할분담-1)   
#### [3. 🗓 프로젝트 구현 일정](#3--프로젝트-구현-일정-1)   
#### [4. 📌 SKILLS](#4--skills-1)   
#### [5. 🤖 Hardware](#5--hardware-1)   
#### [6. 🎬 System Flow](#6--system-flow-1)   
#### [7. 🛠️ Node Architecture](#7-%EF%B8%8F-node-architecture-1)   
#### [8. ✨ 주요 기능](#8--주요-기능-1)   
#### [9. 🔍 프로젝트 기대효과](#9--프로젝트-기대효과-1)   

---

&nbsp;

## 1. 📘 프로젝트 개요
바쁜 현대인의 출퇴근 시간에 반복되는 물건 정리 및 준비 작업을 협동로봇을 통해 자동화함으로써,   
일상 속 작업 효율을 높이고 사용자 편의를 증대 시키고자 하였음   

### **기획 의도**
- 출근과 퇴근 과정에서 반복적인 선반 정리 및 수납이 반복되어 작지만 지속적인 시간 소모와 불편함을 야기
- 협동로봇을 선반에 적용을 하여, 정리 및 수납 과정을 자동화함으로써 사용자에게 편리함 제공

### **유사 서비스와의 차별점**
- 기존 로봇은 산업 현장 혹은 물류 자동화에 많이 사용되며, 일상에서의 실질적 적용 사례는 거의 없음   
- 협동로봇을 일상생활에 적용해 대중들의 편의를 증진시킴   

&nbsp;

## 2. 👥 프로젝트 팀 구성 및 역할분담
|이름|담당 업무|
|--|--|
|백홍하(팀장)| 협동 로봇 모션 및 알고리즘 코드 작성, 수납 및 꺼내기 좌표 티칭 |
|서형원| 협동 로봇 설정, 수납 및 꺼내기 좌표 티칭 |
|정민섭| Rasberry-Pi 하드웨어 연결 , 제어 노드 및 패키지 작성 |
|정서윤| ROS 비동기 물체 찾기, 수납 및 꺼내기 작성, PPT 작성 및 발표 |

&nbsp;

## 3. 🗓 프로젝트 구현 일정
**진행 일자: 25.05.15(목) ~ 25.05.22(목) (8일)**
<img src="https://github.com/user-attachments/assets/f6969f4f-f75f-4069-a7c7-1a2a29960436" width="100%" height="100%" title="px(픽셀) 크기 설정" alt="project_management"></img>

&nbsp;

## 4. 📌 SKILLS
### **Development Environment**
<div align=left>
  
  ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
  ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
</div>

[![My Skills](https://skillicons.dev/icons?i=ubuntu,vscode&theme=light)](https://skillicons.dev)

### **Robotics**
![ROS](https://img.shields.io/badge/ros-%230A0FF9.svg?style=for-the-badge&logo=ros&logoColor=white)   
[![My Skills](https://skillicons.dev/icons?i=ros&theme=light)](https://skillicons.dev)

### **Programming Languages**
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)   
[![My Skills](https://skillicons.dev/icons?i=python&theme=light)](https://skillicons.dev)

&nbsp;

## 5. 🤖 Hardware
### **Robot**
- Doosan Robotics m0609, OnRobot RG2 Gripper
### **SBC**
- Raspberrypi4 4gb

&nbsp;

## 6. 🎬 System Flow
<img src="https://github.com/user-attachments/assets/c7a137e3-37f4-423e-9d72-eb4948b9b1aa" width="50%" height="50%" title="px(픽셀) 크기 설정" alt="system_flow"></img>

&nbsp;

## 7. 🛠️ Node Architecture
<img src="https://github.com/user-attachments/assets/c821f24d-95ff-41a5-8450-9235f3273d0c" width="50%" height="50%" title="px(픽셀) 크기 설정" alt="node_architecture"></img>

&nbsp;

## 8. ✨ 주요 기능

### 1. 수납 알고리즘 시작
- Check Force condition으로 외력이 감지될 때까지 대기
- y축 외력이 감지되면 수납 알고리즘 시작   
<img src="https://github.com/user-attachments/assets/4fd9eb2e-5751-4213-98b0-5f124727f209" width="28%" height="28%" title="px(픽셀) 크기 설정" alt="image"></img>
<img src="https://github.com/user-attachments/assets/18eb697e-e85a-4368-b787-74f352cf7a8d" width="50%" height="50%" title="px(픽셀) 크기 설정" alt="image"></img>

&nbsp;

## 9. 🔍 프로젝트 기대효과
### **활용 방안**
- 각 가정에 출퇴근 과정에서 정리도우미
- 공장/창고/편의점에서 물품 정리 도우미
- 학교/회사책상 정리 도우미

### **기대 효과**
- 일상생활에 많은 사람들이 사용 가능
- 다양한 물품 및 센서로 기능 확장 가능

&nbsp;
