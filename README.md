# html5 
작업환경 설치 https://github.com/limpi/html5/wiki 
교재 : HTML5+CSS3 웹표준의 정석 (저자:고경희, 출판사:이지스 퍼블리싱)
교재 웹사이트 : http://easyspub.co.kr/20_Menu/BookView/119/PUB#tab01 (하단에 동영상강의)
소스 : https://drive.google.com/file/d/0B_pYzKnELUDDekdGYThLM2YweFE/view 

I. HTML5 개요
￼1. HTML (HyperText Markup Language)
     - World Wide Web에서 사용하는 마크업 언어
     - 인터넷에서 사용하는 웹 페이지 구조를 표현하기 위한 언어
     - 하이퍼텍스트(HyperText) : 사용자의 선택에 따라 원하는 페이지로 이동할 수 있도록 조직화된 정보
     - 마크업 언어(Markup Language) : 어떤 문서안에 정보가 어떻게 구조화(배치, 크기, 모양) 되는가를 태그를 사용하여 지정하는 언어
          절차적(procedural) 마크업 언어 : 문서의 형식이나 텍스트의 외양을 기술 - 워드프로세서
          기술적(descriptive) 마크업 언어 : 문서의 논리적 구조 및 속성을 기술 - SGML, HTML, XML
     - 확장자 : .html .htm
     - 대소문자 구분하지 않음
     - 두 칸 이상의 공백은 한 칸으로 인식

2. 마크업의 종류
     - 구조(structure) : 문서의 구조적(structural) 정보 - 제목, 장, 절, 각주, 문단
     - 양식(style) : 문서를 외적으로 표현하기 위한(stylistic) 정보 - 글자체, 글자크기, 색
     - 내용(content) : 문서가 표현하는 실제 의미적(semantic) 정보
3. ￼HTML 역사
     1) HTML 역사
          - Tim Berners-Lee (http://www.ted.com/talks/tim_berners_lee_on_the_next_web)
          - ￼￼￼￼￼￼1991. HTML (CERN)
          - 1995. ￼￼￼HTML 2.0 (IETF)
          - 1997. HTML 3.2  (W3C)
          - 1999. HTML 4.01
          - 2000. ￼￼￼XHTML 1.0
          - 2001. XHTML 1.1
￼￼￼          - 2004. ￼￼￼￼Web Applications 1.0 (WHATWG : Ian Hickson, David Baron, David Hyatt)
          - 2008. HTML 5 First Public Working Draft (초안)
          - 2012. Candidate Recommendation
          - 2014. Proposed Recommendation
          - 2014.10.28. HTML 5 Recommendation (권고안) (http://www.w3.org/TR/html5)
     2) 권고안 단계
          http://wit.nts-corp.com/2013/10/16/280
          ➀ 노트(Note) : 기술문서로 제안하기 위해 제시된 문서
          ➁ 초안(WD, Working Draft) : 아직 완전하지 않은, 아이디어를 담은 문서
          ➂ 초안 검토안(LC, Last Call) : WD에 대한 최종 검토안
          ➃ 후보 권고안(CR, Candidate Recommendation) : 심사를 거친 작업 최종안
          ➄ 제안 권고안(PR, Proposed Recommendation) : 최종 권고안이 될 수 있는 전 단계
          ➅ 권고안(REC, Recommendation) : W3C 참여 회원에게 동의를 얻은 최종 표준안(standard)

4. HTML5에 대한 관심
     - 2009. Google I/O 개발자 컨퍼런스 - HTML5 데모 시연
     - 2010. Apple iPhone/iPad에 플래시 지원 거부
     - 2010. GENIVI 연합의 자동차 소프트웨어 플랫폼(IVI, In-Vehicle Infotainment)에 HTML5 적용 의지 피력
     - 2011. Adobe 모바일플래시 개발 중지
     - 2012. 국제전자제품박람회(CES) AT&T HTML5용 API 플랫폼 공개
     - 2012. 소셜 네트워크 게임회사 Zynga HTML5 개발 참여
     - 오페라 TV, 구글 TV, 인텔-삼성의 타이젠 TV, LG 웹OS TV 등 가전제품에 HTML5 플랫폼 탑재
     - 운영체제에 독립적(Cross-Platform), 다양한 기기 지원(One Source Multi Use) 등의 장점으로 인기

5. 관련 기구
     - W3C : 월드와이드웹을 위한 표준을 개발하고 가이드라인을 개발하는 조직, http://www.w3.org
     - WHATWG : 애플리케이션을 작성하고 전개할 수 있는 새로운 기술 개발을 위해 만든 오픈 커뮤니티, http://whatwg.org
￼￼￼￼￼￼￼
6. ￼HTML5 디자인 원칙
     - 호환성 : 혁신이 아니라 진화, 기존 HTML 문법/사용법을 최대한 지원, 단계적 기능 축소가 가능
     - 유용성 : 사용자가 최우선 순위, 웹 폼 입력 값의 유효성 확인(email, number, date), <input>의 datetime 등
     - 상호 호환성 : 불필요한 복잡성을 제거 단순함 추구, 명세서를 최대한 자세하게 기술하고 오류 처리에 용이하도록 설계
     - 보편적인 접근성 : 접근성, 미디어 독립성, 모든 언어 지원

7. ￼HTML5의 특징
     ➀ 웹 애플리케이션 개발을 위한 플랫폼 : 웹 문서 작성 + 추가적인 플러그인 없이 웹 애플리케이션 제작 가능
     ➁ 시맨틱 웹 : 의미있는 구조의 문서 작성을 위한 태그들이 추가
     ➂ 웹 표준화 : 어떤 브라우저에서든, 누구든 정상적으로 동작하는 사이트를 이용할 수 있도록 웹 표준 지향
          - HTML5 지원 여부 확인
            http://html5test.com
            http://caniuse.com
          - 문법검사
            http://validator.w3.org

8. HTML5의 주요 특징 및 기능
     - HTML5 differences with HTML4 http://www.w3.org/TR/html5-diff (번역 http://html5.creation.net/html4-differences)
     - HTML Tutorial http://www.w3schools.com/html/ > Search w3schools.com     
     ￼￼￼￼

￼￼￼￼9. ￼HTML 구성 요소
     - 요소, 태그, 속성, 변수
     - html 태그 (http://www.w3schools.com/tags)


10. HTML 기본 구조
     - DOCTYPE 선언의 간략화 (http://www.w3schools.com/tags/tag_doctype.asp)
     - DOCTYPE을 선언하지 않을 경우 비표준 관용모드(Quirks mode)로 랜더링되고, 선언시 표준모드(Standard mode)로 랜더링 된다
     - 문서의 최상위에 위치, 유효성검증, 문서형식을 지원하는 것이 아닌 기능을 지원하는 것이므로 구형브라우저에서도 최신의 문서형식이 허용된다
     - HTML5는 SGML에 기반을 두지 않아 DTD 참조가 필요없다
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN" "http://www.w3.org/TR/html4/frameset.dtd">
<!DOCTYPE HTML PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<!DOCTYPE HTML PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<!DOCTYPE HTML PUBLIC "-//W3C//DTD XHTML 1.0 Frameset//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-frameset.dtd">
<!DOCTYPE HTML PUBLIC "-//W3C//DTD XHTML 1.1//EN" "http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd">
￼<!DOCTYPE html>

     - 문자인코딩 선언의 간략화
<meta http-equiv="content-type" content="text/html; charset=UTF-8">
<meta charset="utf-8">

<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>Welcome to HTML5</title>
</head>

<body>
    <h3>HTML5의 특징</h3>
    <ol>
        <li>웹 어플리케이션 개발을 위한 플랫폼</li>
        <li>시멘틱 웹</li>
        <li>웹 표준화</li>
    </ol>
</body>
</html>




II. 시멘틱 웹을 위한 요소
1. 컨텐츠 타입에 따른 요소 분류

     http://www.w3.org/TR/html5/dom.html#kinds-of-content
     (번역 http://html5.clearboth.org/content-models.html#kinds-of-content)
Metadata content
나머지 내용의 표현이나 행동을 설정하거나 다른 문서와의 관계를 설정하거나 미분류 정보들을 포함
<base>, <command>, <link>, <meta>, <noscript>, <script>, <style>, <title>
Flow content
<body> 요소에서 사용되는 대부분의 요소들
...
Sectioning content
헤딩과 푸터의 유효범위를 정의
<article>, <aside>, <header>, <footer>, <nav>, <section>
Heading content
섹션의 헤더를 정의
<h1>, <h2>, <h3>, <h4>, <h5>, <h6>, <hgroup>
Phrasing content
문서의 텍스트를 정의
<a>, <abbr>, <area>, <audio>, <b>, <bdi>, <bdo>, <br>, <button>, <canvas>, <cite>, <code>, <command>, <datalist>, <del>, <dfn>, <em>, <embed>, <i>, <iframe>, <img>, <input>, <ins>, <kbd>, <keygen>, <label>, <map>, <mark>, <math>, <meter>, <noscript>, <object>, <output>, <progress>, <q>, <ruby>, <s>, <samp>, <script>, <select>, <small>, <span>, <strong>, <sub>, <sup>, <svg>, <textarea>, <time>, <var>, <video>, <wbr>, <text>
Embedded content
문서에 외부 동영상, 사진 등을 포함
<audio>, <canvas>, <embed>, <iframe>, <img>, <math>, <object>, <svg>, <video>
Interactive content
사용자와의 상호작용을 할때
<a>, <audio>, <button>, <details>, <embed>, <iframe>, <img>, <input>, <keygen>, <label>, <menu>, <object>, <select>, <textarea>, <video>


2. 레이아웃 추가 요소
     - 기존에 html 작성은 대부분 <div class=“”>의 형태로 div 요소와 class 속성으로 레이아웃을 구분
     - div 요소의 class 속성을 분석하여 가장 많이 쓰이고 유용한 의미들을 정리하여 html5 요소로 적용
<header>
머리말
소개 또는 네비게이션 목적의 도우미 그룹
(섹션의 제목, 차례나 검색 폼, 관련 로고 등을 감싸는 용도)
<main>
메인 컨텐츠
문서의 주요내용을 감싸는 용도
(문서에는 하나의 main 요소만 존재하여야 하며 article, aside, footer, header, nav 요소 안에 존재할 수 없다)
<section>
주제별로 나눈 컨텐츠
일반적인 문서 또는 프로그램의 섹션 (보통 제목으로 시작하는 컨텐츠의 의미적 그룹)
➀ 하나의 주제로 구성된 문서의 내용 부분을 나타낸다
<section><h1></h1><p></p></section> <section><h1></h1><p></p></section>

➁ 하나의 주제 안에 다른 세부 주제가 존재하는 경우 레벨을 달리하여(중첩) 나타낸다
<section><h1></h1> <section><h1></h1><p></p></section> </section>
<nav>
메뉴
다른 페이지 또는 동일 페이지의 다른 부분으로 이어주는 섹션, 즉 네비게이션 링크로 구성된 섹션
<article>
독립적인 컨텐츠
독립적으로 배포 혹은 재사용할 수 있는 컴포넌트
(포럼 글, 잡지나 신문의 기사, 블로그 항목, 사용자 의견, 위젯 등)
<aside>
부차적인 컨텐츠
주위 내용과 접점을 이루는 섹션, 주위 내용과는 분리된 것으로 간주할 수 있다. 일반적으로 사이드바 형태로 표현
<hgroup>
제목 묶음
섹션의 제목을 나타내는데, 제목이 몇개의 레벨을 가질때 그룹짓기 위해 사용
<section> <hgroup><h1></h1><h2></h2></hgroup> </section>
<footer>
꼬리말
가장 가까운 조상 요소인 섹션 컨텐츠의 꼬리말
(일반적으로 작성자, 연관 문서 링크, 저작권 정보 등)


3. 표현을 위한 추가/변경 요소
<mark>
강조 (시각적,의미적)
기본적으로는 노란색 형광펜을 칠한 표시
<strong>
강조 (시각적)

<time>
날짜/시간
<p>현재 시간은 <time>14:00</time>입니다.</p>

<!-- datetime 속성 -->
<p>이번 추석은 <time datetime="2014-09-08">월요일</time>입니다.</p>
<meter>
일정 범위안의 값/분포의 비율
- value 속성 : 실제 데이터
- min, max 속성 : 인식하는 최소값, 최대값
- low, high 속성 : 허용되는 최소값, 최대값
- optimum 속성 : 기대값
- title 속성 : 툴팁
<process>
현재 진행중인 상태
(javascript 연동)
- value 속성 : 현재 상태값
- max : 최대값




III. 폼
1. input 요소
<form action="" method="post”>
   <input type="text" name="textbox" hidden>
</form>
     1) type 속성값 : input 요소의 종류
          - 기존 : button, text, checkbox, radio, file(파일), image, password, reset(초기화), submit(전송), hidden,
          - 추가 : tel, email, url, number, range(슬라이더), search, color, date, datetime, datetime-local, month, week, time
     2) 속성
          - 기존 : type, name, size, value, checked, disabled, maxlength, readonly, src,
          - 추가 : placeholder(기본 표시텍스트), autofocus(자동커서), autocomplate(자동완성), required(필수), form(폼 지정), width, height, list, min, max, step
          - pattern : 입력값에 대한 유효성 검사 (정규표현식)
               정규표현식(regular expression) : 일반문자 및 메타문자로 알려진 특수문자로 구성된 텍스트의 패턴
               \(￦) : 다음에 오는 문자를 특수문자, 리터럴, 8진수 이스케이프로 표시
               [xyz] : 괄호로 묶인 문자집합중 하나,  [^xyz] : 괄호로 묶인 문자를 제외한 것 중 하나,  [a-z] : 영소문자 a부터 z까지 중 하나,  . : \n이외의 모든 단일 문자
               {n} : 음이 아닌 정수 n개,  {n,m} : n개 이상 m개 이하
               ^ : 시작,  $ : 끝
               * : 앞의 문자나 부분식이 0개 이상 {0,}, | : 혹은(이거나),  + : 앞의 문자나 부분식이 1개 이상 {1,},  ? : 앞의 문자나 부분식이 0개나 1개 {0,1}
               \d : 숫자,  \D : 숫자가 아닌 문자 [^0-9]            
             

2. datalist 요소
<input list="browsers">
<datalist id="browsers">
  <option value="Internet Explorer">
  <option value="Firefox">
  <option value="Chrome">
  <option value="Opera">
  <option value="Safari">
</datalist>

3. keygen 요소
     - 암호키 생성, 비밀키는 클라이언트에 저장되고 공개키는 서버로 보내진다
<form action="demo_keygen.asp" method="get">
  Username: <input type="text" name="usr_name">
  Encryption: <keygen name="security" keytype="rsa">
  <input type="submit">
</form>

4. output 요소
     - input 요소에 입력값이 변경되면 곧바로 반영하여 화면에 출력하기 위한 요소
     - for 속성 : 계산결과와 계산에 사용된 요소와의 관계를 지정
<form onsubmit="return false" oninput="o.value = a.valueAsNumber + b.valueAsNumber">
  <input name="a" id="a" type="number" step="any"> +
  <input name="b" id="b" type="number" step="1"> =
  <output name="o" for="a b"></output>
</form>



IV. 드래그앤드롭
     ➀ 드래그할 요소에 드래그 속성 지정: draggable=“true | false"
     ➁ 이벤트 지정 및 컨트롤
     
     ➂ 교환할 데이터에 대한 처리
          - dataTransfer 객체의 메소드 :
               clearData(type) : 데이터 초기화
               setData(type, data) : 새로운 요소 정의
               getData(type) : setData()에서 정의한 요소와 데이터를 가져옴
          - type : Text(text/plain: 단순한 문자열), URL(text/url-list: URL문자열), Files
     ➃ 포인터 변경관련 속성
          - effectAllowed : 드래그 동안 허용할 효과 (none, copy, link, move, copyLink, copyMove, linkMove, all, uninitialized)
          - dropEffect : effectAllowed 속성에서 허용한 동작과 일치 (none, copy, link, move)
          - 커서 이미지 변경 : setDragImage(element, x, y)
<head>
<style>
div { width: 200px; height: 200px; border: 1px solid; float: left; margin-right: 10px;}
</style>

<script>
  function dropset(event) {
    event.preventDefault();
    event.dataTransfer.dropEffect = "copy";
  }

  function drag(event) {
    event.dataTransfer.setData("Text", event.target.id);
    event.dataTransfer.effectAllowed = "copy";
    // cursor 변경
    var icon = document.createElement("img");
    icon.src = "mini.jpg";
    event.dataTransfer.setDragImage(icon, 0, 0);
  }

  function drop(event) {
    var data = event.dataTransfer.getData("Text");
    event.target.appendChild(document.getElementById(data));
    event.preventDefault();
    event.dataTransfer.dropEffect = "copy";
  }
</script>
</head>

<body>
  <div id="div1" ondrop="drop(event)" ondragover="dropset(event)">
    <img id="drag1" src="android.jpg" width="150" draggable="true" ondragstart="drag(event)">
  </div>
  <div id="div2" ondrop="drop(event)" ondragover="dropset(event)"></div>
</body>



V. 텍스트 편집
1. 편집 속성
     - 기존에 텍스트 편집이 불가능한 요소들까지 편집 가능 : contenteditale 속성, designMode 속성
<style type="text/css">  
div   { width: 700px; height: 200px; border: 1px solid; float: left; margin-right: 10px; }
input { width: 100px; height: 30px; }
</style>

<script>
  window.onload = function() {
    document.designMode = "off";    // designMode: 웹페이지 전체에 편집속성을 부여

    var editor = document.getElementById("editor");
    if (editor.isContentEditable) {
      editor.focus();
    }
  };

  function setBold() {
    // document.execCommand(commandId, showUI, value);
    // commandld : bold, italic,  subscript, superscript, createLink, delete, forwardDelete, formatBlock, insertImage, insertHTML, insertText, insertLineBreak(줄바꿈), insertOrderedList, insertUnorderedList, insertParagraph, undo, redo, selectAll, unlink, unselected, vendorID-customCommandID
    document.execCommand("bold");
  }
</script>
￼￼  
<div id="editor" contenteditable></div>  <!-- contenteditable 속성 부여 -->
<input type="button" value="굵게" onclick="setBold();">

2.  텍스트 선택
<style>  
div   { width: 700px; height: 200px; border: 1px solid; float: left; margin-right: 10px; }
input { width: 100px; height: 30px; }
</style>

<script>
window.onload = function() {
    var editor = document.getElementById("editor");
    if (editor.isContentEditable) {
      editor.focus();

      // 텍스트 선택 객체 생성 getSelection()
      var select = window.getSelection();

      // 선택 영역 지정 관련 메소드 : selectAllChildren(parentNode) 지정 노드 아래 자식요소 모두 선택, deleteFromDocument(), rangeCount(선택된 범위의 개수 반환), getRangeAt(index) 지정한 인수 번째의 선택 영역 반환, addRange(range), removeRange(range), removeAllRanges()
      select.collapse(editor.firstChild, 3);
      select.selectAllChildren(editor);

      // 마우스 커서 위치 지정 관련 메소드 : collapse(parentNode, offset) 지정한 요소안의 지정 위치로 커서 이동, collapseToStart() 선택된 문자열의 맨 앞으로 이동, collapseToEnd() 선택된 문자열의 맨 뒤로 이동, isCollapsed 선택여부
      select.collapseToEnd();
    }
  };
</script>
￼￼  
<div id="editor" contenteditable>텍스트 입력</div>  <!-- contenteditable 속성 부여 -->




VI. CSS3

1. CSS 개요
     - CSS(Cascading Style Sheets) : 웹문서에 스타일을 추가하는 간단한 메카니즘, http://www.w3schools.com/css
     - CSS 3 : 모듈화되어 부분적으로 Level 3 구현중, Selectors / Namespaces / Color 3, http://www.w3.org/Style/CSS
     - CSS 3 와 CSS 2 차이 http://naradesign.net/css3/documentation.html
     - CSS 2.1 http://www.w3.org/TR/CSS2 (번역 http://trio.co.kr/webrefer/css2/cover.html)
     - vendor prefix : -webkit-(chrome, safari), -moz-(firefox), -o-(opera), -ms-(i.e)

     1) CSS 사용의 장점
          - 문서 형식의 다양화
          - 다양한 기능의 확장
          - 통일된 문서 양식 제공, 로딩 시간 단축
          - 독립된 문서로 제작 가능

     2) CSS 기본구조
     

     3) CSS 적용방식 : 위치에 따라 구분
인라인(inline) 방식
각 요소안에 style 속성을 직접 적용
<body>
  <h1 style="font-size:30pt">CSS 적용</h1>
</body>
임베디드(embedded)/internal 방식
<head> 요소안에 style 요소를 사용하여 표현
(문서에 포함)
<head>  
  <style>   
    h1 { font-size: 30pt }   
  </style>
</head>
링크(link)/external 방식
외부에 css 파일을 별도로 만들고 <link> 요소를 통해 연결 (외부에 존재)
cf. <head> 요소안에 <style> 요소를 사용하여, @import url("path.css") 한 것과 동일한 결과이나 @import 비권장
<head>  
   <link rel="stylesheet" href="path.css">   
</head>

          - 동시에 선언되어 있을 경우, 우선순위 : 인라인 > 임베디드 > 링크 > HTML태그속성
          - 부모요소의 스타일은 기본적으로 하위요소로 상속 (전부 그런 것은 아니다)
          - 같은 요소에 다른 스타일을 순차적으로 중복적용 했을경우, 마지막 스타일을 적용한다
          - 중요도를 지정(!important)하여 최우선 적용할 수 있다, selector{property:value !important; }

2. 선택자 (단순선택자)
     

3. 조합자 : 요소의 계층구조와 문맥을 기반으로 하여 선택자를 조합선택하기위한 일종의 기호연산자
     “CSS그룹(,)은 하위( )조직 직원들의 직계자식(>)은 물론 더하여 인접(+)형제, 모든 일반(~)형제에게까지 보너스를 주었다"
     

4. 글꼴
     1) 글꼴 관련
     
     http://pxtoem.com

     2) 사용자 폰트 스타일
          - @font-face { font-family:글꼴이름 , src:경로}
          - 폰트 포맷 : ttf, otf, woff, eot(only IE), svg(not support IE, FF)

5. 텍스트
     

6. 배경
     

7. 색
     - 색상명 : red (http://www.w3schools.com/cssref/css_colornames.asp)
     - 16진수 색상코드 : #f00 (#ff0000)
     - RGB(255 | %) : rgb(255,0,0), rgb(100%,0%,0%)
     - RGBA(255 | %, Alpha 0~1) : rgba(255,0,0,1)
     - HSL (Hue(0~360), Saturate(%), Lightness(%) : hsl(0,100%,50%)
     - HSLA (Hue(0~360), Saturate(%), Lightness(%), Alpha)

8. 그라데이션
     - 브라우저마다 다름 : vendor prefix 필요
     - background: linear-gradient(direction, color-stop1, color-stop2, ⋯);
     - background: linear-gradient(angle, color-stop1, color-stop2);
     - background: radial-gradient(shape size at position, start-color, ⋯, last-color);
#grad {
  background: -webkit-linear-gradient(left top, red, blue); /* safari 5.1 to 6.0 */
  background: -moz-linear-gradient(bottom right, red, blue); /* firefox 3.6 to 15 */
  background: -o-linear-gradient(bottom right, red, blue); /* opera 11.1 to 12.0 */
  background: linear-gradient(to bottom right, red, blue); /* standard syntax */
  filter: progid: DXImageTransform.Microsoft.gradient(GradientType=0, startColorstr=#ff0000, endColorstr=#0000ff); /* i.e. 6-8 */
  -ms-filter: "progid: DXImageTransform.Microsoft.gradient(GradientType=0, startColorstr=#ff0000, endColorstr=#0000ff)”; /* i.e. 8-9 */;
}



9. 박스 모델
     
     - <div>는 독립된 박스 속성(줄바꿈이 됨)
     - <span> 은 인라인 박스 속성(줄바꿈이 안됨)
     
     
     - float : 부모요소 영역을 기준으로 왼쪽이나 오른쪽으로 배치 : none, left, right, page-floats
     - clear : float 해제 : none, left, right, both
     - position : 요소 박스의 배치 방식을 지정 : default static
          static : 일반적인 흐름에 따라 현재 위치에 배치, 별도의 위치 지정/변경 불가, top/left 속성값 무시
          relative : 일반적인 흐름에 따라 배치되지만, 본래 위치를 기준으로 지정한 위치만큼 이동하여 배치
          absolute : 일반적인 흐름에서 벗어나 지정한 위치만큼 이동하여 배치, 상위요소 중 relative/absolute/fixed 지정된 요소 중 가장 가까운 요소를 기준
          fixed : 뷰포트(viewport)를 기준으로 배치, 스크롤해도 움직이지 않는다
          sticky : 일반적인 흐름에 따라 배치되지만, 해당 요소 박스 흐름의 루트와 포함 블록에 대하여 상대적인 위치에 배치
          center : 상위요소를 기준으로 수평/수직 방향의 가운데로 배치
          page : 미디어가 page로 지정된 경우 페이지마다 동일한 영역에 배치

10. 유연한(플렉서블) 박스 레이아웃
     - flex-direction : 플렉스 컨테이너의 기본 축의 방향을 설정하여 플렉스 항목의 배치블 지정


11. CSS Gradient Button
     http://cssgradientbutton.com/css-button.php
http://editor.livegap.com/?fid=nv2negf91x939&pid=mx1znkbd42939


<!DOCTYPE html>
<html>
<head>
     <style type="text/css">
          .button_example {
               border:1px solid #CE9A01;
               -webkit-box-shadow:#FFF563 0 1px 0 inset;
               -moz-box-shadow:#FFF563 0 1px 0 inset;
               box-shadow:#FFF563 0 1px 0 inset;
               -webkit-border-radius:10px;
               -moz-border-radius:10px;
               border-radius:10px;
               font-family:arial, helvetica, sans-serif;
               padding:7px 14px 7px 14px;
               text-decoration:none;
               display:inline-block;
               text-shadow:0 1px 0 rgba(255, 255, 255, 0.44);
               font-weight:bold;
               color:#63460C;
               background-color:#FFD65E;
               background-image:-webkit-gradient(linear, left top, left bottom, from(#FFD65E), to(#FEBF04));
               background-image:-webkit-linear-gradient(top, #FFD65E, #FEBF04);
               background-image:-moz-linear-gradient(top, #FFD65E, #FEBF04);
               background-image:-ms-linear-gradient(top, #FFD65E, #FEBF04);
               background-image:-o-linear-gradient(top, #FFD65E, #FEBF04);
               background-image:linear-gradient(to bottom, #FFD65E, #FEBF04);
               filter:progid: DXImageTransform.Microsoft.gradient(GradientType=0, startColorstr=#FFD65E, endColorstr=#FEBF04);
          }
          .button_example:hover{
               border:1px solid #CE9A01;
               background-color:#FFC92B;
               background-image:-webkit-gradient(linear, left top, left bottom, from(#FFC92B), to(#CE9A01));
               background-image:-webkit-linear-gradient(top, #FFC92B, #CE9A01);
               background-image:-moz-linear-gradient(top, #FFC92B, #CE9A01);
               background-image:-ms-linear-gradient(top, #FFC92B, #CE9A01);
               background-image:-o-linear-gradient(top, #FFC92B, #CE9A01);
               background-image:linear-gradient(to bottom, #FFC92B, #CE9A01);
               filter:progid: DXImageTransform.Microsoft.gradient(GradientType=0, startColorstr=#FFC92B, endColorstr=#CE9A01);
          }
     </style>
</head>

<body>
     <a class="button_example" href="#">PREVIEW BUTTON</a>
</body>
</html>


12. 다단
     


13. 애니메이션
     1) 트랜지션(transition, 변화)
     
div {
     width:150px;
     height:100px;
     background:orange;
     -webkit-transition-property:width;
     -webkit-transition-duration:2s;
     -webkit-transition-timing-function:ease-in;
     -webkit-transition-delay:1s;
     /* -webkit-transition: width 2s ease-in 1s */;
}
div:hover{
     width:300px;
}

     2) 트랜스폼(transform, 변형)
     

     3) 애니메이션(naimation)
          ➀ keyframes
               - keyframes animationname { from { } to { } }
               - keyframes animationname { 0% { } 50% { } 100% { } }
          ➁ animation 속성
          


14. 미디어 쿼리(media query)
     - @media type [and (조건)], type [and (조건)] { }
     - media type : all, print, screen, aural(음성장치), braille(점자장치), handheld(휴대장치), projection, tty(텔렉스,터미널), tv, embossed
     - 조건 (미디어를 구분하기 위한 조건)
     


VII. 캔버스
     - 해상도에 의존하는 비트맵 캔버스(그래프, 게임그래픽, 기타 비주얼 이미지)와 스크립트를 제공
     - 지원 체크 : if (canvas.getContext) { } 
     - canvas요소가 지원되지 않는 경우 폴백 컨텐츠(fallback content)를 나타내어 준다
     - 그리기 방법
          ➀ 그림영역을 지정 : id, width, height
          ➁ 자바스크립트 : 객체 생성, 컨텍스트 생성, 그리기 메소드 및 속성을 사용


<script>
function drawCanvas() {

    // 캔버스 객체 생성  
    var canvas = document.getElementById('canvas');  
    // 그리기 컨텍스트 생성  
    var context = canvas.getContext('2d');
    // var context = document.getElementById('canvas').getContext('2d');


    // 그리기 작업 : canvas 영역내 좌표는 좌상단이 (0,0)이다
    // 사각형
    context.strokeRect(x, y, width, height); // 테두리만 있는 사각형
    context.fillRect(x, y, width, height);   // 채워진 사각형
    context.clearRect(x, y, width, height);  // 사각형 모양으로 지우기

    // 선, 다각형
    // 선으로 이동(moveTo)하고 라인긋고(lineTo) 출력(stroke)한다. 채우고(filee) 닫기도(closePath) 한다
    context.beginPath();    // 패스 지정 초기화
    context.moveTo(x0, y0); // 시작점 지정 (이동)
    context.lineTo(x1, y1); // 지정 위치까지 선을 그음
    context.closePath();    // 패스를 닫음 (종료점과 시작점을 자동으로 연결)
    context.stroke();       // 이전 lineTo()로 그은 선들을 출력
    context.fill();         // 혹은 채우기

    // 원
    
    // 중심좌표로 이동후, 반지름만큼 벌리고,
    // 원의 가장 오른쪽이 0, 시계방향으로 각도 * Math.PI / 180, 그리는 방향은 시계방향이 false
    // 180 * Math.PI / 180은 == 1 * Math.PI로 표현 할 수 있다

    context.beginPath(); // 패스 지정 초기화
    context.arc(x, y, r, sAngle, eAngle, (counter-)clockwise);  // x, y, 반지름(radius), 시작각도, 종료각도, 회전방향(default false: clockwise)
    context.stroke();    // 이전 arc()로 그은 선들을 출력
    context.fill();      // 혹은 채우기


    // 직선과 접하는 원호
    
    context.beginPath();              // 패스 지정 초기화
    context.moveTo(x0, y0);           // 시작점 지정 (이동)
    context.arcTo(x1, y1, x2, y2, r); // 제1점과 제2점을 향해 그리다 반지름만큼 원호를 그린다
    context.stroke();                 // 이전 arcTo()로 그은 선들을 출력
    context.fill();                   // 혹은 채우기

    // 베지에 곡선(bezier curve) : n개의 점을 기준으로 만들 수 있는 (n-1)차 곡선
    // 2차 베지에 곡선
    context.beginPath();    // 패스 지정 초기화
    context.moveTo(x0, y0); // 시작점 지정 (이동)
    context.quadraticCurveTo(cpx, cpy, x, y);             // 제어점과 종료점으로 곡선을 그린다
    context.stroke();       // 이전 quadraticCurveTo()로 그은 선들을 출력
    // 3차 베지에 곡선
    context.beginPath();    // 패스 지정 초기화
    context.moveTo(x0, y0); // 시작점 지정 (이동)
    context.bezierCurveTo(cp1x, cp1y, cp2x, cp2y, x, y);   // 제어점 2개와 종료점으로 곡선을 그린다
    context.stroke();       // 이전 bezierCurveTo()로 그은 선들을 출력


    // 선 스타일 속성
    context.lineWidth = 5;       // 선 두께 (default 1.0)
    context.lineCap = 'butt';    // 선 끝부분 스타일 : butt, round, square (default butt)
    context.lineJoin = 'miter';  // 선 꺾이는 부분 스타일 : miter, bevel, round (default miter)
    context.strokeStyle = 'red'; // 선 컬러 : '색이름', '색상코드', RGB, RGBA [주의] not lineStyle !

    // 채우기 스타일 속성
    context.fillStyle = rgb(255, 0, 0); // 채우기 색
    context.globalAlpha = 0.5;         // 채우기 색의 투명도(0~1)

    // 그라데이션 속성
    var gradient = context.createLinearGradient(x1, y1, x2, y2);          // 선형 그라데이션
    var gradient = context.createRadialGradient(x1, y1, r1, x2, y2, r2);  // 원형 그라데이션
    gradient.addColorStop(offsets, color);                                // 그라데이션 경계색 지정 (오프셋 0~1, 색)
    context.fillStyle = gradient;

    // 그림자 스타일 속성
    context.shadowColor = #ff0000; // 그림자 색 (default 투명)
    context.shadowOffsetX = 0;     // 대상을 기준으로 그림자의 x좌표 (default 0)
    context.shadowOffsetY = 0;     // 대상을 기준으로 그림자의 y좌표 (default 0)
    context.shadowBlur = 0;        // 그림자 흐린 정도, 숫자 클수록 흐림 (default 0)


    // 도형 합성
    // 먼저 그린 도형과 나중 그릴 도형의 사이에서 정의
    context.globalCompositeOperation = 'source-over';
    // https://developer.mozilla.org/ko/docs/Web/HTML/Canvas/Tutorial/Compositing
    

    // 텍스트 삽입
    // 글자스타일, 글자변형, 글자두께, 글자크기, 글꼴,… (default 10px sans-serif)
    context.font = 'font-style font-variant font-weight font-size font-family [caption icon ...]';
    context.font = 'italic normal bolder 12pt arial';
    // 가로 방향의 정렬 : start, end, center, left, right (default start)
    context.textAlign = 'start';
    // 기준선 : alphabetic, top, hanging, middle, ideographic, bottom (default alphabetic)
    context.textBaseline = 'alphabetic';
    context.fillText(text, x, y [,maxWidth]);   // 텍스트 삽입
    context.strokeText(text, x, y [,maxWidth]); // 아웃라인 텍스트 삽입

    // 이미지 삽입
    var img = new Image();
    img.src = 'image.jpg';
    context.drawImage(img, dx, dy);
    context.drawImage(img, dx, dy, dw, dh);                 // 이미지를 지정 크기로 삽입
    context.drawImage(img, sx, sy, sw, sh, dx, dy, dw, dh); // 소스가 되는 이미지를 일부를 잘라내어 삽입

    // 이미지 패턴
    var img = new Image();
    img.src = 'image.jpg';
    // 반복형식 : repeat, repeat-x, repeat-y, no-repeat (default repeat)
    var pattern = context.createPattern(img, repeat);
    context.fillStyle = pattern;

    // 도형 변환
    scale()
    rotate()
    translate()
    transform()
    [주의] not skew() !
}
</script>  

<body onLoad="drawCanvas();">  
    <canvas id="canvas" width="500" height="500">  
        이 브라우저는 HTML5의 canvas 요소를 지원하지 않습니다.  
    </canvas>  
</body>
http://cheatsheetworld.com/programming/html5-canvas-cheat-sheet/



VIII. 오디오와 비디오
1. <embed>
     - 오래전부터 지원은 해왔으나 html 4.01 명세에는 없었다. 그래서 html 5에 신규로 생긴 요소
<embed type="video/quicktime" src="movie.mov" width="640" height="480">

2. <audio>
     - <audio>의 속성 : src(파일경로), [controls(콘트롤러), loop(반복), autoplay(자동재생), muted(음소거), preload(로드설정 : none, auto, meta)]
     - <source> 요소의 속성 : src(파일경로), type(미디어종류), media(미디어쿼리)
<audio controls>
    <source src="audio.ogg" type="audio/ogg"> <!-- not support ogg: IE, Safari -->
    <source src="audio.mp3" type="audio/mpeg">
    <source src="audio.wav" type="audio/wav"> <!-- not support ogg: IE -->
    Your browser does not support the audio tag.
</audio>

3. <video>
     - <video>의 속성 : src, width, height, controls, loop, autoplay, muted, preload(: none, auto, meta), poster(스냅샷)
     - <source> 요소의 속성 : src(;코덱), type, media
     - <track> 요소
     - codecs : http://www.w3.org/TR/html5/embedded-content-0.html#the-source-element
<video width="640" height="480" controls poster="">  
    <source src="movie.ogg" type="video/ogg; codecs='theora, vorbis'"> <!-- Theora and Vorbis, Not support ogg: IE, Safari -->
    <source src="movie.mp4" type="video/mp4;codecs='avc1.42E01E, mp4a.40.2'"> <!-- H.264 and AAC -->
    <source src="movie.webm" type="video/webm;codecs='vp8, vorbis'"> <!-- VP8/9 and Vorbis, Not support webm: IE, Safari -->
    <track src="devstories-en.vtt" label="English subtitles" kind="subtitles" srclang="en" default>
    Your browser does not support the video tag.
</video>

4. 미디어 파일의 제어 : 자바스크립트
<script>  
    // 객체 생성  
    var video = document.getElementById("video");

    // 상태관련 속성
    // src(파일경로), currentSrc(재생중인 파일경로), currentTime(재생위치,초), duration(총시간,초), paused(일시정지상태 여부), defaultPlaybackRate(기본재생속도), playbackRate(재생속도), ended(종료상태 여부)
    // autoplay(자동재생), loop(반복), controls(콘트롤러), volumn(소리크기 값), muted(음소거상태 여부)  
    // error(에러 : 1(MEDIA_ERR_ABORTED:사용자에의한 중지), 2(MEDIA_ERR_NETWORK:네트워크에러), 3(MEDIA_ERR_DECODE:디코딩실패), 4(MEDIA_ERR_SRC_NOT_SUPPORT:미지원 형식))   
    // networkState(접속 상태 : 0(NETWORK_EMPTY:초기상태), 1(NETWORK_IDLE:접속직전), 2(NETWORK_LOADING:로딩중), 3(NETWORK_LOADED:로드완료), 4(NETWORK_NO_SOURCE:미지원형식이라 로드불가))  
    // readState(다운로드 상태 : 0(HAVE_NOTHING:다운로드 하지않음), 1(HAVE_METADATA:메타데이터 다운로드 완료), 2(HAVE_CURRENT_DATA:현재 재생위치까지 다운로드 완료), 3(HAVE_FUTURE_DATA:재생위치에서 조금더 재생할 만큼 다운로드 완료))
    function play() {
        // 미디어 파일 재생/멈춤
        if (video.paused)
        video.play();
        else
        video.pause();
    }

    // 이벤트 리스너
    // element.addEventListener(event, function[, useCapture]);
    // 이벤트 : play(재생할때), timeupdate(재생중 매프레임마다), waiting(다음 프레임 로딩 대기중일때), ended(종료일때), progress(로딩중일때), loadstart(로딩시작했을때), load(로딩완료되었을때), error(에러일때) [주의] not stop()!
    video.addEventListener("error", function(err){
        errMessage(err);
    }, true);
    video.addEventListener("timeupdate", playTime, false);
    video.addEventListener("ended", playEnd, false);

    function errMessage(msg) {
        alert("에러가 발생하였습니다.(에러코드:" + msg);
    }

    function playTime(e) {
        document.getElementById("playtime").innerHTML = "재생 상태 : " + Math.floor(video.currentTime) + "/" + Math.floor(video.duration)
    }

    function playEnd(e) {
        alert("미디어 재생이 완료되었습니다.");
    }
</script>

<video id="video" width="640" height="480" controls>
    <source src="movie.ogg; codecs='theora, vorbis'" type="video/ogg">
    <source src="movie.mp4; codecs='avc1.42E01E, mp4a40.2'" type="video/mp4">
    <embed src="movie.wav"></embed>
</video>


<!-- 재생 버튼 생성 -->
<input type="button" value="재생" onclick="play();">
<!-- 이벤트 예제 -->
<div id="playtime"></div>



IX. 파일 접근
1. 파일 접근
     1) 파일 접근 개요
          - 파일의 데이터에 대한 직접 읽기 가능 (읽기 전용)
          - 드래그앤드롭의 드롭 파일, input type=“file”의 change 파일
          - 선택한 파일의 객체를 구해 속성/메소드 사용
     2) 파일 메소드
          - name : 파일 이름
          - type : 파일 속성 (MIME 타입 | null)
          - size : 파일 크기
          - lastModifiedDate : 수정된 시간
          - slice(start, length) : 필요한 만큼 내용을 잘라 새로운 Blob 객체를 만듬
     3) 파일 내용 읽기 메소드
          - var reader = new FileReader(); // 파일리더 객체 생성
          - readAsBinaryString(file)
          - readAsText(file, encoding) : default “utf-8"
          - readAsDataURL(file)
          - abort( ) : 파일 읽기 중지
          - result : 읽어 들인 파일 내용
          - onload : 읽기 성공
          - onprogress : 읽는중
          - onerror : 오류
               1 : NOT_FOUND_ERR : 읽을 파일을 찾지 못할때
               2 : SECURITY_ERR : 보안상 안전하지 못할때, 파일 선택후 파일에 변경이 있을때
               3 : ABORT_ERR : 읽기 중지되었을때
               4 : NOT_READABLE_ERR : 권한 등으로 인해 파일에 접근하지 못할때
               5 : ENCODING_ERR : Data URL 길이가 초과했을때

2. 오프라인 접근
     1) 오프라인 접근 개요
          - 오프라인에서도 사용 가능한 어플리케이션
          - 클라이언트에서 웹페이지와 파일들을 캐시로 저장
     2) 웹서버 mime.type 파일 설정
          - text/cache-manifest manifest
     3) HTML 페이지 설정
          <html manifest=“cache.manifest">
          - [주의] not 따로 CACHE 섹션에 페이지 이름을 입력해야된다 !
     4) 매니페스트 파일
          - 어떠한 파일을 캐시로 저장해야 하는지를 지정한 파일 (*.manifest)
CACHE MANIFEST
# Cache Section : 캐시되어야할 파일, 오프라인 접근 가능
CACHE:
news.html
news.js
news.css
image.jpg

# Network Section : 온라인 접근만 가능
NETWORK:
new_news.html
image_check.jpg
￼
# Fallback Section : 페이지가 존재하지 않을때 표시할 대체 리소스 지정
FALLBACK:
./news
image_notice.jpg

     5) applicationCache 객체
          - status : 상태
               0 : UNCACHE : 캐시하지 않음
               1 : IDLE : 최신 캐시 이용 상태
               2 : CHECKING : 업데이트 체크 중
               3 : DOWNLODING : 업데이트 다운로드 중
               4 : UPDATEREADY : 최신 캐시를 이용할 수 있음
               5 : OBSOLETE : 에러에 의한 캐시 무효화
          - update() 
          - swapCache()
          - 이벤트
               checking : 업데이트 체크 중
               error : 오류
               noupdate : 업데이트 되지 않음
               downloading :  업데이트 중
               process : 업데이트 중
               updateready : 최신 캐시 얻기 완료
               cached : 캐시 완료
               obsolete : 캐시 무효



X. 웹스토리지
1. 웹스토리지
     1) 로컬스토리지 (local storage)
          - 클라이언트에 간단한 정보를 저장하기 위한 저장 영역
          - 저장용량/유효기간 무한, 도메인 종속
          - 쿠키(cookie) : 저장용량 5KB, 유효기간 존재

     2) 로컬스토리지 메소드
          - length : 저장되어있는 데이터 수 반환
          - key(index) : 인덱스를 지정하여 키 얻음
          - getItem(key) : 키에 대응하는 값 얻음
          - setItem(key, data) : 데이터 저장
          - removeItem(key) : 값 삭제
          - clear : 전체 데이터 삭제 
<script type="text/javascript">
window.onload = function() {
    // 브라우저의 로컬 스토리지 지원 여부
    if (window.localStorage) {
      // 데이터 저장 방법 (3개 동일)
      localStorage.setItem("computer", "programming");
      localStorage["computer"] = "programming";
      localStorage.computer = "programming";
    }￼
  };
</script>

     3) 세션스토리지 (session storage)
          - 저장기간 유한, 세션 종료시 폐기
          - 세션별 종속
          - 로컬스토리지 메소드와 동일
          - sessionStorage.setItem(key, data);

2. 웹 데이터베이스
     1) 웹데이터베이스
          - 추가적인 시스템없이 DB 생성, SQL 사용 가능
     2) 웹데이터베이스 메소드
          - openDatabase(name, version, displayName, estimateSize) : 저장공간 생성
          - db.transaction(callback, errorCallback, successCallback) : 데이터베이스 접근
          - tx.executeSql(sql, args, callback, errorCallback) : SQL 실행
     3) SQL질의어
          - create table ~ ;
          - select ~ from tbl where ~ ;
          - insert into tbl value ( ) ;
          - update tbl set ~ ;
          - delete from tbl where ~ ;
     4) SQLResultSet형 객체관련 속성
          - insertId : insert문을 실행하여 생성된 ID
          - rowAffected : SQL 실행에 의해 처리된 레코드 수
          - rows : SELECT문을 실행한 결과: length, item(index)
<script>  
    window.onload = function() {
     var db = openDatabase("movie", "1.0", "movie database", 1024 * 1024);
      db.transaction(exeCreate);
    }

    function exeCreate(tx) {
     tx.executeSql("create table movie(name, actor)");
    }  

    function insertData() {
     db.transaction(exeInsert);
    }

    function exeInsert(tx) {
        tx.executeSql("insert into movie values(?,?)", [movie.value, actor.value]);
    }  

    function viewData() {
     db.transaction(exeSelect);
    }

    function exeSelect(tx) {
        tx.executeSql("select * from movie", [], viewTable);
    }

    function viewTable(tx, rs) {
        for (var i = 0; i < rs.rows.length; i++) {
        var row = rs.rows.item(i);
        document.getElementById("table").innerHTML += "<tr><td>" + row["name"] + "</td><td>" + row["actor"] + "</td></tr>";
        }
    }
</script>

<body>
    movie: <input type="text" id="movie">
    actor: <input type="text" id="actor">
    <input type="button" onclick="insertData()" value="저장">
    <input type="button" onclick="viewData()" value="조회">
    <hr>
    <table id="table">
    </table>
</body>



XI. 웹워커
1. 웹워커
     1) 웹워커 개요
          - 멀티스레드 : 하나의 응용프로그램이 스레드라는 처리단위를 복수 생성하여 동시에 병행처리하는 것
          - 웹브라우저는 본래 싱글스레드
          - 메인에서 동작하는 UI스레드와는 별개로 백그라운드에서 여러 개의 워커들이 각각의 기능을 처리하는 형태
     2) 웹워커 객체 생성 및 종료
          - 일감은 별도의 js파일로 존재
          - var worker = new Worker(“calc.js”);
          - worker.terminate( );
     3) 웹워커의 메세지 전달
          - 워커에서 생성한 데이터는 외부에서 호출 불가능(캡슐화)
          - postMessage(data) : 송신
          - onmessage(event) : 수신
          - onerror(event) : 에러

2. 공유워커
     1) 공유워커 개요
          - 여러 개의 워커 객체가 하나의 백그라운드 프로세스를 공유해서 사용
     2) 공유워커 객체 생성
          - 같은 이름의 자바스크립트 파일명과 워커 이름을 사용
          - var worker1 = new ShareWorker(“sharecalc.js”, “share”);
     3) 공유워커의 메세지 전달
          - port 속성 : 일종의 채널개념으로 메인 UI 스레드에서 port 사용
          - var port = event.ports[0]; // 채널 1개
          - port.postMessage(data) : 송신
          - post.terminate() : 종료
          - onconnect(event) : 이벤트 핸들러
          - post.onmessage(event) : 수신
          - post.onerror(event) : 에러

3. 웹소켓
     1) 웹소켓 개요
          - 소켓(socket) : 서버와 클라이언트간 특정포트를 통한 양방향 통신 소프트웨어 장치
          - 웹소켓 : TCP라인을 통해 HTML에서 연결지향 양방향 전이중(duplex) 통신 가능
     2) 웹소켓 클라이언트 구현 (메소드)
          - 프로토콜 : ws://, 보안접속 wss://
          - var socket = new WebSocket(“ws://localhost:8080”); // 웹소켓 객체 생성
          - send(data) : 송신
          - onopen(event) : 연결
          - onclose(event) : 종료
          - onmessage(event) : 수신
          - [주의] not onconnect !
     3) 웹소켓 서버
          - 기존 TCP 서버 이용 불가
          - 파이썬 pywebsocket https://code.google.com/p/pywebsocket/
          - PHP phpwebsocket https://code.google.com/p/phpwebsocket/
          - Java jWebSocket http://jwebsocket.org
          - 루비 web-socket-ruby https://github.com/gimite/web-socket-ruby
          - 자바스크립트 Socket.IO http://socket.io



XII. 위치정보
1. Geolocation API
     - GPS가 내장된 스마트폰에서 정확한 위치 정보 파악이 가능
     1) 현재위치 객체
          - navigator.geolocation.getCurrentPosition(successCallback, errorCallback, options)
          - clearPosition() : 종료
          ➀ 위치 정보 속성 (첫번째 인자)
               - coords.latitude : 위도
               - coords.longitude : 경도
               - coords.altitude : 표고
               - coords.accuracy : 위도, 경도의 오차
               - coords.altitudeAccuracy : 표고의 오차
               - coords.heading : 디바이스 진행방향 (North 기준 시계방향의 각도)
               - coords.speed : 디바이스의 진행속도(m/s)
               - timestamp : 위치정보를 얻은 시각 (1970.1.1일이후 ms)
          ➁ 오류 속성 (두번째 인자)
               - code : 오류 코드
                    0 : UNKOWN_ERROR : 알수없는 오류
                    1 : PERMISSION_DENIED : 권한 없음
                    2 : POSITION_UNAVALABLE : 위치 알수 없음
                    3 : TIMEOUT : 시간제한 초과
               - message : 오류 메세지
          ➂ 지정 옵션 속성 (세번째 인자)
               - enableHighAccuracy : 정확도 높은 위치 정보 요청
               - timeout : 시간제한 설정(ms)
               - maximumAge : 정보 유효기간(ms), 0이면 항상 새 위치 정보 요청

     2) 현재위치 추적
          - navigator.geolocation.watchPosition(successCallback, errorCallback, options)
          - clearPosition() : 종료
          - getCurrentPosition 메세드와 동일

2. 지도 서비스 API
     - Google https://developers.google.com/maps/?hl=ko
     - Bing http://www.microsoft.com/maps/choose-your-bing-maps-API.aspx
     - Naver http://developer.naver.com/wiki/pages/MapAPI
     - Daum http://apis.map.daum.net




HTML
http://www.w3.org/TR/html5/
http://html5.clearboth.org/spec (번역)
http://www.w3.org/TR/html5-diff/
http://channy.creation.net/project/html5/html4-differences/ (번역)
http://dev.w3.org/html5/html-design-principles/
http://www.whatwg.org/html/
웹개발 입문부터 응용까지 http://div.or.kr
HTML5 오픈 레퍼런스 http://html5ref.clearboth.org/
HTML5 가이드 (한국웹표준커뮤니티) http://html5.creation.net/html5-guide.pdf
HTML 웹개발의 기초와 핵심역량 A to Z https://www.appvillage.or.kr/jsp/developInfo/movieEduList.jsp
Head Tags http://gethead.info/
HTML5rocks https://www.html5rocks.com/en/tutorials

CSS
Normalize.css https://necolas.github.io/normalize.css/
당신은 모를 수도 있는 CSS의 7가지 단위 https://webdesign.tutsplus.com/ko/articles/7-css-units-you-might-not-know-about--cms-22573
최고의 CSS 중앙정렬 기법https://webdesign.tutsplus.com/ko/tutorials/the-holy-grail-of-css-centering--cms-22114
모든 디자이너와 프런트 개발자가 숙달하고 있어야할 CSS 스니핏 50https://nolboo.kim/blog/2013/07/22/50-useful-css-snippets/
CSS Tricks https://css-tricks.com/

CSS Formatter
Online Code Beautifier (Indent with 2 spaces) http://jsbeautifier.org
Online Syntax Highlighter (xml, convert whitespace) http://puzzleware.net/CodeHtmler
Online CSS Formatter (compress, no options) http://teenage.cz/acidofil/tools/cssformat.php
Online CSS Beautifier (Break multiple selector, Space after, Compact line break) http://mini-web-tools.googlecode.com/svn/p/css-compressor-and-beautifier.html

Online Live Editor
http://jsbin.com
http://codepen.io/pen
http://editor.livegap.com
http://jsfiddle.net
http://liveweave.com
http://dabblet.com
http://codemagic.gr
http://thecodeplayer.com

Templates
https://html5up.net
https://freehtml5.co
http://flypixel.com/site-templates
https://onepagelove.com
https://templated.co
http://www.os-templates.com
https://shapebootstrap.net
https://wrapbootstrap.com

Web Awards
http://www.awwwards.com
https://thefwa.com
http://www.csswinner.com
http://www.cssdesignawards.com
http://dbcut.com/bbs/index.php
