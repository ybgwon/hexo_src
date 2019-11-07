---
title: markdown 문법
date: 2019-11-07 03:05:47
tags: markdown
---

Emacs 마크다운 사용법
=====================

C-c C-s 키를 누르면 미니버퍼에 사용가능한 키들이 표시된다.
주로 styling text 관련 키들이 표시되고 command 관련 키들은
C-c C-c 명령에 의해 표시된다.

링크와 이미지 삽입
------------------

C-c C-l, C-c C-i 키 사용

- link

``` markdown
1. [google](http://www.google.com)
2. <http://www.daum.net>
3. [참조링크][1]
```

1. [google](http://www.google.com)
2. <http://www.daum.net>
3. [참조링크][1]

- image

``` markdown
1. 절대 경로
![cat](https://ybgwon.github.io/images/cat.jpg)
2. 상대 경로
![cat](/images/cat.jpg)
3. 이미지에 링크
[![naver](/images/cat.jpg)](http://www.naver.com)
```

1. ![cat](https://ybgwon.github.io/images/cat.jpg)
2. ![cat](/images/cat.jpg)
3. [![naver](/images/cat.jpg)](http://www.naver.com)

코드
----

1. inline

``` markdown
이것은 인라인 코드 `code` 예입니다.
```

이것은 인라인 코드 `code` 예입니다.

2. block

<pre>

```
s = "Python syntax highlighting"
print s
```

</pre>

``` python
s = "Python syntax highlighting"
print s
```

링크
----

<https://heropy.blog/2017/09/30/markdown/>

<https://gist.github.com/ihoneymon/652be052a0727ad59601>

<https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet>
