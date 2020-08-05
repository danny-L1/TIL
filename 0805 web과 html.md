# Web

1990년 11월에

세계 최초의 웹브라우저 탄생 '월드 와이드 웹(world wide web)'

최초의 웹서버  info.cern.ch

웹을 만든 팀 버너스 리는 웹을 퍼블릭 도메인으로 선언함

웹의 핵심은 접근성, 누구나 차별없이 정보에 접근할 수 있다는 것

웹은 모든 운영체제에서 동작하고 웹페이지의 소스코드는 누구나 볼 수 있다.

### 서버와 클라이언트

웹브라우저는 클라이언트 컴퓨터에서 동작하므로 웹브라우저를 다른 말로는 웹 클라이언트라고도 한다.

### 웹 호스팅

인터넷에 연결된 컴퓨터 하나 하나를 호스트라고 합니다.

이런 컴퓨터를 빌려주는 사업을 호스팅

-github로 웹페이지 호스팅하기

1. upload file 로 html 파일 업로드하기
2. commit change 로 업로드하기
3. Github Pages 항목에서 master branch를 선택
4. Select branch 중 master branch > save
- github의 컴퓨터에 설치된 웹서버에 접속하게 됨.

html만으로 만들어진 정적인 웹사이트 호스팅은 무료가 많지만 

동적인건 그렇지 않음..

### 웹서버 운영하기

웹서버의 종류

- Apache
- IIS
- Nginx

HTTP

hyper text transfer protocol

웹페이지를 전송하기 위해 만든 통신규약

주소창에 입력된 주소가 [http://로](http://xn--2o2b/) 시작하면 웹브라우저는 http 통신규약에 따라서 웹서버에 접속하게 됩니다. file://로 시작하면 웹브라우저는 파일을 직접 열어서 보여줍니다.

## **HTML(** HyperText Markup Language)

HTML 에디터 ( 에디트 플러스 / 아톰 / 메모장.. )

# **tag**

<u> 기울임

<strong> 강조

### <br>과 <p>의 차이

p 태그 br로 하는 단락 구분도 하면서 

css를 통해 스타일도 줄 수 있음

### 부모태그와 자식태그 <ul><li><ol>

<ul> ( **u**nordered **l**ist )

<ol> ( **o**rdered **l**ist )

### <meta charset="utf-8">

웹브라우저가 페이지를 utf-8로 읽게 해주는 코드

### <!doctype html>

이 웹페이지가 HTML로서 만들어졌다는 것을

표현하기 위한 코드

### <a>

anchor의 첫글자를 딴 링크 태그

**href**

HyperText Reference의 약자

**target="_blank"**

링크를 클릭했을 때

새창에서 페이지가 열리게 하는 속성

**title="blah blah"**

이 링크가 어떤 내용을 담고있는지 툴팁으로 보여주는 속성
