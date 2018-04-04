# github-com.celloa.cordova.dev

-  프로젝트 생성
cordova create 폴더명 패지키명 앱명 -d

-- 프로젝트 폴더로 이동 후
- 플랫폼 추가 명령어
cordova platform add android@6.3.0
cordova platform add browser
cordova platform add ios

- 플랫폼 업데이트 (함부로 하면 안됨)
cordova platform update 플랫폼이름

- 설치된 플랫폼 목록
cordova platform list

- 플랫폼 실행
cordova run android
cordova run browser

- 단말기 리스트
cordova run android --list
adb devices

- 빌드cd 
cordova build android
cordova build --release android
