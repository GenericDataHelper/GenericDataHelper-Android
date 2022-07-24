# GenericDataHelper-Android
맨날 만드는 그것!! Data object와 관련된 REST API를 빠르게 작성할 수 있게 도와주는 Android Client용 Module

# 설치 방법
당신의 git 최상위 폴더에서 다음 명령어를 실행합니다:

 git submodule add git@github.com:GenericDataHelper/GenericDataHelper-Android.git
 
또는 아래와 같이 특정 디렉터리에 설치할 수 있습니다.

  git submodule add git@github.com:GenericDataHelper/GenericDataHelper-Android.git android/GenericDataHelper-Android



settings.gradle 파일을 열고 아래 줄을 추가합니다.
  include ':GenericDataHelper-Android'
  
app의 build.gradle 파일을 열고 dependencies에 아래 줄을 추가합니다.
  implementation project(path: ':GenericDataHelper')
  
