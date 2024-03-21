<div align="center">

# Tennis Echo (Unity)
**테니스 에코 (유니티)**<br>

2023 디자인적 사고 팀프로젝트<br>
2023 Design Thinking Team Project

</div>

## 개요 | Outline

제작 기간(period): 2023/10/13 ~ 2023/12/23

인공지능을 이용한 테니스 :tennis: 가이드 앱 만들기 프로젝트입니다.
오픈소스인 [ThreeDPoseUnityBarracuda](https://github.com/digital-standard/ThreeDPoseUnityBarracuda)와 유니티를 활용하여 제작하였습니다.

더 자세한 내용은 [이 링크](https://big-tracker-47a.notion.site/12-14-d93f476dd8ce41ffb1f5b3410525bab9?pvs=4)를 참고해주세요!

It is a project to create a tennis :tennis: guide app using artificial intelligence.
It was produced using the open source [ThreeDPoseUnityBarracuda](https://github.com/digital-standard/ThreeDPoseUnityBarracuda) and Unity.

For more information, please refer to [this link](https://big-tracker-47a.notion.site/12-14-d93f476dd8ce41ffb1f5b3410525bab9?pvs=4)!


## 팀 구성원 | Team member

* [Keval](https://github.com/kevalsil)<br>
* [Ji Hwan Park](https://github.com/DefineJH)<br>
* [OverWindow](https://github.com/OverWindow)<br>
* [hoyoon choi](https://github.com/hoyoonchoi)<br>

## 개발과정 | Development process

[Presentation PPT](https://drive.google.com/file/d/11CmiScZ9sJiZIK8G8POVK6VpsX0rLEDj/view?usp=drive_link)

## 사용법 | How to use

### 1. 실행 | Execution

TennisTeacher.exe를 실행합니다.

Run TennisTeacher.exe.

### 2. 로비 | Lobby

![lobby](./Screenshot/Tennis_lobby.png)</br>

모드를 선택할 수 있습니다.
* 연습 모드: 공이 일정한 시간마다 날아옵니다.
* 거울 모드: 초기에는 공이 자동으로 날아오나, 이후부터 자신이 쳤던 방향대로 다시 공이 날아옵니다.

Allows you to select a mode.
* 연습 모드(Practice mode): The ball flies at regular intervals.
* 거울 모드(Mirror mode): Initially, the ball flies automatically, but then it flies back in the direction it hit.

### 3. 연습 모드 | Practice mode

![detail](./Screenshot/Tennis_menu.png)</br>
![detail](./Screenshot/Tennis_detail.png)</br>
![ready](./Screenshot/Tennis_ready.png)</br>
![start](./Screenshot/Tennis_start.png)</br>

입장 시 3가지 자세 중 하나를 선택해 연습할 수 있습니다. 선택 시 시연 연상이 나오며, 구동 준비 이후 연습이 시작됩니다.

When entering, you can practice by selecting one of the three postures. When selected, you will be reminded of the demonstration, and practice will begin after you are ready to drive.

### 3. 거울 모드 | Mirror mode

구동 방법은 연습 모드와 동일합니다.

The driving method is the same as the Practice mode.

## 기타자료 | Other data

<details close>
  <summary>Source code</summary>
  GameManager.cs: 게임 전체를 관리합니다.</br>
  LobbyManager.cs: 로비씬을 관리합니다.</br>
  RotateRacket.cs: 3d 테니스 라켓 오브젝트를 돌립니다.</br>
  PracticeManager.cs: 연습씬을 관리합니다.</br>
  BallShooter.cs: 공을 발사합니다. (현진님 브랜치, 약간 수정)</br>
  Ball.cs: 공의 타격 판정을 관리합니다. 공 오브젝트에 부착합니다.</br>
  TrailRenderer.cs: 공의 궤적을 그립니다. 공 오브젝트에 부착합니다.</br>
  RoundUIManager.cs: 라운드 UI를 그립니다.</br>
</details>
