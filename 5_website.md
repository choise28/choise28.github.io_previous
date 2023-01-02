# 웹 사이트 제작

## 특강 계획
- 웹 페이지 저작 및 웹 사이트 제작
- 난이도
    - 최대한 쉽게
    - 초보자 수준
- 주제 선정 사유
    - 기본기 교육만으로도 많은 성과를 거둘 수 있는 내용
    - 코딩의 기본 개념을 체험하기 적당한 분야
    - 웹 페이지 저작은 빅데이터과 교육 과정의 완성을 위한 기본 토대
- 요청하는 수강 태도
    - 해결하고 싶은 문제를 가진 <u>당사자</u>라고 가정하는 공감력
    - 자신이 (강의 노트를 공유하고 싶어하는) 선생님이라고 가정
    - 코딩은 문제 해결을 위한 것이고,  
    여러분은 문제의 **당사자**이자 **해결사**를 자임해야 함
    - 공부를 위한 공부가 아니라, 문제 해결을 위한 공부  
        <img alt="공부를 위한 공부" src="https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/course/3084/7519.png" width="45%">
        <img alt="문제를 해결하는 공부" src="https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/course/3084/7518.png" width="45%">
    - 코딩 공부와 친해지는 계기가 될 수업  
        <img alt="우리를 짓누르는 공부" src="https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/course/3084/7520.png" width="45%">
        <img alt="친해지는 공부" src="https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/course/3084/7522.png" width="45%">

## 기획
- 기획의 의미
    - 새로운 것을 만들려면, 사전에 준비와 계획이 필요함
    - 문제의 인식에서 출발  
    - 만들려고 하는 것을 상상해보고, 계획하는 과정  
      ![기획자](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7546.png)
- 지금부터 우리는 기획자!  
- 우리가 만들고 싶은 웹 화면  
  ![화면 기획](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7547.png)
    1. 화면 상단에 수업의 제목
    2. 화면 좌측에 수업의 목록(메뉴)
    3. 화면 우측에 선택한 내용(제목/동영상/본문)

## 코딩 (구경하기)
- 유용한 사이트
    - [github.com](https://github.com/)
    - [codepen.io](https://codepen.io//) 
    - [한글입숨](http://hangul.thefron.me/)
- 코딩과 실행
    - HTML 코드 입력과 렌더링의 차이
    - 코딩: 우리는 코드를 작성 
    - 실행: 컴퓨터는 코드를 실행
    - 코드는 원인, 화면은 결과
- 코드와 언어
    - 코드는 컴퓨터에게 지시하는 작업 명령서(지시서)
    - 원천 코드(source code)는 컴퓨터 언어로 사람이 작성함
    - 작성된 코드 덩어리를 애플리케이션, 앱, (응용) 프로그램, 정보 시스템 등으로 부름
    - 컴퓨터 언어도 사람의 언어처럼 매우 다양함
    - 유명한 컴퓨터 언어의 예: HTML, CSS, JavaScript, Python, Java, C, C++, PHP, SQL, ...  
    - [프로그래밍 언어 순위](https://pypl.github.io/PYPL.html)  
    
    ![컴퓨터 언어](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7551.png)

- HTML
    - 우리 수업의 주제
    - 웹 문서를 만드는 컴퓨터 언어
    - 웹 문서의 내용을 정의하는 역할
    - 웹 문서의 모양은 CSS 언어로 작성
    - 웹 문서의 동작은 JavaScript로 작성
- HTML은 배우기 쉬움  
    - 쉽지만, 중요함  
    - 웹 문서를 작성하는 도구
    - 여러분이 맨 처음 배우는 컴퓨터 언어

    <img src="https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7552.png" width="45%">
    <img src="https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7553.png" width="45%">  

- 공공재(public domain)
    - 무료로 쓸 수 있도록, 공개되어 있는
    - 세종대왕은 자신이 창제한 한글에 저작권을 설정하지 않았음  
    - 팀 버너스 리는 자신이 창제한 웹에 저작권을 설정하지 않았음
- 웹 세상에 첫 발을 들여놓은 여러분을 환영함    

## 코딩 준비
- 코드 편집을 위한 SW 종류
    - 윈도: 메모장, Atom
    - 맥: 텍스트 편집기
    - 리눅스: gedit, nano, vim  
    ![notepad](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7574.png)
- Atom 설치
    - 우리 수업에서는 [github.com](https://github.com/)에서 만든 Atom 편집기로 통일  
    - [https://atom.io/](https://atom.io/)에서 프로그램을 다운로드하고 설치  
      ![atom](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7575.png)
- Atom 실행 모습
    - 좌측은 프로젝트(폴더) 파일 목록
    - 우측은 선택한 파일의 편집 영역  
      ![아톰 실행 화면](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7576.png)
- 컴퓨터 화면 배치
    - 좌측: 웹 브라우저
    - 우측: Atom  
      ![화면 배치](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7578.png)
- 실습 폴더 생성  
    - 실습 파일을 저장할 (프로젝트) 폴더를 바탕화면에 WEB라는 이름으로 생성
    - Atom 좌측 화면에 WEB (프로젝트) 폴더가 표시되도록 지정  
      `메뉴 → File → Add project folder`  
      ![](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7583.png)
- 실습 파일 생성
    - Atom 좌측 화면에서,  
      WEB 폴더를 오른쪽 클릭해서 New File을 선택하고,  
      '1.html' 입력 후 엔터  
      ![Atom new file](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7584.png)
    - 방금 생성한 파일의 확장자는 html
        - MS 워드 파일의 확장자는 doc
        - PDF 파일의 확장자는 pdf
        - 웹 문서 파일의 확장자는 html
- 실습 파일 오픈
    - Atom에서 오픈하려면, Atom 왼쪽 화면에 보이는 `1.html` 파일을 클릭
    - 웹 브라우저에서 오픈하려면, 
        - 윈도우: Ctrl + O(알파벳)
        - 맥: Cmd + O(알파벳)  
      ![파일 열기](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7592.png)
    - 또는 윈도우 탐색기나 맥 파인더에서 `1.html` 파일을 더블클릭해도 웹 브라우저에서 오픈 가능함
- 실습 파일 편집
    - 편집 화면에 'hello web' 입력하고 저장(윈도우: Ctrl + S, 맥: Cmd + S)  
      ![atom에서 편집](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7588.png)
    - 웹 브라우저 새로고침  
      ![웹 브라우저 새로고침](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7590.png)
- 첫 웹 문서 제작을 축하!
    - 이제까지는 웹 문화의 **소비자**로 살아온 시간
    - 이제부터는 웹 문화의 **생산자**로 살아갈 시간
- 자주 묻는 질문
    - Atom 설치 실패: 다른 에디터를 써도 무방하고, 윈도우 메모장을 써도 가능함
    - Atom 자동 줄바꿈: 메뉴에서 `file -> settings -> editor -> Soft Wrap` 항목을 체크

## 기본 문법 - 태그
- 진짜 코딩 시작
    - 기획서 다시 보기  
    ![다시 기획서](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7594.jpeg)
    - "쪼개서 해결하기!" 작전으로, 붉은색 부분부터 작업
    - 문제와 해결의 당사자라는 감정 이입 신공을 발휘하면서
    - 상상력을 발휘해서, 나의 어떤 상황에 응용이 가능할까를 고민하면서 
- `html.html` 파일에 다음 내용을 입력/저장하고, 브라우저 새로고침  
    <p class="codepen" data-height="174" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="GRjYZPW" style="height: 174px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="start html.html">
    <span>See the Pen <a href="https://codepen.io/logistex/pen/GRjYZPW">
    start html.html</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
    on <a href="https://codepen.io">CodePen</a>.</span>
    </p>
    <script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>
- 축하!
- HTML 문서에서 
    - 공백을 반복해도 무효
    - 줄 바꿈을 해도 무효
    - 그럼 어떻게 하나요 ... ?
    - 해결 방법은 뒤에 공부할 예정
- 강조 표시
    - 'creating web pages'를 강조하려면, `<strong></strong>` 태그를 적용
    - 태그마다 역할이 지정되어 있다는 점을 인식해야 함
- 추가적 강조    
    - 'creating web pages'에서 'web'을 더 강조하려면, `<u></u>` 태그를 적용  
    <p class="codepen" data-height="169" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="vYXzxjq" style="height: 169px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="emphasize.html">
      <span>See the Pen <a href="https://codepen.io/logistex/pen/vYXzxjq">
      emphasize.html</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
      on <a href="https://codepen.io">CodePen</a>.</span>
    </p>
    <script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>    
- 코딩 내용을 반추
    - 태그(tag) 
        - 옷에 붙어 있는 태그
        - SNS에서 사용하는 해시 태그
        - HTML 태그  
        ![태그 위력](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7596.jpeg)
    - 쌍을 이루는 태그
        - 여는 태그
        - 닫는 태그  
    - 쌍이 없는 단독 태그도 있음
    - 태그는 중첩 가능함
- HTML 태그의 바다를 경험한 여러분에게 축하!  
  ![태그로 다이빙](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7597.jpeg)
- 한글이 깨지는 경우  
    - 윈도우는 기본적으로 "cp949"라는 인코딩 방식을 사용함
    - cmd 창을 열어서 `chcp` 명령을 실행하면 확인 가능함
    - 윈도우에서 제공되는 메모장으로 `html.html` 파일을 열어보면 한글이 깨짐
    - 윈도우 기본 코드 페이지를 "utf-8"로 변경하려면  
        - 일회성 변경: cmd 창에서 `chcp 65001` 명령을 실행하면 됨
        - 영구적 변경: 레지스트리를 수정해야 하는데,  
          [윈도10 CMD 코드 페이지 변경](https://extrememanual.net/12502) 참고
    - `<meta charset="utf-8">` 코드를 `1.html` 앞 부분에 추가
    - Atom에서 저장할 때 사용하는 인코딩 방식은 "utf-8"
    - 웹 브라우저에서 파일을 오픈할 때 사용할 인코딩 방식을 동일하게 지정
    - 요약
        - html 파일을 저장할 때 사용한 인코딩 방식과  
        - 웹 브라우저에게 알려줄 인코딩 방식을 일치시켜야 함 
    
## 혁명적 변화의 시대
- 시험에 대한 오해
    - "중요한 것은 어렵고, 쉬운 것은 사소하다?"
    - "쉬운 것은 시험에 잘 안나오니까!"
    - 시험의 역기능 혹은 부작용
- 시험의 본질
    - 얼마나 잘 습득했는지를 평가하려는 것이 본질
    - 상대평가 체제에서 순위 변별력을 담보하기 위한 본말의 전도
- 쉽지만, (쉽고 중요한) 기본에 충실해야!
    - 쉽지만 중요한 기본 개념이 실무 기술의 대부분을 차지함
    - 공부가 깊어질수록 점점 어려운 것을 배우게 되지만, 기초가 중요함  
    ![](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7825.jpeg)
- 지금가지 우리가 배운 것
    - HTML 태그 2 개
    - 태그를 배우기 전과 후의 여러분은 크게 달라졌음 
    - 너무 심한 과장일까?
    ![배움 전후](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7606.jpeg)    
- 과장이 아님!
    - 엄청 복잡한 HTML 문서를 해독하는 과정을 통하여 과장이 아니라는 점을 설명
    - 엄청 복잡한 HTML 문서를 획득
        - [https://www.w3.org/](https://www.w3.org/) 방문  
            ![w3c](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7608.jpeg)
        - W3C(The World Wide Web Consortium)라는 웹 표준화 기구의 홈페이지
        - W3C에서 HTML 문법의 표준을 결정함
        - W3C 웹 페이지를 오른쪽 마우스로 클릭하여 `페이지 소스보기(View Page Source)`  
          ![보이는 소스](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7610.png)
        - "모르는 내용이 많군요! 그래서 불편하죠."
- 복잡한 HTML 문서를 해독하는 과정
    - 위에서 `<h1>`으로 시작하는 코드를 살펴보면, 여전히 복잡...   
        <div class="colorscripter-code" style="color:#010101;font-family:Consolas, 'Liberation Mono', Menlo, Courier, monospace !important; position:relative !important;overflow:auto">
            <table class="colorscripter-code-table" style="margin:0;padding:0;border:none;background-color:#fafafa;border-radius:4px;" cellspacing="0" cellpadding="0">
                <tr>
                    <td style="width:5%;padding:6px;border-right:2px solid #e5e5e5">
                        <div style="margin:0;padding:0;word-break:normal;text-align:right;color:#666;font-family:Consolas, 'Liberation Mono', Menlo, Courier, monospace !important;line-height:130%">
                        <div style="line-height:130%">1</div><div style="line-height:130%">2</div><div style="line-height:130%">3</div><div style="line-height:130%">4</div><div style="line-height:130%">5</div><div style="line-height:130%">6</div></div></td>
                    <td style="width:95%;padding:6px 0;text-align:left"><div style="margin:0;padding:0;color:#010101;font-family:Consolas, 'Liberation Mono', Menlo, Courier, monospace !important;line-height:130%"><div style="padding:0 6px; white-space:pre; line-height:130%"><span style="color:#010101">&lt;</span><span style="color:#ff3399">h1</span>&nbsp;<span style="color:#0099cc">class</span>=<span style="color:#52be14">"logo"</span><span style="color:#0099cc"></span><span style="color:#010101">&gt;</span></div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#010101">&lt;</span><span style="color:#ff3399">a</span>&nbsp;<span style="color:#0099cc">tabindex</span>=<span style="color:#52be14">"2"</span><span style="color:#0099cc"></span>&nbsp;<span style="color:#0099cc">accesskey</span>=<span style="color:#52be14">"1"</span><span style="color:#0099cc"></span>&nbsp;<span style="color:#0099cc">href</span>=<span style="color:#52be14">"/"</span><span style="color:#0099cc"></span><span style="color:#010101">&gt;</span></div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#010101">&lt;</span><span style="color:#ff3399">img</span>&nbsp;<span style="color:#0099cc">src</span>=<span style="color:#52be14">"/2008/site/images/logo-w3c-mobile-lg"</span><span style="color:#0099cc"></span>&nbsp;<span style="color:#0099cc">width</span>=<span style="color:#52be14">"90"</span><span style="color:#0099cc"></span>&nbsp;<span style="color:#0099cc">height</span>=<span style="color:#52be14">"53"</span><span style="color:#0099cc"></span>&nbsp;<span style="color:#0099cc">alt</span>=<span style="color:#52be14">"W3C"</span><span style="color:#0099cc"></span>&nbsp;<span style="color:#0099cc">/</span><span style="color:#010101">&gt;</span></div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#010101">&lt;</span><span style="color:#010101">/</span><span style="color:#ff3399">a</span><span style="color:#010101">&gt;</span>&nbsp;</div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#010101">&lt;</span><span style="color:#ff3399">span</span>&nbsp;<span style="color:#0099cc">class</span>=<span style="color:#52be14">"alt-logo"</span><span style="color:#0099cc"></span><span style="color:#010101">&gt;</span>W3C<span style="color:#010101">&lt;</span><span style="color:#010101">/</span><span style="color:#ff3399">span</span><span style="color:#010101">&gt;</span>&nbsp;&nbsp;&nbsp;&nbsp;</div><div style="padding:0 6px; white-space:pre; line-height:130%"><span style="color:#010101">&lt;</span><span style="color:#010101">/</span><span style="color:#ff3399">h1</span><span style="color:#010101">&gt;</span></div></div><div style="text-align:right;margin-top:-13px;margin-right:5px;font-size:9px;font-style:italic"><a href="http://colorscripter.com/info#e" target="_blank" style="color:#e5e5e5text-decoration:none">Colored by Color Scripter</a></div></td>
                    <td style="width:5%;vertical-align:bottom;padding:0 2px 4px 0"><a href="http://colorscripter.com/info#e" target="_blank" style="text-decoration:none;color:white"><span style="font-size:9px;word-break:normal;background-color:#e5e5e5;color:white;border-radius:10px;padding:1px">cs</span></a></td></tr></table></div>
    - 이 코드에서 `<img ...>` 부분은 그림을 표시하는 태그인데, 이를 제거하면 ...
        <div class="colorscripter-code" style="width:100%;color:#010101;font-family:Consolas, 'Liberation Mono', Menlo, Courier, monospace !important; position:relative !important;overflow:auto"><table class="colorscripter-code-table" style="margin:0;padding:0;border:none;background-color:#fafafa;border-radius:4px;" cellspacing="0" cellpadding="0"><tr>
      <td style="width:5%;padding:6px;border-right:2px solid #e5e5e5"><div style="margin:0;padding:0;word-break:normal;text-align:right;color:#666;font-family:Consolas, 'Liberation Mono', Menlo, Courier, monospace !important;line-height:130%"><div style="line-height:130%">1</div><div style="line-height:130%">2</div><div style="line-height:130%">3</div><div style="line-height:130%">4</div><div style="line-height:130%">5</div></div></td>
      <td style="width:95%;padding:6px 0;text-align:left"><div style="margin:0;padding:0;color:#010101;font-family:Consolas, 'Liberation Mono', Menlo, Courier, monospace !important;line-height:130%"><div style="padding:0 6px; white-space:pre; line-height:130%"><span style="color:#010101">&lt;</span><span style="color:#ff3399">h1</span>&nbsp;<span style="color:#0099cc">class</span>=<span style="color:#52be14">"logo"</span><span style="color:#0099cc"></span><span style="color:#010101">&gt;</span></div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#010101">&lt;</span><span style="color:#ff3399">a</span>&nbsp;<span style="color:#0099cc">tabindex</span>=<span style="color:#52be14">"2"</span><span style="color:#0099cc"></span>&nbsp;<span style="color:#0099cc">accesskey</span>=<span style="color:#52be14">"1"</span><span style="color:#0099cc"></span>&nbsp;<span style="color:#0099cc">href</span>=<span style="color:#52be14">"/"</span><span style="color:#0099cc"></span><span style="color:#010101">&gt;</span></div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#010101">&lt;</span><span style="color:#010101">/</span><span style="color:#ff3399">a</span><span style="color:#010101">&gt;</span>&nbsp;</div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#010101">&lt;</span><span style="color:#ff3399">span</span>&nbsp;<span style="color:#0099cc">class</span>=<span style="color:#52be14">"alt-logo"</span><span style="color:#0099cc"></span><span style="color:#010101">&gt;</span>W3C<span style="color:#010101">&lt;</span><span style="color:#010101">/</span><span style="color:#ff3399">span</span><span style="color:#010101">&gt;</span>&nbsp;&nbsp;&nbsp;&nbsp;</div><div style="padding:0 6px; white-space:pre; line-height:130%"><span style="color:#010101">&lt;</span><span style="color:#010101">/</span><span style="color:#ff3399">h1</span><span style="color:#010101">&gt;</span></div></div><div style="text-align:right;margin-top:-13px;margin-right:5px;font-size:9px;font-style:italic"><a href="http://colorscripter.com/info#e" target="_blank" style="color:#e5e5e5text-decoration:none">Colored by Color Scripter</a></div></td>
      <td style="width:5%;vertical-align:bottom;padding:0 2px 4px 0"><a href="http://colorscripter.com/info#e" target="_blank" style="text-decoration:none;color:white"><span style="font-size:9px;word-break:normal;background-color:#e5e5e5;color:white;border-radius:10px;padding:1px">cs</span></a></td></tr></table></div>
    - 이 코드에서 `<a>...</a>` 부분은 링크를 연결하는 역할의 태그인데, 이를 제거하면 ...
        <div class="colorscripter-code" style="width:100%;color:#010101;font-family:Consolas, 'Liberation Mono', Menlo, Courier, monospace !important; position:relative !important;overflow:auto"><table class="colorscripter-code-table" style="margin:0;padding:0;border:none;background-color:#fafafa;border-radius:4px;" cellspacing="0" cellpadding="0"><tr>
      <td style="width:5%;padding:6px;border-right:2px solid #e5e5e5"><div style="margin:0;padding:0;word-break:normal;text-align:right;color:#666;font-family:Consolas, 'Liberation Mono', Menlo, Courier, monospace !important;line-height:130%"><div style="line-height:130%">1</div><div style="line-height:130%">2</div><div style="line-height:130%">3</div></div></td>
      <td style="width:95%;padding:6px 0;text-align:left"><div style="margin:0;padding:0;color:#010101;font-family:Consolas, 'Liberation Mono', Menlo, Courier, monospace !important;line-height:130%"><div style="padding:0 6px; white-space:pre; line-height:130%"><span style="color:#010101">&lt;</span><span style="color:#ff3399">h1</span>&nbsp;<span style="color:#0099cc">class</span>=<span style="color:#52be14">"logo"</span><span style="color:#0099cc"></span><span style="color:#010101">&gt;</span></div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#010101">&lt;</span><span style="color:#ff3399">span</span>&nbsp;<span style="color:#0099cc">class</span>=<span style="color:#52be14">"alt-logo"</span><span style="color:#0099cc"></span><span style="color:#010101">&gt;</span>W3C<span style="color:#010101">&lt;</span><span style="color:#010101">/</span><span style="color:#ff3399">span</span><span style="color:#010101">&gt;</span></div><div style="padding:0 6px; white-space:pre; line-height:130%"><span style="color:#010101">&lt;</span><span style="color:#010101">/</span><span style="color:#ff3399">h1</span><span style="color:#010101">&gt;</span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</div></div></td>
      <td style="vertical-align:bottom;padding:0 2px 4px 0"><a href="http://colorscripter.com/info#e" target="_blank" style="text-decoration:none;color:white"><span style="font-size:9px;word-break:normal;background-color:#e5e5e5;color:white;border-radius:10px;padding:1px">cs</span></a></td></tr></table></div>
    - 이 코드에서 `<span>...</span>` 부분은 줄바꿈 없이 어떤 효과를 연출하기 위한 태그인데, 이를 제거하면 ...
        <div class="colorscripter-code" style="color:#010101;font-family:Consolas, 'Liberation Mono', Menlo, Courier, monospace !important; position:relative !important;overflow:auto"><table class="colorscripter-code-table" style="margin:0;padding:0;border:none;background-color:#fafafa;border-radius:4px;" cellspacing="0" cellpadding="0"><tr>
      <td style="width:5%;padding:6px;border-right:2px solid #e5e5e5"><div style="margin:0;padding:0;word-break:normal;text-align:right;color:#666;font-family:Consolas, 'Liberation Mono', Menlo, Courier, monospace !important;line-height:130%"><div style="line-height:130%">1</div><div style="line-height:130%">2</div><div style="line-height:130%">3</div></div></td>
      <td style="width:95%;padding:6px 0;text-align:left"><div style="margin:0;padding:0;color:#010101;font-family:Consolas, 'Liberation Mono', Menlo, Courier, monospace !important;line-height:130%"><div style="padding:0 6px; white-space:pre; line-height:130%"><span style="color:#010101">&lt;</span><span style="color:#ff3399">h1</span>&nbsp;<span style="color:#0099cc">class</span>=<span style="color:#52be14">"logo"</span><span style="color:#0099cc"></span><span style="color:#010101">&gt;</span></div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;&nbsp;&nbsp;&nbsp;W3C&nbsp;&nbsp;&nbsp;&nbsp;</div><div style="padding:0 6px; white-space:pre; line-height:130%"><span style="color:#010101">&lt;</span><span style="color:#010101">/</span><span style="color:#ff3399">h1</span><span style="color:#010101">&gt;</span></div></div></td><td style="vertical-align:bottom;padding:0 2px 4px 0"><a href="http://colorscripter.com/info#e" target="_blank" style="text-decoration:none;color:white"><span style="font-size:9px;word-break:normal;background-color:#e5e5e5;color:white;border-radius:10px;padding:1px">cs</span></a></td></tr></table></div>
    - 이 코드에서 `class="logo"` 부분은 태그에 효과를 연출하기 위한 코드인데, 이를 제거하면 ...
        <div class="colorscripter-code" style="color:#010101;font-family:Consolas, 'Liberation Mono', Menlo, Courier, monospace !important; position:relative !important;overflow:auto"><table class="colorscripter-code-table" style="margin:0;padding:0;border:none;background-color:#fafafa;border-radius:4px;" cellspacing="0" cellpadding="0"><tr>
      <td style="width:5%;padding:6px;border-right:2px solid #e5e5e5"><div style="margin:0;padding:0;word-break:normal;text-align:right;color:#666;font-family:Consolas, 'Liberation Mono', Menlo, Courier, monospace !important;line-height:130%"><div style="line-height:130%">1</div><div style="line-height:130%">2</div><div style="line-height:130%">3</div></div></td>
      <td style="width:95%;padding:6px 0;text-align:left"><div style="margin:0;padding:0;color:#010101;font-family:Consolas, 'Liberation Mono', Menlo, Courier, monospace !important;line-height:130%"><div style="padding:0 6px; white-space:pre; line-height:130%"><span style="color:#010101">&lt;</span><span style="color:#ff3399">h1</span><span style="color:#010101">&gt;</span></div><div style="padding:0 6px; white-space:pre; line-height:130%">&nbsp;&nbsp;&nbsp;&nbsp;W3C&nbsp;&nbsp;&nbsp;&nbsp;</div><div style="padding:0 6px; white-space:pre; line-height:130%"><span style="color:#010101">&lt;</span><span style="color:#010101">/</span><span style="color:#ff3399">h1</span><span style="color:#010101">&gt;</span></div></div></td>
      <td style="vertical-align:bottom;padding:0 2px 4px 0"><a href="http://colorscripter.com/info#e" target="_blank" style="text-decoration:none;color:white"><span style="font-size:9px;word-break:normal;background-color:#e5e5e5;color:white;border-radius:10px;padding:1px">cs</span></a></td></tr></table></div>
    - 결국 다음과 같은 `<h1>` 태그만 남는다는 ...    
        <div class="colorscripter-code" style="width:100%;color:#010101;font-family:Consolas, 'Liberation Mono', Menlo, Courier, monospace !important; position:relative !important;overflow:auto"><table class="colorscripter-code-table" style="margin:0;padding:0;border:none;background-color:#fafafa;border-radius:4px;" cellspacing="0" cellpadding="0"><tr>
      <td style="width:5%;padding:6px;border-right:2px solid #e5e5e5"><div style="margin:0;padding:0;word-break:normal;text-align:right;color:#666;font-family:Consolas, 'Liberation Mono', Menlo, Courier, monospace !important;line-height:130%"><div style="line-height:130%">1</div></div></td>
      <td style="width:95%;padding:6px 0;text-align:left"><div style="margin:0;padding:0;color:#010101;font-family:Consolas, 'Liberation Mono', Menlo, Courier, monospace !important;line-height:130%"><div style="padding:0 6px; white-space:pre; line-height:130%"><span style="color:#010101">&lt;</span><span style="color:#ff3399">h1</span><span style="color:#010101">&gt;</span>W3C<span style="color:#010101">&lt;</span><span style="color:#010101">/</span><span style="color:#ff3399">h1</span><span style="color:#010101">&gt;</span></div></div></td>
      <td style="vertical-align:bottom;padding:0 2px 4px 0"><a href="http://colorscripter.com/info#e" target="_blank" style="text-decoration:none;color:white"><span style="font-size:9px;word-break:normal;background-color:#e5e5e5;color:white;border-radius:10px;padding:1px">cs</span></a></td></tr></table></div>
- `h1` 태그의 의미를 탐구
    - 이 코드는 무엇을 지시하는 걸까요?
        - 무엇을 지시하는지는 몰라도, 
        - `h1` 태그가 열리고, 닫혔다는 것은 알겠네!
        - `h1` 태그 내부에 'W3C'라는 단어가 표시되겠네!
        - 이런 짐작은 가능한 상태에 여러분은 도달했음
        - `h1` 태그가 어떤 역할을 하는지는 모름
        - 적어도, 무엇을 모르는지는 아는 상태가 되었음
    - 구글 검색에서 `HTML h1 tag`로 검색하면, `h1` 태그의 정체에 대해서는 순식간에 알아낼 수 있음
        - 엄청난 검색 결과가 순식간에 나올테지만 ...
        - 첫째 검색 결과인 [www.w3schools.com/tags/tag_hn.asp](https://www.w3schools.com/tags/tag_hn.asp) 링크로 가보면   
          ![w3schools](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7611.png)
        - 예제(Example)와 정의(Definition)를 볼 수 있음
        - 정의를 먼저 보는 것보다는, 예제를 먼저 보고나서, 정의를 이해하기를 권함  
          <p class="codepen" data-height="370" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="qBaMPWw" style="height: 370px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="qBaMPWw">
              <span>See the Pen <a href="https://codepen.io/logistex/pen/qBaMPWw">
              qBaMPWw</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
              on <a href="https://codepen.io">CodePen</a>.</span>
          </p>
          <script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>
    - 추론
        - `h` 뒤에 숫자가 나옴
        - 큰 글씨부터 작은 글씨가 나열됨
        - `h` 뒤의 숫자가 커질수록, 글씨는 작아짐
        - 여기까지 추론이 되었다면, 정의는 뭘까?
    - 정의  
      > The `<h1>` to `<h6>` tags are used to define HTML headings.  
      > `<h1>` defines the most important heading. `<h6>` defines the least important heading.

      > `<h1>`부터 `<h6>`까지의 태그는 HTML 문서에서 제목을 정의하는 데 사용합니다.  
      > `<h1>`은 가장 중요한 제목을 정의합니다. `<h6>`은 가장 덜 중요한 제목을 정의합니다.
    - 결론 
        - `h` 태그는 HTML 문서에서 제목을 지정하는 태그
        - `h1` 태그는 제일 큰 제목을 지정하는 태그
        - 이런 식으로 구글링을 통해 스스로 학습이 가능함
- 응용
    - 우리가 만들었던 HTML 문서에 제목을 추가
    - 웹 문서 맨 앞에 `<h1>HTML</h1>` 코드 추가  

<p class="codepen" data-height="241" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="xxEyEZX" style="height: 241px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="with h1.html">
  <span>See the Pen <a href="https://codepen.io/logistex/pen/xxEyEZX">
  with h1.html</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>


- "태그를 배우기 전과 후가 달라졌다!"는 말은 과장이 아니죠?
    - 놀라운 점은 웹을 통해서 "원하는 정보에 쉽게 접근할 수 있다!"는 점
    - `h1` 태그를 도서관에 가서 찾아봐야 했던 시절도 있었음  
      ![도서관 다녀 오기](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7616.jpeg)
    - 이런 시절엔, 도서관에서 알아낸 결과를 머리(가방) 속에 넣었어야 했다는 ...  
      ![머리 속에 저장](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7615.jpeg)
    - 요즘엔, 검색 방법을 머리 속에 넣어두면 해결된다는 ...
      ![쉽게 검색 가능한 세상](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7620.jpeg)
    - 과거엔 머리 속에 든 지식이 중요했지만,  
      현재는 어떻게 찾으면 되는지를 하는 것이 중요하고,   
      사실 더욱 중요한 것은 *무엇을 모르는지를 아는 것*
- 혁명적 출발을 축하!  
  ![시작이 가속되고 있음](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7622.jpeg)
    
## 통계에 근거한 학습
- HTML에는 150 종이 넘는 태그가 존재함
- 파레토 법칙 또는 80-20 법칙  
    - *"상위 20%가 전체의 80%를 점유한다."*
    - (2030년에는) 상위 1%의 부자가 전체 부의 64%를 독식할 것으로 전망  
      출처: [세계 상위 1% 부자, 2030년에는 세계 부 64% 독식](https://www.yna.co.kr/view/AKR20180408040000009)
    - 자주 사용되는 태그 30개가 HTML 태그 사용량의 80%를 차지
- 태그 사용 통계
    - [advancedwebranking.com](https://advancedwebranking.com/html/) 
    - 32 종 태그로 작성된 웹 문서가 가장 많음   
      ![webranking_1](https://user-images.githubusercontent.com/10287629/104163272-7f448c80-5439-11eb-907e-4fee16d23b05.png)
    - 웹 문서에서 특정 태그의 사용 빈도
        - 1등인 `html`과 `head` 태그는 모든(100%) 웹 문서에 등장
        - 4등인 `title` 태그는 97.9%의 웹 문서에 등장 (`title` 태그가 누락된 웹 문서도 2.1%나 됨)
        - 13등인 `li`와 `p` 태그는 80.8%의 웹 문서에 등장
        - ...  
        - 19등인 `h1` 태그는 61.9%의 웹 문서에 등장
        - 27등인 `strong` 태그는 45.1%의 웹 문서에 등장
        - 150 종이 넘는 태그 중에서 30등 이내라면 자주 쓰이는 태그인 셈
        ![webranking_2](https://user-images.githubusercontent.com/10287629/104163268-7e135f80-5439-11eb-810c-075fc226fa81.png)
- 쉽고 중요한 태그 30여개만 익혀도 웹 문서 작성이 충분함
    - 기본 태그를 활용하다가,  
      "이런 태그가 있으면 편리하지 않을까?"라는 생각을 ...
    - 내가 고민스러운 문제라면, 이미 선배들이 해결했으리라는 믿음
    - 고민스러운 문제인데, 선배들의 해결 사례가 없다면 ... *"대박!"*

## 줄바꿈
- 배울 내용
    - 인기있는 태그 두 종
    - CSS
- `br` 태그 예제 
    - 좌측 코드에는 단락 구분을 위한 줄바꿈을 적용하였으나, 
    - 우측 실행 결과에는 줄바꿈이 동작하지 않음
    <p class="codepen" data-height="526" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="oNzPRRx" style="height: 526px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="no new line.html">
      <span>See the Pen <a href="https://codepen.io/logistex/pen/oNzPRRx">
      no new line.html</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
      on <a href="https://codepen.io">CodePen</a>.</span>
    </p>
    <script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>    
    
    - 줄바꿈 태그가 별도로 존재함  
    - 구글에서 `html new line tag`로 검색  
    - HTML `br` 태그  

    <p class="codepen" data-height="565" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="yLaxdBZ" style="height: 565px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="with br tag.html">
      <span>See the Pen <a href="https://codepen.io/logistex/pen/yLaxdBZ">
      with br tag.html</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
      on <a href="https://codepen.io">CodePen</a>.</span>
    </p>
    <script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>
    
    - `<br>` 태그는 단독 태그라서 `<br />`로 쓰기도 함
    - `<br>` 태그는 내용을 감싸는 태그가 아니라, 해당 위치에서 줄바꿈하라는 의미
    - `<br>` 태그는 여는 태그와 닫는 태그가 쌍으로 구성되지 않고, 단독으로 쓰임
    - 단독 태그라는 의미를 분명하게 표시하기 위하여, `<br />`로 쓰기도 함
    
- `p` 태그 예제    
    - 단락(paragraph) 표현을 위한 전용 태그
    - 구글에서 `html paragraph tag`로 검색
    - `<p> ... </p>` 태그  
    <p class="codepen" data-height="582" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="qBaMzON" style="height: 582px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="p tag">
      <span>See the Pen <a href="https://codepen.io/logistex/pen/qBaMzON">
      p tag</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
      on <a href="https://codepen.io">CodePen</a>.</span>
    </p>
    <script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>    
- 단락인 듯, 단락 아닌, 단락 같은 `br` 태그
    - `br` 태그 예제의 결과와 `p` 태그 예제의 결과는   
      사람에게는 동일한 모습처럼 보임
    - 검색 엔진에게는 전혀 다른 실체로 인식됨
        - `br` 태그는 단락과는 전혀 무관함
        - `p` 태그를 써야 단락이라는 실체로 인정됨
    - 의미에 부합하는 태그를 써야 바람직함
    
- `P` 태그의 불편함, `br` 태그의 편리함
    - `br` 태그를 쓰면 단락과 단락 사이의 여백 크기를 `br` 태그를 반복하여 조절 가능함
    - `P` 태그에서 단락과 단락 사이의 여백 크기는 정해져 있음
    - `p` 태그를 쓰되 단락과 단락 사이의 여백을 더 크게 하려면,  
      CSS 언어를 동원하면 됨
    
- CSS 언어를 활용하여 단락 간 여백을 조정하는 예제 
    - p 태그에 `style="margin-top:45px;"`라는 CSS 코드를 추가  
    - p 태그에 여백(margin)을 상부(top)에 45 픽셀(px)만큼 주는 모양새(style)라는 의미
        ```html
        <p style="margin-top:45px;">
        ```  
    <p class="codepen" data-height="598" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="YzGOoZx" style="height: 598px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="styling with CSS">
      <span>See the Pen <a href="https://codepen.io/logistex/pen/YzGOoZx">
      styling with CSS</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
      on <a href="https://codepen.io">CodePen</a>.</span>
    </p>
    <script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>
    
- 중요한 것은  
    - `br` 태그보다 `p` 태그가 좋다는 점을 이해하는 것 
    - 그 이유를 이해하는 것
    - 의미에 맞는 태그를 사용하라!
    - `p` 태그를 써서 단락의 경계를 명확하게 지정하되
    - CSS 스타일을 지정하여 모양을 멋지게 할 수 있다는 점
    
- 웹 문서 작성 도구 3 종
    - HTML: 문서의 내용 구조(? ... !)
    - CSS: 문서의 외관(스타일) 디자인
    - JavaScript: 문서의 동적 동작(기능, 콘텐츠가 아닌 행위) 
    
- 요약
    - 84%의 빈도로 등장하는 `p` 태그
    - 70%의 빈도로 등장하는 `br` 태그
    - 웹 문서의 디자인을 책임지는 CSS
## 학이불사...

![학이불사 이미지](haki.jpg)


## HTML이 중요한 이유
- 기초가 중요한 이유
    - 응용으로 가는 토대
    - 기초만으로도 할 수 있는 다양한 작업
- 웹 문서에서 제목을 만드는 두 방법  
    - [opentutorials.org](https://opentutorials.org/module/5316/edit) 구경  
        [![two title](https://user-images.githubusercontent.com/10287629/104263825-b1073300-54cd-11eb-85d3-3b1bf7b5752b.png)](https://opentutorials.org/module/5316/29936/edit)
    - 일반인: (`스타일`이 `본문`인 상태에서) 글자 크기를 22로 키우고, 진하게 지정  
        ![일반인](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7638.png)
    - 전문가: `스타일`을 적당한 크기의 `제목`으로 지정  
        ![전문가](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7640.png)
    - 배우기 전까지는 
        - `스타일`이 눈에 보이지 않았을 것
        - 모르는 것을 무시하는 우리 뇌의 배신
        - 공부를 하면 보이지 않던 것이 보이기 시작함
        - 공부를 하면 들리지 않던 것이 들리기 시작함
    - `소스` 단추를 눌러보기  
        ![](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7642.png)
    - 일반인의 코드  
        ```html
        <strong><span style="font-size:22px;">coding</span></strong>
        ```
    - 전문가의 코드  
        ```html
        <h3>coding</h3>
        ```
- 검색 엔진 입장에서 두 코드의 차이
    - 일반인 코드의 'coding'은 검색 엔진에게 제목이 아님
    - 전문가 코드의 'coding'은 검색 엔진에게 제목으로 인식됨
    - 두 사람이 10년 동안 2,000 개 웹 문서를 만들었다고 가정하면,  
      일반인의 웹 문서는 검색 엔진에서 처리되지 않고 무시됨

- HTML의 중요성 
    - 검색 엔진 친화적인 HTML을 써야 비즈니스가 잘 됨
    - 접근성을 보장하기 위해서도 용도에 맞는 HTML 태그를 써야 함
    - 결론은 용도에 맞는 HTML 태그를 써야 의미론적 유용성이 보장됨

## 태그의 속성과 img

- 계획 
    - 지금까지 HTML 문법 중에서 태그를 공부하였음  
      ![](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7660.png)
    - 이제부터 HTML 문법 중에서 **속성(attribute)**을 공부할 예정  
    - 이미지를 처리하는 `img` 태그도 공부할 예정
- 이미지(image)
    - 글씨만 포함된 웹 문서는 따분함
    - 이미지가 포함된 웹 문서가 필요함
    - 초창기 웹에는 문서에 그림을 넣는 방법이 없었음
    - 처음으로 웹 페이지에 그림이 등장했을 때, ...
- `img` 태그
    - `img` 태그를 썼지만 그림은 안 보이네...  
        <p class="codepen" data-height="446" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="ZEpqEpg" style="height: 446px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="not shown image.html">
          <span>See the Pen <a href="https://codepen.io/logistex/pen/ZEpqEpg">
          not shown image.html</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
          on <a href="https://codepen.io">CodePen</a>.</span>
        </p>
        <script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>

    - 어떤 그림을 표시해야 하는지 지정하지 않았음
        - `<img>?</img>`처럼 쓸 수 있을까요?
        - `?` 자리에 그림을 넣을 수 있을까요?
        - `img` 태그에 표시할 그림을 지정할 문법적 장치가 필요함
    - `img` 태그 내부에 표시할 그림을 지정하는 *속성*이라는 장치를 도입  
        - 코드  
            ```html
            <img src="https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7648.png">
            ```
        - 위 코드에서   
            `"https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7648.png"` 부분이  
            속성값  
        - 속성값  
            [https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7648.png](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7648.png)은  
            이미지(가 저장된 웹) 주소
        - 이 주소를 웹 브라우저 주소 창에 입력하면?
        - `속성="속성값"` 문법 형식  
            <p class="codepen" data-height="489" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="poExoem" style="height: 489px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="shown image ">
              <span>See the Pen <a href="https://codepen.io/logistex/pen/poExoem">
              shown image </a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
              on <a href="https://codepen.io">CodePen</a>.</span>
            </p>
            <script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>

    - `src` 속성으로 웹에 존재하는 이미지를 내 문서에 표시했음
        - 웹 문서에 이미지를 표시하려면,  
          이미지 파일 자체가 웹 주소를 통해 접근 가능해야 함
        - 내 컴퓨터에 존재하는 이미지 파일을 내 HTML 문서에 표시할 수 있지만,  
          막상 해당 HTML 문서가 웹에 배포되어도,  
          이미지 파일이 웹을 통해 접근 가능한 경우가 아니라면,  
          해당 HTML 문서에 포함된 이미지는 보이지 않을 것임
- 로컬/원격 이미지
    - 웹에 공개되어 있는 원격 이미지를 내 웹 문서에 표시  
        ```html
        <img src="https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7648.png">
        ```        
    - 내 컴에 저장되어 있는 로컬 이미지를 내 웹 문서에 표시  
        ```html
        <img src=".\photo-1610146140168-eb3b4219a80f.jpg">
        ```        

- 웹에 공개된 이미지를 활용하는 방법
    - 구글에서 `public domain image`로 검색
    - [unsplash.com](https://unsplash.com/)도 저작권 없는 사진을 제공하는 웹 사이트 중의 하나
    - 원하는 사진을 선택하고, `이미지를 다른 이름으로 저장` 메뉴를 써서 내 컴으로 다운로드
    - 작성 중인 웹 문서와 같은 폴더로 잘라내서 붙여넣은 후
    - `img` 코드를 활용  
    <img src="./photo-1610146140168-eb3b4219a80f.jpg">
    - 이 그림을 codepen.io 사이트에 입력했던 HTML 문서에서 보여주고 싶다면?
        - 웹에서 접근 가능한 이미지 파일의 주소를 사용해야 함
        - 웹에서 접근 가능한 곳에 이미지 파일을 올려야 함
        - 예를 들면 github 사이트를 활용하면 됨 

- 이미지 크기 조절
    - 이미지 주소를 지정하는 `src` 속성이 존재한다면, ...
    - 이미지 크기를 지정하는 속성도 있을테지 ...
    - 구글에서 `html img size attribute` 검색
        ```html
        <img width="30%" src="./photo-1610146140168-eb3b4219a80f.jpg">
        ```        
      <img width="30%" src="./photo-1610146140168-eb3b4219a80f.jpg">
    
- 높은 곳까지 올라온 여러분에게 박수를!
    ![](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7662.png)
    
## 목록 태그의 부모-자식 관계
- 태그 간의 부모(parent)-자식(child) 관계
  ![](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7679.jpeg)  
- 가상적 예제    
  실제로 존재하는 태그는 아니지만,  부모 코드 영역에 포함된 자식 코드  
    ```html
    <parent>
        <child></child>
    </parent>
    ```        
- 실제적 예제  
    ```html
    <p>
        <a href="https://logistex.github.io/smart_IT/">신입생을 위한 신교수 특강</a>
    </p>
    ```        
    - `p` 태그 내부에 포함된 `a` 태그
    - 여기서 `a` 태그는 하이퍼 링크 역할
- 상황에 따라 가변적인 태그 간의 관계        
    - `a` 태그가 항상 `p` 태그의 자식이어야 하는 것은 아님
    - `p` 태그가 항상 `a` 태그의 부모이어야 하는 것은 아님
    - 태그 간의 부모-자식 관계는 상황에 따라 달라짐
- 고정적 부모-자식 관계인 태그도 존재함

- 기획서  
    - 기획서에서 붉은색 영역
    - 웹 사이트의 메뉴 목록
    ![](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7677.png)
    
- 목록인 듯, 목록 아닌, 목록 같은 너...  
    - 목록처럼 보이지만, 실제로는 목록이 아님
    - HTML에서 목록(list)을 위해 준비해 둔 태그를 써야 함  
    <p class="codepen" data-height="265" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="MWjPYMO" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="no list">
      <span>See the Pen <a href="https://codepen.io/logistex/pen/MWjPYMO">
      no list</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
      on <a href="https://codepen.io">CodePen</a>.</span>
    </p>
    <script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script><br><br>  
    
- 올바른 목록은 전용 태그를 써서 작성해야 함  
- `li` 태그로 작성한 수업 목록   
    <p class="codepen" data-height="257" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="poExJMQ" style="height: 257px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="list.html">
      <span>See the Pen <a href="https://codepen.io/logistex/pen/poExJMQ">
      list.html</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
      on <a href="https://codepen.io">CodePen</a>.</span>
    </p>
    <script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script><br><br>  

- `li` 태그로 작성한 과일 목록 
        - 수업 목록과 과일 목록의 구분이 어려움
        - 목록 간의 구분이 필요함
        - 이 항목은 수업 목록이고, 이 항목은 과일 목록이라는 식으로  
        - 부모 태그 `ul`을 써서 자식 항목을 소속시키는 방식  
    <p class="codepen" data-height="265" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="eYdPLae" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="fruits list.html">
      <span>See the Pen <a href="https://codepen.io/logistex/pen/eYdPLae">
      fruits list.html</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
      on <a href="https://codepen.io">CodePen</a>.</span>
    </p>
    <script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script><br><br>    

- `ul` 태그를 사용하여 부모-자식 관계를 설정한 목록
    - 부모 `ul` 태그 내부에 자식 `li` 태그 항목을 두는 방식
    - 수업 `ul` 태그와 과일 `ul` 태그 사이에 빈 줄이 없어도 웹 화면에서 빈 줄이 표시됨
    - 수업 `ul` 태그와 과일 `ul` 태그 사이에 빈 줄을 두는 방식이 코드의 가독성을 높여줌  
    <p class="codepen" data-height="327" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="GRjYYKK" style="height: 327px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="ul li.html">
      <span>See the Pen <a href="https://codepen.io/logistex/pen/GRjYYKK">
      ul li.html</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
      on <a href="https://codepen.io">CodePen</a>.</span>
    </p>
    <script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script><br><br>    

- `li` 태그는 `ul` 부모 태그에 고정적으로 포함되는 방식으로 사용함
    - 상황에 따라서 부모-자식 관계를 자유롭게 맺는 태그가 아니라
    - 고정적으로 부모-자식 관계를 필수적으로 맺는 태그에 해당함

- 그런데, 수업의 목록 항목 개수가 매우 많다면?
    - 모든 항목의 번호를 사람이 일일이 지정해야 할까?
    - 자동적으로 번호가 지정된다면 편리하지 않을까?  
    - 아래 코드에서 과일 목록 코드에는 번호를 따로 지정하지 않았지만,  
      자동적으로 번호가 부여되어 표시되었음  
    <p class="codepen" data-height="265" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="wvzYYKW" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="ol.html">
      <span>See the Pen <a href="https://codepen.io/logistex/pen/wvzYYKW">
      ol.html</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
      on <a href="https://codepen.io">CodePen</a>.</span>
    </p>
    <script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script><br><br>

- 요약
    - 목록과 관련한 태그 세 개를 공부했음
    - 목록 항목을 정의하는 `li` 태그

- 최종적인 코드
    - 과일 목록은 파일에서 제거
    - 수업 목록 `ol` 태그로 변경하여 남긴 코드  
    <p class="codepen" data-height="265" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="LYRggbv" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="ol final.html">
      <span>See the Pen <a href="https://codepen.io/logistex/pen/LYRggbv">
      ol final.html</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
      on <a href="https://codepen.io">CodePen</a>.</span>
    </p>
    <script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script><br><br>

## 문서 구조와 수퍼 스타들
- 우리는 이미 HTML 문법 공부를 완료했음
    - HTML 문장 만드는 방법, 즉 HTML 문법 공부를 완료했음
    - HTML 문법에 더 복잡한 규칙은 없음  
    ![HTML 문법 공부를 완료](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7668.png)

- 웹 문서의 구조
    - 문장이 모여서 페이지를 구성함
    - 페이지가 모여서 책을 구성함
    - 책에는 표지가 있어야 하고,  
      표지에는 제목, 출판 일자와 저자 등이 표기되어야 함  
    ![](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7669.png)  
      
- 웹 문서의 구조를 만드는 방법
    - 정보를 정리정돈하기 위한 체계, 즉 구조가 필요함
    - HTML 태그 중에서 가장 많이 사용되는 수퍼스타 태그들도 공부할 예정  
    ![](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7664.png)

- 우리가 만든 웹 페이지와 다른 웹 페이지를 비교  
    - 다른 웹 페이지는 탭에 제목이 잘 정리되어 표시되었음
    - 우리 웹 페이지는 탭에 파일 경로가 표시되었음  
    - 구글에서 `html title` 검색
    ![](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7665.png)

- `title` 태그 활용
    ```html
    <title>WEB1 - html</title>
    ``` 
    - `title` 태그는 검색 엔진이 웹 페이지를 분석할 때, 중요하게 취급하는 태그
    - 모든 웹 문서에 반드시 포함되어야 할 중요한 태그
    <p class="codepen" data-height="265" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="XWjxxYo" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="title.html">
      <span>See the Pen <a href="https://codepen.io/logistex/pen/XWjxxYo">
      title.html</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
      on <a href="https://codepen.io">CodePen</a>.</span>
    </p>
    <script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script><br><br>    

- 웹 문서의 인코딩 방식을 브라우저에게 알리는 태그
    - 인코딩: 문서에 포함된 문자를 암호화하는 방식에는 여러 종류가 있지만,  
      최근에는 `UTF-8` 방식이 표준임 
    - 웹 문서 작성할 때 사용한 인코딩 방식과  
      웹 브라우저가 해석할 때 사용하는 인코딩 방식이  
      서로 다르면 웹 브라우저에서 글자가 깨져서 보임  
      ![](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7666.png)
    
    - 웹 문서를 작성할 때 사용한 인코딩 방식이 'UTF-8'임을 확인  
      ![](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7667.png)
      
    - 웹 브라우저에게 웹 문서의 인코딩 방식이 `UTF-8`임을 신고  
        ```html
        <meta charset="utf-8">
        ```
        <p class="codepen" data-height="241" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="jOMeedz" style="height: 241px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="charset.html">
          <span>See the Pen <a href="https://codepen.io/logistex/pen/jOMeedz">
          charset.html</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
          on <a href="https://codepen.io">CodePen</a>.</span>
        </p>
        <script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script><br><br>       
    
- `title`과 `meta` 태그의 공통점  
    ```html
        <title>WEB1 - html</title>
        <meta charset="utf-8">
    ```
    - 두 태그는 본문이 아님
    - HTML을 만든 사람들은  
      본문과 본문을 설명하는 정보를 각기 다른 태그로 분리해서  
      정리정돈하는 것이 바람직하다고 생각했음
      
- 문서의 구조를 처리하는 태그
    - 본문을 가두는 `body` 태그
    - 본문을 설명하는 `head` 태그  
    <p class="codepen" data-height="265" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="ExgddqB" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="head body.html">
      <span>See the Pen <a href="https://codepen.io/logistex/pen/ExgddqB">
      head body.html</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
      on <a href="https://codepen.io">CodePen</a>.</span>
    </p>
    <script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script><br><br>       

- `!doctype` 및 `html` 태그    
    - HTML 문서임을 표시하는 `!doctype html`  
        - 문서 유형을 표시하는 태그
        - 유일하게 '!'로 시작하는 태그
        - 문서의 맨 앞에 위치시킴
        - 닫는 태그 없이 단독으로 사용
    - 전체 문서를 가두는 `html` 태그
        - `html` 태그의 자식 태그는 `head`와 `body` 태그
        - `html` 태그는 여는 태그와 닫는 태그로 구성됨

- 결론적으로 웹 문서의 완전한 구조는 다음과 같음    
    ```html
    <!doctype html>
    <html> 
        <head>
            ...
        </head>
        <body>
            ...
        </body>
    </html>
    ```   
    <p class="codepen" data-height="265" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="RwGevea" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="doctype html.html">
      <span>See the Pen <a href="https://codepen.io/logistex/pen/RwGevea">
      doctype html.html</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
      on <a href="https://codepen.io">CodePen</a>.</span>
    </p>
    <script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script><br><br>       
    
- 전 세계의 모든 웹 문서가 공통적으로 준수하는 표준 구조를 공부했음
    ```html
    <!doctype html>
    <html> 
        <head>
            <title>...</title>
            <meta charset="utf-8">
            ...
        </head>
        <body>
            ...
        </body>
    </html>
    ```   
    ![웹 문서 구조](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7671.png)

## Emmet
- 맛 보기
    - !+[tab]
    - p+[tab]
    - li*n+[tab]
    - li>a*20+[tab]
    - (li>a)*20+[tab]
    - child: >
    - sybling: + 
- 설치  
    - atom에서 `File > Settings > Install`에서  
    - 'emmet' 입력하고 `Package` 검색한 후,  
    - `Install`

## HTML 태그의 제왕
![HTML 태그의 제왕](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7683.jpeg)
- 제왕이라 할만한 태그
    - 모든 웹 항해의 연결 수단
    - 검색 엔진의 존재 근거
    - 도시의 길, 인체의 혈관  
      ![도시의 길](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7686.jpeg)
    - 전 세계 웹 문서가 고립을 면하는 이유
    - 우리가 하루에 백번도 넘게 사용하는 태그 
    - 웹을 웹답게 만드는 가장 중요한 태그
    - 클릭하면 순식간에 연결  
      ![클릭하면 연결](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7688.jpeg)
    - "HTML"의 "HT" = "HyperText"  
      ![HyperText](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7689.jpeg)
    - 이 태그의 이름은 "anchor(닻)"에서 따온 `a`
    - 정보의 바다에 정박한다는 시적인 표현  
      ![anchor](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7690.jpeg)
    - 이 태그를 우리는 **링크(link, 연결)** 태그라고 부름
    - HTML 공식 문서에 대한 링크는 [https://html.spec.whatwg.org/](https://html.spec.whatwg.org/)이고,  
      `a` 태그에 대한 링크는 [https://html.spec.whatwg.org/#the-a-element](https://html.spec.whatwg.org/#the-a-element)
    - 구글에서 `html a tag` 검색
    
- 링크 태그 적용
    - 아래 코드에서 링크 태그가 적용된 부분에 주목
    - `<a>...</a>` 태그를 쓰면, `...`으로 표시된 문구에 링크가 걸림
    - `href` 속성은  **H**yperText **Ref**erence의 약자
    - `target="_blank`는 링크를 클릭했을 때,  
      새 창에서 페이지가 열리게 하는 속성
    - `title` 속성은 이 링크가 어떤 내용을 담고 있는지를  
      툴팁으로 보여주는 기능
        <p class="codepen" data-height="265" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="KKgGEVG" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="link tag.html">
          <span>See the Pen <a href="https://codepen.io/logistex/pen/KKgGEVG">
          link tag.html</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
          on <a href="https://codepen.io">CodePen</a>.</span>
        </p>
        <script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>    
    
- 링크를 통한 정보 탐험
    - 지식의 대중화, 학문의 민주화를 열어준 새로운 세상
    - 링크가 우리를 어디로 인도할까요?
    - 관광만 하지 말고, 여행을 하세요!
    - 클릭 가는데로 가다보면 길을 잃고 헤멜 수도 있어요.

## 웹 사이트 1차 완성 (내용 및 구조)
- 웹 문서와 웹 사이트
    - 지금까지 웹 문서(페이지) 저작 방법을 배웠음  
      ![웹 문서 저작](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/8130.png)
    - 링크로 문서와 문서를 연결하는 방법도 배웠음  
      ![링크 연결](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7707.jpeg)
    - 문서를 모아서 제본하면 책이 완성되듯,  
      웹 문서를 링크로 모으면 웹 사이트가 완성됨  
      ![웹 문서 연결](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7709.jpeg)

- 우리의 웹 사이트는 모두 4 개의 웹 문서로 구성됨 
    - `index.html`  
        웹 3대 기술을 총괄하는 "WEB" 소개 문서
    - `1_html.html`  
        첫번째 웹 기술로서 "HTML" 소개 문서
    - `2_css.html`  
        두번째 웹 기술로서 "CSS" 소개 문서
    - `3_javascript.html`  
        세번째 웹 기술로서 "JavaScript" 소개 문서

- 웹 사이트 작성 순서
    - 웹 사이트 전체의 제목을 "WEB"으로 작성  
      ![전체 제목 WEB](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7701.png)
    - 링크 설계   
      ![링크 설계](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7702.png)
    - 완성된 `index.html`   
        <p class="codepen" data-height="401" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="MWjPxGN" style="height: 401px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="index.html">
          <span>See the Pen <a href="https://codepen.io/logistex/pen/MWjPxGN">
          index.html</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
          on <a href="https://codepen.io">CodePen</a>.</span>
        </p>
        <script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script><br><br>
        
    - 완성된 `1_html.html`  
        <p class="codepen" data-height="367" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="XWjxGym" style="height: 367px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="1_html.html">
          <span>See the Pen <a href="https://codepen.io/logistex/pen/XWjxGym">
          1_html.html</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
          on <a href="https://codepen.io">CodePen</a>.</span>
        </p>
        <script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script><br><br>
        
    - `1_html.html`을 복사하여 적절히 수정하여 나머지 문서를 완성
    - 완성된 `2_css.html`  
        <p class="codepen" data-height="265" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="LYRgaoL" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="2_css.html">
          <span>See the Pen <a href="https://codepen.io/logistex/pen/LYRgaoL">
고          2_css.html</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
          on <a href="https://codepen.io">CodePen</a>.</span>
        </p>
        <script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script><br><br>
        
    - 완성된 `3_javascript.html`  
        <p class="codepen" data-height="265" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="MWjPxNw" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="3_javascript.html">
          <span>See the Pen <a href="https://codepen.io/logistex/pen/MWjPxNw">
          3_javascript.html</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
          on <a href="https://codepen.io">CodePen</a>.</span>
        </p>
        <script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script><br><br>

- 본 교안의 원전
    - egoing, [WEB1 - HTML & Internet](https://opentutorials.org/course/3084), [opentutorials.org](https://opentutorials.org/), 2020-07-28.
    - 본 교안은 원전을 미세하게 수정하여 작성하였음
    - 원전의 내용 구성 및 강의 진행 방식이 매우 훌륭하고 탁월함
    - 신입생 특강은 완주하는 학생이 많지 않음
    - 완주하지 못하더라도, 원전에서 충분히 자습할 수 있다는 점을 고려했음
    - 원전에서는 동영상 강의도 제공되므로 적극 활용하기 바람  
    [![](https://s3.ap-northeast-2.amazonaws.com/opentutorials-user-file/course/94.png)](https://opentutorials.org/)

## 웹 사이트 2차 완성 (스타일)

- 구글에서 'CSS 화면 레이아웃'으로 검색  
    [CSS / 고정형 레이아웃 만들기](https://www.codingfactory.net/10530) 참고

- 완성된 `index.html` 
    
<p class="codepen" data-height="265" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="NWRQyVB" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="index_css.html">
  <span>See the Pen <a href="https://codepen.io/logistex/pen/NWRQyVB">
  index_css.html</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>
<br><br>

- 완성된 `1_html.html` 
<p class="codepen" data-height="265" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="VwKoQOP" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="1_html_css.html">
  <span>See the Pen <a href="https://codepen.io/logistex/pen/VwKoQOP">
  1_html_css.html</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>
<br><br>

- 완성된 `2_css.html`  
<p class="codepen" data-height="265" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="dypxmbN" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="2_css_csss.html">
  <span>See the Pen <a href="https://codepen.io/logistex/pen/dypxmbN">
  2_css_csss.html</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>    
<br><br>
        
- 완성된 `3_javascript.html` 
<p class="codepen" data-height="265" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="XWjvEWW" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="3_javascript_css.html">
  <span>See the Pen <a href="https://codepen.io/logistex/pen/XWjvEWW">
  3_javascript_css.html</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>    
<br><br>

## 웹 사이트 3차 완성 (스타일 파일 분리)

- 분리된 `css.css`

<p class="codepen" data-height="265" data-theme-id="light" data-default-tab="css,result" data-user="logistex" data-slug-hash="WNGVzbY" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="css_final.css">
  <span>See the Pen <a href="https://codepen.io/logistex/pen/WNGVzbY">
  css_final.css</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>   
<br><br>

- 완성된 `index.html`
<p class="codepen" data-height="265" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="oNzKqXB" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="index_final.html">
  <span>See the Pen <a href="https://codepen.io/logistex/pen/oNzKqXB">
  index_final.html</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>
<br><br>

- 완성된 `1_html.html` 
<p class="codepen" data-height="265" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="zYoOEBJ" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="1_html_final.html">
  <span>See the Pen <a href="https://codepen.io/logistex/pen/zYoOEBJ">
  1_html_final.html</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>
<br><br>

- 완성된 `2_css.html`  
<p class="codepen" data-height="265" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="ExgqEKP" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="2_css_final.html">
  <span>See the Pen <a href="https://codepen.io/logistex/pen/ExgqEKP">
  2_css_final.html</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>
<br><br>
        
- 완성된 `3_javascript.html` 
<p class="codepen" data-height="265" data-theme-id="light" data-default-tab="html,result" data-user="logistex" data-slug-hash="RwGXMaj" style="height: 265px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;" data-pen-title="3_javascript_final.html">
  <span>See the Pen <a href="https://codepen.io/logistex/pen/RwGXMaj">
  3_javascript_final.html</a> by logistex (<a href="https://codepen.io/logistex">@logistex</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>
<br><br>

- 완성된 코드는 [https://github.com/logistex/test0100](https://github.com/logistex/test0100)에서 일괄 다운로드 가능함  
    - 위 링크로 접속하여, 우측 상단에 보이는 초록색 `code`를 클릭하면, 보이는 메뉴에서  
    - `Download Zip` 항목을 클릭하면 내 컴퓨터로 다운로드 가능함
- 완성된 웹 사이트는 [https://logistex.github.io/test0100/](https://logistex.github.io/test0100/)에서 확인할 수 있음    

- 엄청나게 **축하!**  
    - 코딩에 대한 두려움을 떨쳐내는 계기가 되었기를!
    - 코딩을 통한 흥분과 열광을 경험하시길! 
    - 코딩이 우리에게 펼쳐줄 새로운 세상을 만끽하기를!
    ![축하](https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/module/3135/7710.jpeg)


---

[![going home](https://user-images.githubusercontent.com/10287629/104793991-511fcd80-57e8-11eb-86c8-27356c8dd83d.png)](https://logistex.github.io/smart_IT/)
