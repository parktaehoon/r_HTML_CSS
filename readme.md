# HTML & CSS 웹사이트 개발과 디자인 기초 복습

## HTML

### text
- addr
- address
- bold
- cite
- dfn
- strong & em
- hr
- ins & del
- i
- br
- blockquote & q
- s
- sup & sub

### list
- ol>li
- ul>li

### link
- a herf="mailto:xxx@xx.com or website 주소 or 경로(../....../xxx.html)
- h1 id="top" => a herf="#top"
- target="_blank"

### image
- img src="경로" alt"quokka"

### table
- tr
- th
- td (colspan, rowspan)
- 구조 (thead, tbody, tfoot)

### form
- form => get, post
- input => text, password, radio, checkbox, file, email, image, submit, email, url, search
- input (checked="checked", required="required", placehold="키워드 입력")
- textarea
- select>option (multiple="multiple", select="selected)
- label (for, id)
- fieldset>legend

### 추가 마크업
- div [id, class(CSS)] 큰 묶음
- span [class(CSS)] 작은 묶음

### 확장 문자
- < = &lt;
- > = &gt;
- & = &amp;
- " = &quot;
- 저작권 = &copy;
- 등록상표 = &reg;
- 상표 = &trade;
- ' = &lsquo;
- ' = &rsquo;
- " = &ldquo;
- " = &rdquo;
- x = &times;
- / = &divide;

### video
- video src
- poster (사전 이미지)
- width, height
- preload, none, auto, metadata
- controls
- autoplay, loop

## CSS

### css 연결
- style type="text/css" 같은 문서내에
- link rel="stylesheet" href="경로" type="text/css" 다른 위치에
- class = ccs 연결할 것들.

### color
- color : 글자색
- background-color: rgb(opacity) or rgba, hls or hlsa

### font
- ascender, cap height, x-height, baseline, descender
- font-family : 글자체
- font-size : 글자사이즈 (px, em, %)
- font-face : 글자체 다운로드
- font-weight : 굵은 글자 (none, bold)
- font-style : 기울임꼴 (nomal, italic, oblique)
- text-transform : 대소문자 (uppercase, lowcase, capitalize)
- text-decoration : 밑줄 & 취소선 (none, underline, overline, line-through, blink)
- line-height : 리딩-줄 간격 (권장 : 1.4em ~ 1.5em)
- letter-spacing : 글자 간격
- word-spacing : 단어 간격
- text-align : 정렬 (lefr, right, center, justify)
- text-indent : 들여쓰기
- text-shadow : 그림자 (가로, 세로, 번짐, 색상)
- p.xxx:hover, active, focus : 사용자에 대한 반응....
  
### box
- width, height
- overflow : hidden or scroll
- border : 두께 선종류(solid, dotted, dashed, double, groove, ridge, inset, outset) 색상;
- margin : 10px auto 10px auto;
- display : inline, block, inline-block, none;
- visibility : hidden;
- box-shadow: 수평거리 수직거리 번짐거리 확장거리 색상;
- border-radius: top right bottom left;

### list, table, form
- list-style-type: decimal, decimal-leading-zero, lower-alpah, upper-alpha, lower-roman, upper-roman;
- list-style: inside circle;
- CCS - table properties : width, padding, text-transform, letter-spacing, font-size, border, text-align, background-color, :hover
- empty-cells : show or hide or inherit
- border-spacing or border-collapse
- cursor