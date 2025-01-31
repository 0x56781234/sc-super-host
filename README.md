## sc-super-host (스타크래프트 32비트 슈퍼 방장)   
본 프로젝트는 게임 내에서 방을 생성했을 때, 목록 상단에 우선 노출되도록 우선순위를 조정해주는 기능을 제공합니다.    
이를 통해 방 생성 시 노출 우선권을 악용하는 핵 프로그램(klauncher) 사용자와 비사용자 간의 격차를 해소하고, 태초의 공정한 게임 환경을 조성하는 것을 목표로 합니다.

### 사용 방법

0. Battle.net에서 스타크래프트 실행 방식을 `64비트 대신 32비트 클라이언트 실행`을 체크합니다.

1. 아래 링크에서 `ExtremeInjector`, `super.dll`을 다운로드 합니다.   
* [https://github.com/master131/ExtremeInjector
](https://github.com/master131/ExtremeInjector/releases/download/v3.7.3/Extreme.Injector.v3.7.3.-.by.master131.rar)
* [https://github.com/0x56781234/sc-super-host/super.dll](https://github.com/0x56781234/sc-super-host/archive/refs/heads/main.zip)

2. 스타크래프트를 먼저 실행 후, 다음으로 ExtremeInjector을 관리자 권한으로 실행하여, 다음을 따르세요.
* Process Name칸에 `StarCraft.exe`을 정확히 기재합니다.
* Add DLL 버튼을 눌러서 `super.dll`을 추가합니다.
* Inject 버튼을 누르면, 슈퍼 방장이 적용됩니다.

![image](https://github.com/user-attachments/assets/95fdef61-97ce-498b-8e8e-3b72dece4195)


### 참고사항
본 프로젝트에서 제공하는 `super.dll`을 스타크래프트에 주입하는 `Injector` 프로그램은 가장 대중적으로 사용되는 `ExtremeInjector`를 소개해드렸습니다. 
`Injector` 라는 것은, `.dll` 확장자의 라이브러리 파일을 특정 프로세스에 주입하기 위한 프로그램 입니다.   
만약 `ExtremeInjector` 프로그램이 윈도우 내 바이러스로 차단된다면, 다른 `Injector` 프로그램을 찾아 사용하셔도 무방합니다.   

### 업데이트
* 버전 업데이트 필요 시, 이 곳에 재배포 됩니다.
