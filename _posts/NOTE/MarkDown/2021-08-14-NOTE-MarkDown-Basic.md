---
layout: post
title: "마크다운 기본 문법"
subtitle: ""
date: 2021-08-14 13:00:00 +0900
categories: note
tags: markdown
comments: false
related_posts: false
#   - category/_posts/study/2020-12-26-making-blog-02.md
#   - category/_posts/study/2020-12-26-making-blog-03.md
---

# 목차

- [**제목** <sub><sub><sup>_Header_</sup></sub></sub>](#header)
- [**강조** <sub><sub><sup>_Emphasis_</sup></sub></sub>](#emphasis)
  - [이텔릭체 <sub><sub><sup>_Italic_</sup></sub></sub>](#italic)
  - [볼드체 <sub><sub><sup>_Bold_</sup></sub></sub>](#bold)
  - [취소선 <sub><sub><sup>_Strike-Out_</sup></sub></sub>](#strike-out)
- [**표** <sub><sub><sup>_Tables_</sup></sub></sub>](#tables)

# **목차 활용**

마크다운 문법 활용

> **1. 최상위 [제목<sup><sub><sup>_Header_</sup></sub></sup>](#header)은 [볼드체<sup><sub><sup>_Bold_</sup></sub></sup>](#bold)를 사용한다.**
>
> <sub>_예시)_</sub>
>
> # Contents Table
>
> - [**Example** ](#Example)

---

> **2. 제목에 영어로 부제를 추가할 때에는 [위 첨자<sup><sub><sup>_Superscript_</sup></sub></sup>](#superscript) 한 번과 [아래 첨자<sup><sub><sup>_Subscript_</sup></sub></sup>](#subscript) 두 번 사용한다.**
>
> <sub>_예시)_</sub>
>
> # Contents Table
>
> - [**Example** <sub><sub><sup>_Example_</sup></sub></sub>](#Example)

---

# **제목** <sub><sub><sup>_Header_</sup></sub></sub>

`<h1>`부터 `<h6>`까지 제목을 정할 수 있다.

```
# 제목 1

## 제목 2

### 제목 3

#### 제목 4

##### 제목 5

###### 제목 6
```

# **강조** <sub><sub><sup>_Emphasis_</sup></sub></sub>

## 이텔릭체 <sub><sub><sup>_Italic_</sup></sub></sub>

| MarkDown    | Result    |
| ----------- | --------- |
| `*Example*` | _Example_ |
| `_Example_` | _Example_ |

## 볼드체 <sub><sub><sup>_Bold_</sup></sub></sub>

| MarkDown      | Result      |
| ------------- | ----------- |
| `**Example**` | **Example** |
| `__Example__` | **Example** |

## 이텔릭체 & 볼드체

| MarkDown        | Result        |
| --------------- | ------------- |
| `***Example***` | **_Example_** |
| `___Example___` | **_Example_** |
| `_**Example**_` | _**Example**_ |
| `*__Example__*` | _**Example**_ |
| `__*Example*__` | **_Example_** |
| `**_Example_**` | **_Example_** |

`___Example___`_이 효율적임_

## 취소선 <sub><sub><sup>_Strike-Out_</sup></sub></sub>

| MarkDown      | Result      |
| ------------- | ----------- |
| `~~Example~~` | ~~Example~~ |

## 위 첨자 <sub><sub><sup>_Superscript_</sup></sub></sub>

| MarkDown                    | Result                    |
| --------------------------- | ------------------------- |
| `Example<sup>Example</sup>` | Example<sup>Example</sup> |

## 아래 첨자 <sub><sub><sup>_Subscript_</sup></sub></sub>

| MarkDown                    | Result                    |
| --------------------------- | ------------------------- |
| `Example<sub>Example</sub>` | Example<sub>Example</sub> |

---

# **표** <sub><sub><sup>_Tables_</sup></sub></sub>

## 표 생성

```markdown
| Example 1 | Example 2 |
| --------- | --------- |
| Content 1 | Content 2 |
```

## 표 정렬

```markdown
| Example 1 | Example 2 | Example3 |
| :-------- | :-------: | -------: |
| Left      |  Middle   |    Right |
```

<sup><sub> [목차](#목차) </sub></sup>

---
