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
```
코드가 추가되어 있어 `post` 레이아웃의 게시글은 다이어그램 작성 가능

`post` 레이아웃이 아닌 곳에서 사용하고 싶다면 위의 코드를 해당 마크다운 파일의 최상단에 삽입하고 아래의 사용법 대로 다이어그램 작성하면 됨


```html
<div class="mermaid"> 
  
  graph TD; A-->B;

</div>
```
형식으로 작성하면 됨

<br/>

## mermaid 문법

[출처](https://mermaid-js.github.io/mermaid/#/)

### Flowchart

![](https://mermaid-js.github.io/mermaid/img/flow.png)

```html
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

<br/>

### Sequence Diagram

![](https://mermaid-js.github.io/mermaid/img/sequence.png)

```html
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
```

<br/>

### Gantt Diagram

![](https://mermaid-js.github.io/mermaid/img/gantt.png)

```html
gantt
dateFormat  YYYY-MM-DD
title Adding GANTT diagram to mermaid
excludes weekdays 2014-01-10

section A section
Completed task            :done,    des1, 2014-01-06,2014-01-08
Active task               :active,  des2, 2014-01-09, 3d
Future task               :         des3, after des2, 5d
Future task2               :         des4, after des3, 5d
```

<br/>

### Class Diagram

![](https://mermaid-js.github.io/mermaid/img/class.png)

```html
classDiagram
Class01 <|-- AveryLongClass : Cool
Class03 *-- Class04
Class05 o-- Class06
Class07 .. Class08
Class09 --> C2 : Where am i?
Class09 --* C3
Class09 --|> Class07
Class07 : equals()
Class07 : Object[] elementData
Class01 : size()
Class01 : int chimp
Class01 : int gorilla
Class08 <--> C2: Cool label
```

<br/>

### Git Graph

![](https://mermaid-js.github.io/mermaid/img/git.png)

```html
gitGraph:
options
{
    "nodeSpacing": 150,
    "nodeRadius": 10
}
end
commit
branch newbranch
checkout newbranch
commit
commit
checkout master
commit
commit
merge newbranch
```

<br/>

### Entity Reationship Diagram

![](https://mermaid-js.github.io/mermaid/img/simple-er.png)

```html
erDiagram
    CUSTOMER ||--o{ ORDER : places
    ORDER ||--|{ LINE-ITEM : contains
    CUSTOMER }|..|{ DELIVERY-ADDRESS : uses
```

<br/>

### User Journey Diagram

![](https://mermaid-js.github.io/mermaid/img/user-journey.png)

```html
journey
    title My working day
    section Go to work
      Make tea: 5: Me
      Go upstairs: 3: Me
      Do work: 1: Me, Cat
    section Go home
      Go downstairs: 5: Me
      Sit down: 5: Me
```

<br/><br/><br/>

# 주의사항

> 모든 이미지 파일은 `/assets` 경로를 통해서만 정상 작동한다.

> javascript 파일도 src로 불러오려면 asset폴더에 위치해야한다.

> 맥에서 작업시 확장자명의 대소문자 구분을 확실히 해야 한다. (소문자 통일 권장)