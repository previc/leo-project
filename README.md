# leo-project

`leo-project`는 Previc가 개발하는 모바일 앱 시리즈(**DrawLeo**, **ListenLeo**)를 한 곳에 모아 관리하는 메타 레포입니다. 각 앱은 독립된 저장소로 개발되며, 이 레포는 서브모듈로 묶어 버전과 릴리즈를 함께 추적합니다.

## 구성

- [`drawleo/`](./drawleo) — DrawLeo 서브모듈
- [`listenleo/`](./listenleo) — ListenLeo 서브모듈

## DrawLeo

어린이를 위한 안드로이드 태블릿용 그림 그리기 앱입니다. 손끝/펜으로 자유롭게 그리고, 붓 크기·색상을 조절하며, 작업물을 갤러리에 저장할 수 있습니다.

- **최신 APK**: <https://proxy.somuna.net/apk-releases/drawleo/drawleo.apk>

## ListenLeo

유튜브에서 가져온 오디오를 라이브러리로 정리해 듣는 안드로이드 앱입니다. 가져오기 → 라이브러리 관리 → 재생을 하나의 흐름으로 제공합니다.

- **최신 APK**: <https://proxy.somuna.net/apk-releases/listenleo/listenleo.apk>

## 참고

각 앱의 상세 사용법, 빌드 방법, 변경 이력 등은 서브모듈 내부의 `README.md`를 참조하세요.

- [`drawleo/README.md`](./drawleo/README.md)
- [`listenleo/README.md`](./listenleo/README.md)

## 서브모듈 클론

이 레포를 처음 클론한다면 서브모듈까지 함께 받아야 합니다.

```bash
git clone --recurse-submodules https://github.com/previc/leo-project.git
```

이미 클론했다면 다음 명령으로 서브모듈을 초기화할 수 있습니다.

```bash
git submodule update --init --recursive
```
