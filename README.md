> # 이뉴에게 물어봐
>
> 인천대학교와 관련된 정보를 제공해주는 캠퍼스 가이드 이뉴(INU) 입니다.



![intro](https://raw.githubusercontent.com/kusakina0608/AskINU/master/img/intro.gif)

캠퍼스 가이드 이뉴는 직관적인 인터페이스로 사용자가 간편하게 학교에 대한 정보를 얻을 수 있도록 도와줍니다.

학생을 포함한 학내 구성원, 방문객들은 음성인식 또는 화면에 보이는 아이콘을 터치하여 손쉽게 이뉴를 사용할 수 있습니다.

주요 기능은 빈 강의실 찾기, 강의실 시간표 확인, 길 찾기, 학교 생활 팁 확인입니다.

<br>

<br>

>  ## 주요 기능

#### 1. 빈 강의실 찾기

[![빈 강의실 찾기](https://raw.githubusercontent.com/kusakina0608/AskINU/master/img/thumbnail_1.jpg)](https://youtu.be/hBACvcsHPEg)

학생들은 빈 강의실 찾기 기능을 사용하여 원하는 시간대에 비어있는 강의실을 확인할 수 있습니다.

빈 강의실 찾기 기능은 메인 화면의 버튼을 터치하여 실행할 수 있습니다.

또는 음성 인식을 통해 빈 강의실을 알려달라고 요청할 수도 있습니다.

<br>

<br>

#### 2. 강의실 시간표 확인

[![강의실 시간표 확인](https://raw.githubusercontent.com/kusakina0608/AskINU/master/img/thumbnail_2.jpg)](https://youtu.be/0EGeGn7FEUc)

특정 강의실의 시간표를 알고싶을 때 강의실 시간표 확인 기능을 사용하여

원하는 강의실에서 어떤 강의가 진행되는지 알 수 있습니다.

화면 터치 또는 음성인식을 통해 강의실의 시간표를 간단히 조회할 수 있습니다.

<br>

<br>

#### 3. 길 찾기

[![길 찾기](https://raw.githubusercontent.com/kusakina0608/AskINU/master/img/thumbnail_3.jpg)](https://youtu.be/Xkj_3OQy75o)

학교에 처음 온 방문객은 더 이상 지나가는 학생을 붙잡고 길을 묻지 않아도 됩니다.

화면에서 안내받고 싶은 건물을 선택하거나 음성인식을 통해 길안내를 요청해서 최단 경로를 확인하세요.

<br>

<br>

#### 4. 학교 생활 팁 확인

[![학교 이용 팁 확인](https://raw.githubusercontent.com/kusakina0608/AskINU/master/img/thumbnail_4.jpg)](https://youtu.be/qH5DYqXvOQA)

와이파이 비밀번호, 프린터 위치, 복지시설, 점심 메뉴 등 학교와 관련된 다양한 정보를 한눈에 확인할 수 있습니다.

<br>

<br>

> ## 프로젝트 구조

<br>

![intro](https://raw.githubusercontent.com/kusakina0608/AskINU/master/img/Architecture.png)

이뉴의 모든 기능은 화면 터치 또는 음성인식으로 사용할 수 있습니다.

사용자의 음성 명령은 GCP를 통해 텍스트로 변환되어 자체 서버로 전송되며,

서버에서는 전송받은 텍스트를 분석하여 원하는 정보를 사용자에게 전달해줍니다.

AWS를 사용하여 구축한 서버에는 Amazon Linux 2, Apache 웹 서버, MariaDB, PHP의 LAMP 스택이 구축되어 있습니다.

<br>

<br>

> ## Credits

### Creator

**Kina**

- [:octocat:Github](https://github.com/kusakina0608)

**RiRi**

- [:octocat:Github](https://github.com/yuhyerin)

