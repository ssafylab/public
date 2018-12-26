---
permalink: /GitPitch-Table/
title: "GitPitch Syntax"
---

GitPitch는 프레젠테이션에 최적화할 수 있도록 일반적으로 쓰이는 Markdown 문법 외에 특별한 문법을 추가로 지원하며, CSS를 활용하여 디자인할 수도 있습니다.
또한 여러가지 템플릿을 제공하고 있으며 [GitPitch Docs](https://help.github.com/articles/basic-writing-and-formatting-syntax/)를 통해 가이드하고 있습니다.
여기에서는 GitPitch 문서에서 사용할 만한 기본적인 것들만 소개하고 있으니, 자세한 사용 방법을 알고 싶다면 위 링크를 참조해 주세요.

|Syntax|Description|Example|
|------|-----------|-------|
|\-\-\-|새 페이지(가로)|\-\-\-<br>슬라이드1<br>\-\-\-<br>슬라이드2|
|\+\+\+|새 페이지(세로)|\+\+\+<br>슬라이드1<br>\+\+\+<br>슬라이드2|
|@title\[text]|페이지 제목|@title\[슬라이드1]|
|@size\[값](text)|글자 크기|@size\[2.0em](안녕)하세요!|
|@coloor\[값]|글자 색상|@color\[red](빨강), @color\[green](초록), @color\[#0000ff](파랑)|
|@transition\[type]|페이지 전환 효과|@transition\[fade-in]|
|@snap\[값]<br>text<br>\@snapend|레이아웃 설정|@snap\[south]<br>footer<br>@snapend|
