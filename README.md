# Goldenpass-paltform

### 2020.07 ~ 2020.08 (4주)

### Code States & 기업 협업 팀 프로젝트

### 0. 소개

- Code States에서 진행한 기업 협업 팀 프로젝트 입니다.

  #### 0-1. 팀 구성

  - Front-end : 2명
  - Back-end : 2명

### 1. Project 소개

- 측정 또는 평가 기준을 통해 미리 분석된 선수 데이터를 비교 및 평가가 가능하도록 시각화하여 제공하는 웹 프로젝트입니다. </br>

  #### 1-1. Stack

    - **Language** : Javascript, HTML/CSS, Sass </br>
    - **Library** : React.js, Hook, Redux, Apexcharts </br>
    - **tools** : Miro, zeplin, slack, zoom
    
  #### 1-2. Workflow - Front-end
  <img width="720" alt="bepro11 - client work flow" src="https://user-images.githubusercontent.com/61106972/96485652-9aa75d80-1277-11eb-8550-945f8b6358c9.png">

### 2. 역할, Front-end

- Pair
  - 개발 환경 initial set
  
    - CRA set
    - Redux set
    - Component Route

- Solo 
  - 선택한 선수 정보를 보여주는 선수 개인 데이터 페이지와 좌측 고정 Nav bar를 맡아 작업하였습니다.
  
    - Nav bar
    
      - Logo 위치 지정
      - Button 구현
      
    - 선수 개인 데이터 페이지
    
      - 페이지 내 전반적 화면 Layout 구성
      
        - Flexbox와 Table, Apexcharts를 활용하여 선수 기본 정보 & 기본 Data Charts 출력
        - 페이지 내 선수 기본 정보 화면 고정
        - 페이지 내 데이터 값 별로 중첩 Routing 적용
        
      - 측정 데이터
      
        - Flexwrap을 활용하여 component간 일정 간격, 화면 비율 유지
        - 측정 일자 내 데이터 항목으로 나누어 출력
        - Apexcharts를 활용하여 데이터 값 시각화
        
      - 경기 데이터 
      
        - 항목 별로 나누어 Table표 분류
        
      - 성장 데이터
      
        - Flexbox를 활용하여 component간 일정 간격, 화면 비율 유지 
        - 데이터 항목으로 분류하여 해당 데이터의 측정 일자 간 비교할 수 있는 데이터 출력
        - Apexcharts를 활용하여 데이터 값 시각화
        
      - 경기 영상
      
        - 해당 기업 경기 영상 페이지로 이동 링크 연결

### 3. 담당 Page 시연 GIF

- #### 측정 데이터

![측정 데이터](https://user-images.githubusercontent.com/61106972/96480873-c4f81b80-1275-11eb-86d1-b777611484fb.gif)

- #### 경기 데이터

![경기 데이터](https://user-images.githubusercontent.com/61106972/96481433-772fe300-1276-11eb-9c56-14bcf5bfe936.gif)

- #### 성장 데이터

![성장데이터](https://user-images.githubusercontent.com/61106972/96478925-38e4f480-1273-11eb-9fa4-10c029b65f27.gif)
