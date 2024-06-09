# **[2024년 1학기] 디지털제어**

본 repo는 서울시립대학교 전자전기컴퓨터공학부 학부/대학원 공통 교과목인 **"디지털제어(Digital Control)"** 교과목의 학습자료를 관리하기 위해 작성되었습니다.

- **수업 학기** : 2024년 1학기
- **강의자** : 서울시립대학교 전자전기컴퓨터공학부 박경훈 교수 (gyunghoon.park@uos.ac.kr)
- **수업 조교** : 서울시립대학교 전자전기컴퓨터공학과 김준수 박사과정생

## **강의 교안 \& MATLAB/Simulink 예제**

본 강의에서는 제어 이론과 제어기 설계 능력을 동시에 함양하기 위하여 MATLAB/Simulink 예제를 추가로 제공하고 있습니다.

- **Ch. 0. Introduction to Course: Why Digital Control**
  - [Lecture Note](https://github.com/CDSL-UoS/Course_Digital-Control_2024/blob/main/Lecture_Notes/CH00_Introduction.pdf)
- **Ch. 2. Discrete-time Systems and the $z$-Transform**
  - [Lecture Note](https://github.com/CDSL-UoS/Course_Digital-Control_2024/blob/main/Lecture_Notes/CH02_Discrete-time%20Systems%20and%20z-Transform.pdf)
  - [MATLAB/Simulink Simulation 2-a](https://github.com/CDSL-UoS/Course_Digital-Control_2024/tree/main/MATLAB-Simulink/CH02/2-a) : $z$-transform의 이해
  - [MATLAB/Simulink Simulation 2-b](https://github.com/CDSL-UoS/Course_Digital-Control_2024/tree/main/MATLAB-Simulink/CH02/2-b) : 이산 시간 시스템의 구현
  - [MATLAB/Simulink Simulation 2-c](https://github.com/CDSL-UoS/Course_Digital-Control_2024/tree/main/MATLAB-Simulink/CH02/2-c) : 상태변수 모델의 이해
- **Ch. 3. Sampling and Reconstruction**
  - [Lecture Note](https://github.com/CDSL-UoS/Course_Digital-Control_2024/blob/main/Lecture_Notes/CH03_Sampling%20and%20Reconstruction.pdf)
  - [MATLAB/Simulink Simulation 3-a](https://github.com/CDSL-UoS/Course_Digital-Control_2024/tree/main/MATLAB-Simulink/CH03/3-a) : 샘플링과 데이터 홀드의 이해 ([HTML](/MATLAB-Simulink/CH03/3-a/main.html))
- **Ch. 4. Open-loop Discrete-time Systems**
  - [Lecture Note](https://github.com/CDSL-UoS/Course_Digital-Control_2024/blob/main/Lecture_Notes/CH04_Open-loop%20Discrete-time%20Systems.pdf)
  - [MATLAB/Simulink Simulation 4-a](https://github.com/CDSL-UoS/Course_Digital-Control_2024/tree/main/MATLAB-Simulink/CH04/4-a) : 펄스 전달함수의 이해 ([HTML](/MATLAB-Simulink/CH04/4-a/main.html))
  - [MATLAB/Simulink Simulation 4-b](https://github.com/CDSL-UoS/Course_Digital-Control_2024/tree/main/MATLAB-Simulink/CH04/4-b) : 샘플 데이터 시스템의 상태변수 모델 ([HTML](/MATLAB-Simulink/CH04/4-b/main.html))
  - [MATLAB/Simulink Simulation 4-c](https://github.com/CDSL-UoS/Course_Digital-Control_2024/tree/main/MATLAB-Simulink/CH04/4-c) : 연결된 개루프 시스템 모델 이해 ([HTML](/MATLAB-Simulink/CH04/4-c/main.html))
  - [MATLAB/Simulink Simulation 4-d](https://github.com/CDSL-UoS/Course_Digital-Control_2024/tree/main/MATLAB-Simulink/CH04/4-d) : 시간 지연이 있는 샘플 데이터 시스템의 해석 (**Optional**, TBA)
- **Ch. 5. Closed-loop Systems**
  - [Lecture Note](https://github.com/CDSL-UoS/Course_Digital-Control_2024/blob/main/Lecture_Notes/CH05_Closed-loop%20Systems.pdf)
  - [MATLAB/Simulink Simulation 5-a](https://github.com/CDSL-UoS/Course_Digital-Control_2024/tree/main/MATLAB-Simulink/CH05/5-a) : 폐루프 샘플 데이터 시스템의 이해
- **Ch. 6. System Time-response Characteristics** 
  - [Lecture Note](/Lecture_Notes/CH06_System%20Time-response%20Characteristics.pdf)
  - [MATLAB/Simulink Simulation 6-a](https://github.com/CDSL-UoS/Course_Digital-Control_2024/tree/main/MATLAB-Simulink/CH06/6-a) : 폐루프 샘플 데이터 시스템의 시스템 응답
  - [MATLAB/Simulink Simulation 6-b](https://github.com/CDSL-UoS/Course_Digital-Control_2024/tree/main/MATLAB-Simulink/CH06/6-b) : 시스템 유형과 내부 모델 이론 소개
- **Ch. 7. Stability Analysis Techniques**
  - [Lecture Note](https://github.com/CDSL-UoS/Course_Digital-Control_2024/blob/main/Lecture_Notes/CH07_Stability%20Analysis%20Techniques.pdf)
  - [MATLAB/Simulink Simulation 7-a](https://github.com/CDSL-UoS/Course_Digital-Control_2024/tree/main/MATLAB-Simulink/CH07/7-a) : 이산 시간 개루프 시스템의 안정성 해석
  - [MATLAB/Simulink Simulation 7-b](https://github.com/CDSL-UoS/Course_Digital-Control_2024/tree/main/MATLAB-Simulink/CH07/7-b) : 근 궤적법과 Jury 판별법을 이용한 안정성 판별
  - [MATLAB/Simulink Simulation 7-c](https://github.com/CDSL-UoS/Course_Digital-Control_2024/tree/main/MATLAB-Simulink/CH07/7-c) : 나이퀴스트 선도를 이용한 안정성 판별과 이득/위상 여유
- **Ch. 8. Digital Control Design** 
   - [Lecture Note](https://github.com/CDSL-UoS/Course_Digital-Control_2024/blob/main/Lecture_Notes/CH08_Digital%20Control%20Design.pdf)
   - [MATLAB/Simulink Simulation 8-a](https://github.com/CDSL-UoS/Course_Digital-Control_2024/tree/main/MATLAB-Simulink/CH08/8-a) : 민감도 함수의 이해
   - [MATLAB/Simulink Simulation 8-b](https://github.com/CDSL-UoS/Course_Digital-Control_2024/tree/main/MATLAB-Simulink/CH08/8-b) : 위상 뒤짐 보상기 설계
   - [MATLAB/Simulink Simulation 8-c]() : PID 제어기 설계 및 구현 (TBA)
 - **Ch. 9. Pole-assignment Design and State Estimation & Ch. 11. Linear Quadratic Optimal Control**
   - [Lecture Note]()
   - [MATLAB/Simulink Simulation 9-a](https://github.com/CDSL-UoS/Course_Digital-Control_2024/tree/main/MATLAB-Simulink/CH09_11/9-a) : 상태 궤환 제어기 설계와 구현
   - [MATLAB/Simulink Simulation 9-b](https://github.com/CDSL-UoS/Course_Digital-Control_2024/tree/main/MATLAB-Simulink/CH09_11/9-b) : 상태 추정기 기반 출력 궤환 제어기 설계 및 구현
   - [MATLAB/Simulink Simulation 11-a]() : 선형 이차 추종기 설계 (**Optional**, TBA) 
   - [MATLAB/Simulink Simulation 11-b]() : 칼만 필터 설계 (**Optional**, TBA)  
- **Ch. 10. System Identification of Discrete-time Systems** (**Optional**, TBA)
   - [Lecture Note]()
   - [MATLAB/Simulink Simulation 10-a]() : (**Optional**, TBA)

## **Homeworks**

(TBA)