# UpChecker

<p align="center">
	<img src="https://user-images.githubusercontent.com/50317129/110218958-c44be300-7eff-11eb-926c-9dd18d92fc2e.png" width="256" height="256" alt="UpChecker" title="UpChecker" />
</p>

<p align="center">
	Icons made by <a href="https://www.flaticon.com/authors/freepik" title="har1ton">har1ton</a> from <a href="https://www.iconfinder.com/har1ton" title="har1ton"> www.iconfinder.com/har1ton</a>
</p>

<br />
<br />
<br />

<p align="center">
	UpBit 공지사항 & 프로젝트 공시 확인 프로그램
</p>

# INFO

개발언어 : `JavaScript`

#### 지원 OS
<img src="https://img.shields.io/badge/Windows10-0078D6?style=flat-square&logo=Windows&logoColor=white"/>

<img src="https://img.shields.io/badge/MacOS (지원예정)-000000?style=flat-square&logo=Apple&logoColor=white"/>

#### Library & Framework
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=Node.js&logoColor=white&link=https://nodejs.org/ko/"/>

<img src="https://img.shields.io/badge/electon-47848F?style=flat-square&logo=Electron&logoColor=white&link=https://www.electronjs.org/"/>

<img src="https://img.shields.io/badge/electon%20builder-47848F?style=flat-square&logo=Electron&logoColor=white&link=https://www.electron.build"/>

<br />

※ 최상위 라이브러리만 표기하며, 해당 라이브러리에 의존되는 하위 라이브러리는 표기하지 않음

<br />
<br />

# RELEASE

## UpChecker 1.0.0 RELEASE

:calendar: 2021.03.07 Wed

+ 공지사항 체크
+ 프로젝트 공시 체크
+ 새로운 공지사항 & 공시 확인 시 알림 표시
+ 알림 내용 Telegram 제공 기능
+ 라이센스 적용

<br />
<br />

# 사용 방법

<p align="center">
	<img src="https://user-images.githubusercontent.com/50317129/110219017-21479900-7f00-11eb-99a8-c7184e71e9be.png" width="400" alt="UpChecker 개요" title="UpChecker 개요" />
</p>

아래의 Run 버튼을 클릭하여 UpBit의 공지사항 및 프로젝트 공시 현황을 체크한다.

<p align="center">
	<img src="https://user-images.githubusercontent.com/50317129/110219118-acc12a00-7f00-11eb-99f5-384659510072.png" width="400" alt="UpChecker 알림" title="UpChecker 알림" />
</p>

체크된 내용은 알림을 통해 사용자에게 제공된다.

<p align="center">
	<img src="https://user-images.githubusercontent.com/50317129/110219169-fa3d9700-7f00-11eb-9662-e7c58d16c7b2.png" width="400" alt="UpChecker 소셜" title="UpChecker 소셜" />
</p>

해당 내용은 텔레그램을 통해서도 받아볼 수 있으며, 현재는 단톡방으로 전송된다.<br />
이 기능은 추후 가능할 경우 1:1 채팅으로 전송할 수 있도록 추가할 예정이다.

## 메인

<p align="center">
	<img src="https://user-images.githubusercontent.com/50317129/110219029-2e648800-7f00-11eb-902b-52a0d6bf2be7.png" width="400" alt="UpChecker 공시" title="UpChecker 공시" />
</p>

메인에서는 가장 최근의 프로젝트 공시 및 공지사항의 내용을 확인할 수 있다.<br />
클릭 시 해당 내용을 확인할 수 있는 UpBit 페이지가 링크된다.

## 프로젝트 공시

<p align="center">
	<img src="https://user-images.githubusercontent.com/50317129/110219032-30c6e200-7f00-11eb-879a-d550b4bc957b.png" width="400" alt="UpChecker 공지사항" title="UpChecker 공지사항" />
</p>

가장 최근의 프로젝트 공시 목록 20개를 출력한다.<br />
클릭 시 해당 프로젝트 공시 내용을 확인할 수 있는 pdf 페이지가 링크된다.

## 공지사항

가장 최근의 공지사항 목록 20개를 출력한다.<br />
클릭 시 UpBit의 해당 공지사항 페이지가 링크된다.

<br />
<br />

# 여담

심심해서 만든 봇 프로그램. 어째 심심해서 만드는 것들은 보면 죄다 봇 프로그램이다. 귀찮아서 그런가.<br />

코인은 안 해서 잘 이해는 안 되지만, 공시? 이게 올라옴에 따라 코인 시세가 변동한다길래 이를 체크하도록 설계했다.<br />
기준은 국내 최대 규모라고 생각되는 UpBit를 기준으로 작성했다.<br />
코인 거래소치곤 왠만한 플랫폼만큼 API를 잘 제공해줘서 데이터 수집 자체는 그리 어렵지 않았다.

예전에 자격증 자리확인 매크로 만들었을때 붙이려다 만 Telegram 봇을 붙였다. 개개인의 니즈와 결과가 상이한 자격증 매크로보다 훨씬 범용적인 데이터라 단체 채팅방에 보내기 유리하다는 점이 주효했다.

결제 관련 API도 있던데, 차후 신규 공시가 확인되면 해당 코인을 자동으로 매매하는 기능을 붙일까 생각중이다.<br />
구매, 판매를 어떤식으로 결정할 것인지 등 생각해볼 부분이 많은 것 같다.<br />
공시 내용에 따라 사용자가 구매, 판매를 결정할 수 있도록 제공하는 것도 괜찮을 것 같다.
