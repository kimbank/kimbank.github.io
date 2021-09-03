---
layout: post
title: "파이썬(Python) 특징"
subtitle: ""
date: 2021-09-03 13:00:00 +0900
categories: note
tags: python
comments: false
related_posts: false
---

# 목차

- [**개요**](#개요)
- [**디자인 철학**](#디자인-철학)
- [**단점**](#tables)

# 개요

파이썬은 스크립트 언어이다.
이 언어는 1991년도에 네덜란드의 프로그래머 귀도 반 로섬에 의해 개발되었다.
난이도가 비교적 쉽다는 평이 많아 프로그래밍 언어 입문자에게 많은 사랑을 받고 있다.
현재는 파이썬 소프트웨어 재단(<a href="https://www.python.org/psf/">Python Software Foundation</a>)에서 관리한다.
![import_this](/_posts/note/python/2021-09-03-import_this.png)

_1991년 파이썬 개발_ <br/> _2000년 파이썬2 출시_ <br/>_2008년 파이썬3 출시_

# 디자인 철학

파이썬의 철학이 존재한다.
이스터에그 형식으로 콘솔에 `import this`를 입력하면 확인이 가능하다.
<img src="/_posts/note/python/2021-09-03-import_this.png">

<br/>
핵심 적인 것은 아래와 같다.

_1.아름다운 것이 추한 것보다 낫다. (Beautiful is better than ugly.)_ <br/>_2. 명시적인 것이 암시적인 것보다 낫다. (Explicit is better than complex)_ <br/>_3. 단순한 것이 복잡한 것보다 낫다. (Simple is better than complex)_ <br/>_4. 복잡한 것이 알기 어려운 것보다 낫다. (Complex is better than complicated)_ <br/>_5. 가독성은 중요하다. (Readability counts)_

이를 통해 파이썬의 철학을 알 수 있다.

# 단점

일반적으로 사람이 편하면 기계가 힘들고 기계가 편하면 사람이 힘들다는 말이 있다.

백준에서 제출된 코드를 참고할 때 다른 언어로 된 것도 보이게 되는데, 파이썬을 확인해 보면 유독 메모리 소비가 크다.

C언어 `Hello World!` 출력

```C
#include <stdio.h>
int main()
{
  printf("Hello World!\n");
}
```

<img src="/_posts/note/python/2021-09-03-c_hello.png">
<br/>
<br/>
파이썬 `Hello World!` 출력

```Python
print('Hello World')
```

<img src="/_posts/note/python/2021-09-03-python_hello.png">

<br/>

파이썬을 보면 코드가 짧아 사용하기 편하다.
하지만 메모리 소모가 큰 것이 확인된다.

<sup><sub> [목차](#목차) </sub></sup>

---
