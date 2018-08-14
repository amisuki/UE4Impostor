# Unreal Engine Impostor Test

![capture](https://user-images.githubusercontent.com/1418478/44069143-6f171e28-9fb8-11e8-9c6a-c643ba5afbf6.PNG)


[사이트](https://shaderbits.com/blog/octahedral-impostors)를 참고하여 테스트한 프로젝트입니다. [Github Link](https://github.com/ictusbrucks/ImpostorBaker)

4.19에서 테스트 완료.

4.20.1에서 테스트를 해보았으나. Show Only Actors가 에러상태로 엔진풀소스코드를 열어보면 
Engine\Source\Runtime\Engine\Classes\Components\SceneCaptureComponent.h 에 ShowOnlyActors변수는 4.19와 4.20.1코드와 차이가 없는 UPROPERTY이나 4.19에서 ReadOnly를 무시하고 읽을 수 있어서 에러 없이 잘되었던 것같다.


![capture2](https://user-images.githubusercontent.com/1418478/44069165-85be66fe-9fb8-11e8-83af-7a356a31600d.PNG)


![capture3](https://user-images.githubusercontent.com/1418478/44069171-887b708a-9fb8-11e8-897d-24004030f25a.PNG)
