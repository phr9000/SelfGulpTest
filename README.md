gulp 개발환경 만들기 22/3/11

1. [node.js 설치]
   node --v
   npm --v
   : cmd에서 제대로 설치 되었는 지 확인하는 명령어

2. [gulp 전역 설치]
   npm install gulp -g
   : 설치 후 cmd에서
   gulp -v
   으로 제대로 설치 되었는지 확인

3. [gulp local 설치]
   npm install gulp --save

: -dev 붙이는 이유는 모듈은 개발할때만 필요, 배포할때는 필요하지 않아서 입니다.
