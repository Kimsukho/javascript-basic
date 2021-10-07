# JavaScript Basic
JavaScript 및 HTML/CSS 공부하기
<br><br><br>

## 자바스크립트란?
### : 객체 기반의 스크립트 프로그래밍 언어 <br>
웹 브라우저가 탑재된 모든 기기에서 자바스크립트로 구현한 프로그램을 실행시킬 수 있다는 것을 얘기함 <br>

† 기존 웹 애플리케이션 개발을 위해서만 사용하던 자바스크립트 node.js가 나오게 됨으로써 웹 브라우저에 종속된 것만이 아니라 
  데스크톱 애플리케이션, 모바일 앱, 게임, 키오스크 아두이노와 같은 마이크로 컨트롤러 등 분야가 넓어짐
<br>
### [개발 환경 구성]

#### 1. 비쥬얼스튜디오코드, VSCode (Visual Studio Code)<br>
: 개발을 위한 도구, 다양한 언어로 개발을 할 수 있다는 장점이 있다.
javascript-basic 폴더 내 -> New file -> basic.html

#### 2.  EXTENSIONS 프로그램 <br>
: 개발에 도움이 되는 다양한 도구(프로그램)
- HTML CSS Support
- HTML Snippets 
- JavaScript code snippets
- Live Server (앞으로 작성할 html 코드를 파일 형태가 아닌 서버 형태로, 마치 서버에서 구동된 것처럼 html 파일을 실행시켜줌, html을 실시간으로(live) 수정하고 있으면 웹 브라우저 refresh 안해도 자동으로 반영됨)
- Open In Default Browser (만들어진 파일을 우 클릭하고 Open In Default Browser 누르면 웹으로 바로 열린다)
<br>

### [ 자바스크립트 코드 작성 위치 ]

#### 1. 새로운 파일 생성 (new file)
#### 1-01.자바스크립트작성위치.html 파일 생성 (html:5 : html5의 기본 골격 구조 해당하는 것을 보여줌)

(1) `<html lang ="en">      ->      <html>`

(2) `<meta>` 지운다. 

(3) html 사용자 정의 Snippit 만들기
† Snippit : 미리 정의된 코드를 몇개의 글자를 이용해서 전체 완성된 코드를 불러서 쓸 수 있는 것 `<!DOCYPE html>   ~   </html>`<br>
† Snippit 설정 : 윈도우 메뉴바 -> preferences -> user snippits -> html.json -> 추가 및 수정하기<br>
† html.json : html에 해당한 스니핏을 넣을 수 있는 것<br>
† 전체 주석 해제 : 주석을 해제하고자 하는 부분 스크롤하고 ctrl + /  누르면 됨
#### 2. html 파일 생성
(1)`<head>`에 script 넣기

      <script>

           document.write("head 파일에 위치")

      </script>
(2) `<body>`에 script 넣기

      <script>

         document.write("body 파일에 위치")

      </script>`
#### 3. 새로운 폴더 생성 (new folder)

(1) scripts 폴더 생성

(2) 폴더 내에 1-01. 자바스크립트작성위치.js 생성

` document.write("js 파일에 위치")`
#### 4. html파일에서 위에 작성한 js 파일 불러오기
3-(1) 번에서 작성된 html파일 <head>에서 js 파일 추가하기 : <script src ="scripts/1-01.자바스크립트작성위치.js"></script>
† html파일에다 <script> 넣는 부분 body태그에 작성<br>
이유 : <head> 태그 안에 <script>를 작성하게 되면 html 파일 랜더링할 시 웹 페이지가 로딩걸리는것에 시간이 지체되므로 <body> 태그 안에 작성함.<br>
