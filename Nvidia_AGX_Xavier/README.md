# Xavier

### install
* 준비
1. 가장 중요한 Xavier
2. C-Type 케이블
3. 랜선
4. JetPack 설치를 위한 호스트 PC(Ubuntu)
5. ETC...

* 초기단계
1. Xavier를 호스트PC에 연결합니다.
    1. 이때, 전원 표시 옆에있는 곳에 연결 합니다.
1. JetPack Install
    1. 아래의 나와 있는 곳에 접속하여 SDK Manager를 다운 받아 Jetpack을 설치 해 줍니다.
    1. [SDK_Manager](https://developer.nvidia.com/embedded/jetpack)에 접속하여 NVIDIA에 로그인 후 다운 받을 수 있습니다.  
       -`NVIDIA SDK Manager Method` 항목에 `FOR ANY JETSON DEVELOPER KIT`를 다운 받아 줍니다.
    1. 설치 완료 시 터미널에 아래 명령어를 입력하여 SDK_Manager를 실행시켜 줍니다.

        ```
        # [version]부분에서는 Tab key를 입력하여 자동완성을 시켜 주면 됩니다.
        sudo apt install ./sdkmanager-[version].deb

        # SDK_Manager 실행
        sdkmanager
        ```
    1. `SDK_Manager`창이 생성 되면 로그인 후 순서에 따라 설치를 진행하시면 됩니다.
    1. 진행 중 아래의 팝업이 발생하면 2번란을 Auto
    
    
