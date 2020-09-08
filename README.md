# golang-workspace

대학교 과제나 실습 환경에서 새로운 코드를 짤 때 새 프로젝트를 만들거나 기존에 작성해두었던 코드를 삭제 또는 주석 처리를 하면서 개발했었습니다. 이 레포지토리는 복잡한 과정 없이 언제 어디서나 빠르게 코드 작성 및 빌드를 도와주는 `Github Codespace` 기반 `Workspace` 입니다.

## 1. Workspace 가져오기

우측 상단에 `Use this template` 를 눌러 본인의 `Repository`에 등록하세요.

## 2. Github Codespace 활성화

등록된 본인의 Repository에서 초록색 `Code`를 눌러 `Open with Codespaces`를 클릭하고 새로운 `Codespace`를 생성하세요.

## 3-1. golang 익스텐션 설치

`Ctrl + Shift + X` 를 눌러 `EXTENSIONS` 탭을 열고, `go` 를 검색하여 설치하고, Codespace를 `Reload`해주세요.

## 3-2. 추가 패키지 설치

빌드 및 디버깅을 위하여 코드를 하나 켜고 `F5`를 누르면 패키지 설치를 추천해줍니다. 모든 패키지를 설치하세요.

```bash
$ sudo apt-get install gdb -y
```

## 4. 개발 시작

프로젝트 `/src` 폴더에 `example` 파일들을 참고하여 단일 코드를 작성하세요.

## 5. 실행 및 디버깅

`F5`를 누르면 현재 포커싱된 파일의 실행 및 디버깅이 시작됩니다. 기본적으로 `TERMINAL`이 선택되어 있는데, `DEBUG CONSOLE`을 클릭하면 코드가 실행되는 화면을 볼 수 있습니다.

## 6. Workspace 업데이트

이 Workspace는 업데이트 될 수 있으며, 업데이트 방법은 추후에 추가될 예정입니다.
