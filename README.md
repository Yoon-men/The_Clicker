![KOM_header](https://user-images.githubusercontent.com/64591335/155003398-f30bfcc2-39b7-48e3-b4b2-e9b18a357fe2.png)

<a href = "https://github.com/Yoon-men/The_King_of_Macro/releases/tag/v2.0"><img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/Yoon-men/The_King_of_Macro?color=b461f2&logo=github"></a>

# "What the fuck is this?"
사용자 설정 매크로 프로그램입니다.

이 프로그램을 사용하기 위해서는 매크로 데이터를 저장해두는 'DATA.p' 파일이 필요합니다.
<details>
  <summary>"Why did you make it?"</summary>

  ![image](https://user-images.githubusercontent.com/64591335/165354839-8295c95e-883f-4a39-bf61-60a75ef76e65.png)
  
  ![image](https://user-images.githubusercontent.com/64591335/165355482-82fbd3ab-8f5b-4fcc-a0aa-99e7304302db.png)
  
  레바의 모험 하려고 만들었습니다.
  
  스킬을 쓰려면 '무색 큐브 조각'이라는 아이템이 많이 필요한데,
  
  손으로 일일이 한 번씩 클릭해가며 사기가 너무 귀찮아서 The_King_of_Macro를 만들게 되었습니다.
</details>

<br>

# How To Use (v2.1)
![KOM_v2 1_mockUp](https://user-images.githubusercontent.com/64591335/195372144-15598ea2-3e1a-4bb2-bca4-1391389d3989.png)


【 기본 】
- 설정 창에서 '불러오기' 버튼을 눌러 DATA.p를 불러온다.

【 추가 】
- 메인 창에서 원하는 매크로 이름을 적고 '추가' 버튼을 누른다.

【 편집 】
- 마우스 좌표 입력 : '클릭 추가' 버튼을 누르고 키보드 F9키(좌클릭) or F10키(우클릭)를 누른다.
- 키보드 입력 : '키보드 추가' 버튼을 누르고 키보드 입력을 한다.
- 딜레이 추가 : '딜레이 추가' 버튼을 누르고 새로 열리는 창에서 원하는 딜레이 초를 입력하고 '추가' 버튼을 클릭한다.
- 컬러체커 추가 : '컬러체커 추가' 버튼을 누르고 원하는 좌표를 추가한다. 원하는 좌표의 컬러를 복사할 수 있으며 컬러체크 딜레이 설정 기능까지 제공한다. 추가한 팔레트를 삭제하고 싶은 경우에는 해당 팔레트를 더블 클릭하면 삭제 여부를 묻는 창이 나온다.
- 삭제 / ▲ / ▼ : 원하는 매크로 부분을 누른 다음에 버튼을 클릭한다.

【 삭제 】
- 삭제하고 싶은 매크로가 있을 경우 그 매크로명을 선택하고 '삭제' 버튼을 누른다.

【 실행 】
- 실행하고 싶은 매크로명을 선택하고 몇 번(or 몇 초 동안) 실행할지 횟수(or 초)를 적은 뒤 '실행' 버튼을 누른다.

【 중단 】
- 매크로 동작 중 중지시키고 싶을 경우에는 중단 키(기본값은 ESC키)를 누른다.
- 중단 키를 변경하고 싶을 경우에는 프로그램 내 설정 창에서 변경한다. (단, 프로그램 종료 시 설정한 중단 키는 ESC키로 초기화된다.)

<br>

# Download
이미 DATA.p 파일을 갖고 있을 경우에는 exe 파일만 설치해주세요.
> <The_King_of_Macro_v2.1>
>> <a href = "https://github.com/Yoon-men/The_King_of_Macro/releases/tag/v2.1">Download Link (Click here)</a>

<br>

# Plan
<details>
<summary>자세히</summary>

- [x] 마우스 입력 추가
- [x] 실행 간격 설정 추가
- [x] 딜레이 설정 관련 변경
- [x] 키보드 입력 추가
- [x] 매크로 동작 중 중지 기능 추가
- [x] 매크로 실행 방법 선택지 추가 ex) 몇 분 동안 실행 or 몇 번 실행
- [x] 키보드 동시 입력 기능 
- [x] 매크로 동작 중 중지 키 사용자 설정 기능 추가
- [x] 설정 창에서 ESC키를 눌러도 나가지지 않도록 변경
- [x] 마우스 좌클릭, 우클릭 구분해서 저장하는 기능 추가
- [x] 매크로 편집 기능('마우스 클릭, 키보드 입력, 딜레이 추가' 통합 기능) 추가
- [x] 각 매크로 사이사이 딜레이 설정 가능토록(편집 창에서)
- [x] 특정 매크로키 삭제 기능 추가(편집 창에서)
- [x] 불러오기 기능 setting UI 내부로 이동
- [x] 자체 UI 변경(mainUI, settingUI, editUI, addDelayUI 총 4종)
- [x] 선택한 매크로가 없을 때 Up, Down 버튼이 동작하지 않도록 조치
- [x] settingUI에 '매크로 프로그램을 가장 위로' 선택 기능 추가
- [x] addClick >> 마우스 클릭이 아닌 키보드 입력으로 마우스 좌표를 추가할 수 있도록 만들기
- [x] 매크로 데이터 저장 방식 변경 (.csv -> .p)
- [x] 컬러체커 기능 추가(색깔 비교 체크)
- [ ] 딜레이 추가 시 초, 분 단위 선택하여 추가할 수 있도록 만들기
- [ ] 추가한 컬러체커 수정 가능하도록 만들기
- [ ] 마우스 좌표 직접 입력으로 입력 추가 가능하도록 만들기
- [ ] pc 조작 기능 추가(매크로 완료 후 pc 종료, 절전 등의 동작을 설정할 수 있도록)


</details>

<br>

# Update History
◇ 2021.12.6 ( MON ) 11:46 // v1.0
- v1.0 개발

◇ 2021.12.9 ( THU ) 21:29 // v1.1
- 딜레이 설정 관련 변경

◇ 2021.12.13 ( MON ) 20:49 // v1.2
- 키보드 입력 기능 추가

◇ 2021.12.31 ( FRI ) 10:52 // v1.3
- 구조 단순화

◇ 2022.1.3 ( MON ) 17:18 // v1.4
- 설정 가능한 매크로 동작 횟수 변경 (99 → 99999999)
- 매크로 이름 추가 시 입력해놓은 내용을 삭제하는 기능 추가
- 매크로 이름을 추가할 때 버튼 클릭뿐만이 아니라 Enter키를 눌러서도 추가가 가능해짐

◇ 2022.1.4 ( TUE ) 03:33 // v1.5
- 코드 내 'Form' 항목 삭제

◇ 2022.1.19 ( WED ) 17:56 // v1.6
- 이전 버전에서 나타난 버그 해결
- 매크로 실행 타입 변경 기능 추가 (1. 횟수 / 2. 시간)
- 매크로 동작 중 중지 기능 추가 (매크로 동작 중 ESC키 입력)

◇ 2022.1.25 ( TUE ) 09:51 // v1.7
- 이전 버전에서 나타난 버그 해결
- 키보드 동시 입력이 가능해짐
- 매크로 중단 키 사용자 설정 기능 추가 (설정 창 안에서 설정 가능)

◇ 2022.2.4 ( FRI ) 22:38 // v1.8
- 매크로 편집 기능('마우스 클릭 추가, 키보드 입력 추가, 딜레이 추가' 통합) 추가
- 설정 창에서 ESC키를 눌러도 나가지지 않도록 변경

◇ 2022.2.22 ( TUE ) 21:37 // v2.0 - **Changing UI**
- 이전 버전에서 나타난 버그 해결
- 자체 UI 변경 (mainUI, settingUI, editUI, addDelayUI 총 4종)
- '불러오기' 기능이 settingUI 안으로 들어감

◇ 2022.10.23 ( SUN ) 21:57 // v2.1
- 컬러체커 기능 추가 (In editUI)
- settingUI에 '매크로 프로그램을 가장 위로' 선택 기능 추가
- 마우스 클릭 대신 키보드 입력으로 마우스 좌표를 추가하도록 변경 (좌클릭 = F9, 우클릭 = F10)
- 딜레이 도중 매크로 종료 가능
- 매크로 데이터 저장 방식 변경 (.csv -> .p)

◇ 202?.??.?? ( ??? ) ??:?? // v2.2
- 실행 횟수(혹은 실행 시간) 입력 후 실행 버튼뿐만이 아니라 Enter키를 눌러서도 매크로 시작 가능
- 딜레이 추가 시 초, 분+초 단위를 선택하여 추가 가능
- 이미 추가한 매크로를 수정할 수 있게 됨(Click, Keyboard, etc.)
