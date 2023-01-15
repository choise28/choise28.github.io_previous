# 빅데이터와 인공지능

## 강의자료 출처
- 생활코딩, 데이터과학, https://opentutorials.org/course/4548/28891
- 모두의 연구소, https://modulabs.co.kr/blog/ai-bigdata/



## 빅데이터와 인공지능의 관계 

- 인공지능(Artificial Intelligence)과 빅데이터(Big Data)의 상호관계
  - 인간이 지능을 늘려가는 과정은 지식을 습득하는 과정
  - 지식은 경험으로부터, 배움으로부터 얻게 됨
  - 인공지능이 인공적으로 지능을 늘리려면 지식을 늘려야 함 
  - 인공지능을 구현하는 머신러닝에 있어서 지식의 원천은 바로 데이터
  - 인공지능 구현에 빅데이터를 이용하여 그 정확도를 획기적으로 증가시켰고, 빅데이터 분석에 인공지능 기술을 도입하여 빅데이터의 활용성을 폭발적으로 높여줌 



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
얼마나 좋은 팀워크를 발휘하느냐에 달려있음 

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


## 문제 정의 
- 머신러닝을 통해 해결하고자 하는 문제를 정의해보자 
- 자신의 문제라고 생각해야 함 
- 인간의 오랜 습관을 고치는 것을 머신러닝의 도움을 받아보자. 
  - 손톱을 깨무는 습관이 있고, 이를 고치기 위해 머신러닝의 도움을 받아보자. 

  ![문제정의](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/4916/12034.png)

- 습관을 고치는 것은 쉽지 않음  
    - 습관은 의지를 이깁니다.
    - 의지는 환경을 이깁니다.
    - 환경은 습관을 이깁니다.
![문제정의](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/4916/12155.jpeg)


- 습관을 고치기 위해
  - 의지로 환경을 조정해서, 환경이 습관을 손봐주는 우회 전략을 구사해보자. 
  - 손톱을 깨물었을 때 알려주는 환경을 만들어보자 
  - 스마트폰으로 나를 촬영하여 손톱을 깨물었을 때 알려주는 기능을 만들어보자. 


![문제정의](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/4916/12163.jpeg)



- 스마트폰 카메라를 통해 촬영된 사진에서 
  - 손톱을 깨물고 있는지, 아닌지를 알려줄 수 있는 기능이 필요함 
  - 우선, 손톱을 깨물고 있는 사진과 깨물지 않고 있는 사진을 구분해서 컴퓨터를 학습시키자 
![](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/4916/12165.jpeg)

  - 이렇게 학습시켜놓은 컴퓨터를 이용해서, 나중에 보여준 적이 없는 사진을 컴퓨터에 보여주면 손톱을 깨물고 있는지 그렇지 않은지를 컴퓨터가 결정해줄 수 있을거야 

![](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/4916/12166.jpeg)


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
  - (최신 브라우저를 사용해주세요. 모바일 환경에서는 동작하지 않을 수 있습니다.)

![TM](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/4916/12087.jpeg)


  - Get Started로 들어가보자. 
    - Image, Audio, Pose Project
    - Image, Audio, Pose는 이 서비스를 이용해서 컴퓨터에게 학습시킬 수 있는 데이터들을 의미
    
![](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/4916/12088.jpeg)

  
- Image Project를 선택하여 들어가보자 
  - 이미지를 컴퓨터에게 학습시키는 기능이 모여있는 페이지
  - Class: 우선, Class는 교실이라는 뜻도 있지만, 여기서는 서로 연관된 사진들을 모아서 그룹핑한 것이라는 의미에서 ‘분류'로 해석

![](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/4916/12090.jpg)


- Class1에 손톱 이라고 작성하고, 
  - 웹캠으로 손톱을 뜯는 영상 촬영하여 데이터를 모음 (웹캠이 연결되어 있어야 함)
![](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/4916/12089.jpeg)
![](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/4916/12091.jpg)

  - 손톱 뜨는 영상을 모은 화면 
![](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/4916/12092.jpeg)


- Class2는 '정상' 이라고 작성하고, 
  - 손톱을 뜯지 않는 영상 모으기 
![](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/4916/12093.jpg)


- 데이터를 모았으면 컴퓨터를 학습시켜보자. 
  - Train model 버튼 누르기 
  - 기계에게 실제로 학습을 시키는 단계
  - 기계는 여러 사진을 보고 어떤 사진이 손톱 class에 속한 사진이고 정상 class에 속한 사진인지를 열심히 학습함 
![](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/4916/12094.jpeg)

- 학습이 끝났다면 Preview를 살펴보자. 
  - 카메라를 보면서 손톱을 깨물면, ‘손톱’의 수치가 높아질 것임 
  - 손톱을 깨물지 않으면 ‘정상’ 쪽의 수치가 높아질 것임 
  - 이 수치는 기계가 판단한 확률입니다.
  - 신기하게도 보여준 적이 없는 이미지를 만나도 그것이 손톱을 깨무는 모습인지 알아맞히는 것을 볼 수 있습니다.

![](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/4916/12098.jpg)

- 이 단계에서 중요한 것은 기계가 학습을 제대로 했는지 평가하는 것
  - 평가 결과 수치가 만족스럽지 않을 수 있음 
  - 시험으로 치면 불합격
  - 그럼 보다 많은 이미지를 추가하거나, 부정확한 이미지를 제거한 후에 다시 컴퓨터를 학습시킴 
  - 사람이 학습하듯이 기계를 학습시켜서 정확한 판단력을 갖게 한다는 점에서 이런 기술을 기계학습, 영어로 Machine Learning이라고 부름 

- 기계가 손톱을 깨무는지 구별하도록 학습했고, 이 학습결과를 파일로 다운로드할 수 있음 
![](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/4916/12099.jpeg)

- Export Model 버튼을 누르면 다운로드 받을 수 있는 여러가지 방법을 볼 수 있음 
  - Tensorflow.js 탭을 누르고,
  - Download 라디오 버튼을 누릅니다.
  - Download my model 버튼을 누르면
  - tm-my-image-model.zip 와 같은 이름의 파일을 다운로드 합니다.


- 이 파일의 압축을 풀어보면 3개의 파일이 있음 
  - metadata.json
  - model.json
  - weights.bin

![](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/4916/12100.jpeg)

- 위 세 파일이 기계가 학습한 **판단력** (**모델**)임 
  - 이 파일에 담겨있는 판단력이 머신러닝의 핵심입니다.
  - 이 파일만 있다면 이 세상의 모든 컴퓨터가 손톱과 정상을 구분할 수 있는 판단력을 갖게 됩니다.
  - 이 파일을 이용해서 놀라운 앱을 만들 수 있음 
  - 머신러닝에서는 판단력이라는 표현 대신 모델이라는 용어 사용 


## 마스크 얼굴 구별하는 기계학습 모델 학습하기 
- 마스크를 낀 얼굴과 마스크를 끼지 않은 얼굴을 구분하는 모델을 만들어보자. 
- 웹캠이 없는 환경에서는 이미 모아져있는 데이터를 활용하여 머신러닝 학습하기  


- 마스크 이미지에 대한 데이터는 다음 링크에서 받을 수 있음 
  - https://github.com/chandrikadeb7/Face-Mask-Detection
  - Mask detection 소스코드, 모델, 데이터 등을 github에 공개함 
  
<img width="750" alt="mask" src="https://user-images.githubusercontent.com/58820851/212538354-4c07069f-0395-4f49-9040-8f872aa2b5c0.PNG">

  - dataset 폴더 안에 with_mask, without_mask 라는 폴더에 마스크를 쓴 얼굴 사진, 마스크를 쓰지 않은 얼굴 사진이 들어 있음 
  - 소스코드와 데이터 등 다운로드받기 
    - 오른쪽 상단 초록색 Code 버튼 클릭 > Download zip 클릭 > 저장 위치 선택하면 zip파일로 다운로드 됨 
<img width="1073" alt="mask2" src="https://user-images.githubusercontent.com/58820851/212538442-5d914584-303b-48fe-9905-f912947d0672.PNG">

    - 다운로드받은 zip 파일을 압축풀어서 폴더내 데이터 확인하기 
      <img width="1198" alt="withoutmask" src="https://user-images.githubusercontent.com/58820851/212538531-5d579168-4440-4d9f-8343-b5cb759fa946.PNG">
      <img width="1199" alt="withmask" src="https://user-images.githubusercontent.com/58820851/212538532-4dccfbbb-026a-4381-8ddf-6b621fd53e59.PNG">



- Teachable Machine에서 다운받은 사진으로 학습하기 
  - https://teachablemachine.withgoogle.com/train
  - Get Started(시작하기) > 새 프로젝트 > 이미지 프로젝트 선택 > 표준이미지모델 선택
<img width="1067" alt="TM1" src="https://user-images.githubusercontent.com/58820851/212538666-124e2d5b-1516-4510-87da-b45d8d13ebae.PNG">



- 부류 이름 변경 
  - Class1 : with_mask 
  - Class2 : without_mask 

<img width="1061" alt="TM2" src="https://user-images.githubusercontent.com/58820851/212538741-f5e8b779-eaa8-43c0-8506-897d650b66c3.PNG">


- 학습 이미지 추가 
  - Class1 > 이미지 샘플 추가 > 업로드 선택 > 파일에서 이미지를 선택하거나 여기로 드래그 앤 드롭하세요. 선택 > Face-Mask-Detection-master\dataset\with_mask에 있는 이미지 모두 선택 (시간이 너무 오래걸리면 100장 정도만 선택)
  - Class2에도 동일한 방법으로 without_mask 이미지 추가 

<img width="1063" alt="TM3" src="https://user-images.githubusercontent.com/58820851/212538857-fd2836a1-e766-453e-9d23-cc90e81d8abd.PNG">

- 학습 데이터 업로드 된 화면 
<img width="1215" alt="TM4" src="https://user-images.githubusercontent.com/58820851/212538885-72b9427e-57ad-4048-9fca-0156143392c7.PNG">

- 학습하기 
  - 학습 > 모델 학습시키기 클릭 
  - 학습 데이터 준비 중... 이란 화면에서 시간이 소요됨 
  - 학습에 사용되는 데이터가 많을 수록 학습 준비, 학습에 상당한 시간이 소요되므로 창을 닫지 않고 완료될 때까지 기다려야 함 
  - 학습이 시작되면 학습중 이라는 메시지로 변함 

- 학습중인 화면 
  - 학습에도 시간이 소요됨 
  - 시간과 epoch (세대)가 표시됨 
  - 고급 
<img width="1213" alt="TM5" src="https://user-images.githubusercontent.com/58820851/212538970-a4e8f292-eff2-4ed5-9035-46df912ab3f5.PNG">

- 학습완료 화면 
<img width="1217" alt="TM6" src="https://user-images.githubusercontent.com/58820851/212539087-f671a734-807b-46e5-8d4b-6d1ff34dd23f.PNG">


- 미리보기 (Preview)
  - 학습된 모델을 이용하여 새로운 사진이 마스크를 썼는지 쓰지 않았는지 판단해보자. 
  - 새로운 사진 다운로드하기 
    - 좋아하는 연예인 또는 유명인 사진을 인터넷으로 검색하기 
    - 마스크 쓴 사진과 마스크쓰지 않은 사진 검색하여 내 PC로 다운로드하기 
  - 사용 > Webcam에서 파일로 변경 > 파일에서 이미지를 선택하거나 여기로 드래그 앤 드롭하세요. 클릭
  - 다운로드받은 사진 선택하여 모델로 예측해보기 

<img width="1210" alt="TM8" src="https://user-images.githubusercontent.com/58820851/212539261-357a38ef-ec20-48c4-a5b3-8d8cb327a728.PNG">
<img width="1213" alt="TM7" src="https://user-images.githubusercontent.com/58820851/212539263-0be9b576-1945-4d67-9cd8-8985712b3df3.PNG">


- 미리보기 > 모델 내보내기 
  - Tensorflow.js > 다운로드 > 모델 다운로드 클릭 > 폴더 지정 > 다운로드 



<!-- ## 머신러닝머신 

- 머신러닝머신 
  - http://ml-app.yah.ac/
  - Teachable model로 생성한 모델을 이용한 애플리케이션을 만들어주는 서비스 
  -  -->