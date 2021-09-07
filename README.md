# 사이트 테스트 방법

## 쉘 코드(Shell Code)

```bash
# 사이트 테스트 시작 #
$ bundle exec jekyll serve

# 테스트 중단 #
# MacOS & Windows 'control + c' #
$ ^C
```



## 테스트 사이트 주소

[http://127.0.0.1:4000/](http://127.0.0.1:4000/)
cmd + click(클릭)



## 포스트 마크다운 파일 작명 규칙

```
YEAR-MONTH-DAY-Categories-Tags-PostTitle.md

# Example #
2021-08-14-NOTE-C++-Example.md
```

공백은 하이픈 `-`으로 표현한다.



# 주의사항

> 모든 이미지 파일은 `/assets` 경로를 통해서만 정상 작동한다.

> 맥에서 작업시 확장자명의 대소문자 구분을 확실히 해야 한다. (소문자 통일 권장)