# React-native
```
npm install -g expo-cli
```

### Expo CLI
[Docs](https://facebook.github.io/react-native/docs/getting-started)
- (recommanded) [expo](https://docs.expo.io/versions/latest/) = create-react-app (기본 set-up)
    - native file을 숨기고 관리해줌
    - 휴대폰에서 앱 테스트 가능
    - API 관리/확장 측면
- React Native CLI (수동으로 작업하고 싶으면)
    - (iOS) 개발자 계정 및 기타 세부 과정 필요
    - native file 제어가능

### zsh: command not found: expo
```
# NPM global installs, react-native 폴더에서 하기
export PATH=$PATH:~/.npm-global/bin
```

### 실행
```
code .
git remote add origin https://github.com/iamwooki/fokin-weather
npm start
//Run on iOS simulator (Error)
sudo xcode-select -s /Applications/Xcode.app
```

### 명령어
- Command(Ctrl) + D
    - Debug Remote JS : 크롬 개발자 도구를 이용해 디버깅, 앱 속도 저하 (네트워크 요청, 콘솔 로그 작업 등에만 사용할 것)