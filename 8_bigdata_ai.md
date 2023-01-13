# 빅데이터와 인공지능

## 강의자료 출처
- 생활코딩, 데이터과학, https://opentutorials.org/course/4548/28891


## 데이터 과학을 위한 머신러닝

- 머신러닝은 인공지능을 구현하는 기술임 
- 인공지능, 머신러닝, 딥러닝 관계 

![AI](https://mblogthumb-phinf.pstatic.net/MjAxOTA4MTNfMjEw/MDAxNTY1NjI0MDM4NzU5.gipXXlssyqZ_eIugsfoCDHK91gxUDZd-mgYGhPF1dowg.kfK2-x7iE0amYCcGn_CZI7wpIgK7mrux0ZcNpXliUygg.PNG.pwj6971/20190813_%EC%9D%B8%EA%B3%B5%EC%A7%80%EB%8A%A5%EC%9D%98%EA%B0%9C%EB%85%90%EB%8F%84.png?type=w800)


- 머신러닝은 기계를 학습시켜 인간의 판단을 위임하기 위해서 고안된 기술임
![AI](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/4916/12139.jpeg)

- 수많은 작업들이 머신러닝이라고 불리는 여러기술들에 의해서 구현되고 있고 구현되려 하고 있음 

  - 전염병의 양성 판정

  - 자동번역

  - 자율주행
  ![자율주행](https://cdn.aitimes.com/news/photo/202206/145065_151816_1416.jpg)


- 인공지능을 즐겁게 공부하기 위해 필요한 준비물
  - ‘상상력’ 이 필요함 
    ![AI](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/4916/12000.png)


  - 해결하고자 하는 문제가 나에게 중요한 문제라고 생각하고 공부하기 

    ![AI](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/4916/12134.jpeg)



  - 해결하고자 하는 문제가 남의 문제이거나 사소하다면 공부 자체가 문제가 되어서 우리를 억압하는 독재자가 됨 

    ![AI](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/4916/12135.jpeg)


- “공부가 구원자가 되느냐? 독재자가 되느냐?” 는 여러분과 이 수업이
얼마나 좋은 팀워크를 발휘하느냐에 달려있습니다.

- 최고의 팀을 만들어봅시다.

![AI](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/4916/12138.jpeg)


## 머신러닝이란?

- 인간의 오랜 고민 
  - 좋은 결정을 하는 것 
    - 오늘 점심을 무엇을 먹을까? 가격? 칼로리? 
    - 어떤 제품을 고를까? 가격? 브랜드? 
  - 어떻게 하면 결정을 잘 할 수 있을까?
  ![ML](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/4916/12008.png)


- 결정의 의미 
  - 비교와 선택으로 이루어 짐 
  ![ML](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/4916/12143.jpeg)

  - 무엇이 더 좋은지, 무엇이 더 나쁜지를 비교할 수 있다면, 선택은 쉬울 것임 
  ![ML](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/4916/12010.png)

- 물건을 사려고 하는 상황 
  - 동일한 두 제품 A, B가 있음 
  - A가 1000원, B가 2000원 이다. 
  - 당연히 A를 선택할 것임 

  ![ML](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/4916/12013.png)

- 집으로 가는 길의 거리 
  - A가 1000m, B가 500m 
  - B를 선택 

  ![ML](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/4916/12014.png)

- 크고 작음을 비교할 수 있다면 선택이 쉬움 

- 그러나, 실제 문제는 그 보다 복잡한 선택이 요구됨 
  - A와 B의 대소관계를 모름 
  - 비교해야할 특징이 너무 많음 (가격, 브랜드, 내 경제 상황... )
  - 결정을 내리는 일이 어려워짐 

- 스마트폰을 사려고 하는 상황 
  - 제품의 특징을 살펴보니... 

  <img width="730" alt="휴대폰1" src="https://user-images.githubusercontent.com/58820851/212233560-17bc9b1e-6a96-4ce0-a739-8f15ac12c76c.PNG">

  - 무게: 제품 B가 제품 A보다 가볍다 --> B 선택? 
  - 속도: 제품 A가 제품 B보다 빠르다 --> A 선택?
  - 용량: 제품 A가 제품 B보다 크다 --> A 선택?
  - 가격: 제품 A가 제품 B보다 비싸다 --> B 선택? 


  - 제품의 특징이 4개가 아니라 20개이고, 제품의 종류가 2개가 아니라 100종류라면? 
    - 선택은 훨씬 어려워짐 
  <img width="734" alt="휴대폰2" src="https://user-images.githubusercontent.com/58820851/212233607-620d3444-355a-43f2-bd14-2fed0de8b7f9.PNG">


- 실제 우리가 마주하는 문제들은 선택하기가 훨씬 어려운 문제들이 많음 

![ML](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/4916/12145.jpeg)

- 인류는 좋은 결정을 하기 위해 노력해 옴 
  - 수를 만들어서 대소관계를 표준화 시킴 
  - 숫자 덕분에 크기에 대해서 엄밀하게 인식할 수 있게 되었고, 정밀하게 소통할 수 있게 됨 
  - 수(number)는 비교를 위한 가장 중요한 도구로, 수의 발명은 혁명적 사건임 
![ML](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/4916/12146.jpeg)


- 인류는 복잡한 세상을 숫자로 표현하기 위한 여러 가지 방법을 찾아냄 
  - 이 방법들을 모아서 '통계'라는 이름을 붙임 


- 컴퓨터가 등장하면서 인류는 단순한 계산으로부터 해방됨 
- 좀 더 인간적인 영역인 '결정하기'에 전념할 수 있게 됨 
- 이런 과정을 통해 인류의 결정능력은 비약적으로 향상됨 
- 인간의 고유한 영역으로 남아있던 결정을 기계에 맡기고 싶어함 


![ML](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/4916/12020.png)

- "하나를 가르치면 열을 안다" 
  - 공부를 하면 똑같은 문제 뿐만 아니라 비슷한 문제도 해결할 수 있는 총명한 사람을 두고 하는 말 

- 이러한 총기를 기계에 부여해서 스스로 결정하도록 할 수 없을까? 라는 꿈을 꾼 사람들에 의해서 만들어진 기술 
  - **기계학습**
  - 영어로 **Machine Learning**



- 머신러닝이 있다고 두뇌가 필요 없을까? 
  - 망원경이 있다고 눈이 필요없지 않음. 망원경은 눈을 더욱 멀리 볼 수 있게 도와줌 
  - 포크레인이 있다고 손이 필요없어 지는 것이 아님 
  - 자동차가 있다고 발이 쓸모없어지는 것이 아님 
  - 머신러닝이 있다고 두뇌가 필요 없어지는 것은 절대 아님 


- 머신러닝은 우리의 두뇌가 가진 중요한 기능인 판단능력을 확장해서 
- 우리의 두뇌가 더욱 빠르고 정확하게 결정할 수 있게 돕는 도구임 


- 머신러닝을 통해 우리의 두뇌를 더욱 두뇌답게 만들어봅시다! 


## Teachable Machine 

- 머신러닝을 이해하기 위해서 꼭 수학과 코딩을 알아야 하는 것은 아님 
- 수학과 코딩없이 머신러닝을 이용할 수 있게 해주는 서비스들이 등장하고 있음 

- 미래에는 수학자나 프로그래머가 아니라도 누구나 머신러닝을 이용해서 기계를 학습시키고, 그것을 활용해서 자신의 문제를 해결하고 있을 것임 

- 컴퓨터의 등장 
  - 처음 컴퓨터가 등장했을 때 소수의 과학자들만 다루는 비밀무기처럼 인식됨 
  - 오늘날은 모든 사람들이 스마트폰을 이용하며 컴퓨팅을 하고 있음 
  - 이것이 머신러닝의 미래 모습 

![TM](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/4916/12174.jpg)



- Teachable Machine 
  - https://teachablemachine.withgoogle.com/

  

