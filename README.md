# 사이트 테스트 방법


## 쉘 코드(Shell Code)

```bash
# 사이트 테스트 시작 #
$ bundle exec jekyll serve

# 테스트 중단 #
# MacOS & Windows 'control + c' #
$ ^C
```

<br/>

## 테스트 사이트 주소

[http://127.0.0.1:4000/](http://127.0.0.1:4000/)
cmd + click(클릭)

<br/>

## 포스트 마크다운 파일 작명 규칙

```
YEAR-MONTH-DAY-Categories-Tags-PostTitle.md

# Example #
2021-08-14-NOTE-C++-Example.md
```

공백은 하이픈 `-`으로 표현한다.

<br/><br/><br/>

# UML 및 다이어그램 사용법
`_includes/post.html` 에 
```html
<script src="https://cdn.jsdelivr.net/npm/mermaid/dist/mermaid.min.js"></script>
<script>mermaid.initialize({startOnLoad:true});</script>

***오류 발견으로 보류됨***
```
코드가 추가되어 있어 `post` 레이아웃의 게시글은 다이어그램 작성 가능

`post` 레이아웃이 아닌 곳에서 사용하고 싶다면 위의 코드를 해당 마크다운 파일의 최상단에 삽입하고 아래의 사용법 대로 다이어그램 작성하면 됨


```html
<div class="mermaid"> 
  
  {그래프 내용}

</div>
```
형식으로 작성하면 됨

<br/><br/><br/>

# 주의사항

> 모든 이미지 파일은 `/assets` 경로를 통해서만 정상 작동한다.

> 맥에서 작업시 확장자명의 대소문자 구분을 확실히 해야 한다. (소문자 통일 권장)