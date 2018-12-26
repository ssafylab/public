---
permalink: /Markdown-Table/
title: "Markdown Syntax"
---

Markdown 문서를 작성하는 데에 필요한 문법은 [GitHub Help](https://help.github.com/articles/basic-writing-and-formatting-syntax/)에서 자세히 볼 수 있습니다.
여기서는 주로 사용되는 것들을 표로 간단히 소개하니, 더 알아보고 싶다면 위 링크를 참조해 주세요.

## Text

|Syntax|Description|Example|
|------|-----------|-------|
|\<h1\> ~ \<h6\>|제목|\<h1\> Hello, SSAFY!|
|# ~ ######|제목|\# Hello, SSAFY!|
|\*text\*|이탤릭체|SSAFY는 Samsung SW Academy for Youth의 \*줄임말\*입니다.|
|\*\*text\*\*|강조|\*\*절대\*\* 지각하지 말아 주세요!!|
|\~\~text\~\~|취소선|오늘 오후 수업을 특별히 \~\~13시\~\~ 14시부터 시작하겠습니다.|
|\>|인용|드디어 메일을 받았습니다.<br>\>"합격입니다."|
|\ |특수기호 사용|별표(\\\*)를 2개 사용해 글자를 강조할 수 있습니다.|

## Paragraph

|Syntax|Description|Example|
|------|-----------|-------|
|빈줄|새 문단||
|\-\-\-|구분선(새 페이지)||

## List

|Syntax|Description|Example|
|------|-----------|-------|
|1. 2. 3. |순번이 있는 목록|1. Language<br>2. Algorithm<br>3. Project|
|\* \-|순번 없는 목록|\*Ground Rule<br>  \-Don't be late.|
|\-[ ] \-[x]|체크리스트| \-[ ] not done<br>\-[x] done|

## Code

|Syntax|Description|Example|
|------|-----------|-------|
|\`code\` |중간 삽입|파이썬이 처음이라면 \`print('Hello, World')\`부터 해봅시다.|
|\`\`\`<br>code<br>\`\`\`|텍스트 박스|이번엔 다음과 같이 해볼까요?<br>\`\`\`<br>for i in range(0, 10):<br>&nbsp;&nbsp;print('Hello, Workld')<br>\`\`\`|
|\`\`\`python<br>code<br>\`\`\`|텍스트 박스(특정 언어 스타일)|이번엔 다음과 같이 해볼까요?<br>\`\`\`<br>for i in range(0, 10):<br>&nbsp;&nbsp;print('Hello, World')<br>\`\`\`|

# Insert

|Syntax|Description|Example|
|------|-----------|-------|
|\[text](address)|링크|\[Go to SSAFY](edu.ssafy.com)|
|\!\[text](address)|이미지|\!\[SSAFY Image](https://edu.ssafy.com/asset/images/logo.png)|
| \- \|| 테이블(표)|\|Name\|Speciality\|<br>\|\-\-\-\-\-\-\|\-\-\-\-\-\-\-\-\-\-\|<br>\|John\|Java\|<br>\|Peter\|Python\|
