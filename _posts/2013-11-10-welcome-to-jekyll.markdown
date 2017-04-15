---
layout: post
title:  "Welcome to Jekyll!"
date:   2013-11-10 10:18:00
categories: Thriller Comedy Horror
---

You'll find this post in your `_posts` directory - edit this post and re-build (or run with the `-w` switch) to see your changes!
To add new posts, simply add a file in the `_posts` directory that follows the convention: YYYY-MM-DD-name-of-post.ext.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll's GitHub repo][jekyll-gh].

[jekyll-gh]: https://github.com/mojombo/jekyll
[jekyll]:    http://jekyllrb.com



# Git 자주 사용하는 명령어 정리
자주 사용하는 기본적인 명령어들을 정리했습니다.
- 최근 수정일 : 2017-04-15 / 수정ddd //  수정2

## 저장소 생성(초기화) 하기
```bash
git init # 저장소 생성
```

## 커밋하기
```bash
git add README.md # 커밋할 파일 추가
git status # 현재 스테이지 상태를 확인
git commit -m "init: README.md" # 인라인 커밋 메시지 작성
git log --decorate=full --oneline --graph # 커밋 로그 확인
```

## 브랜치 생성하기
```bash
git checkout -b readme # readme 라는 이름의 브랜치를 생성한 후, 생성된 브랜치로 체크아웃
```

## 머지하기
```bash
git merge readme --no-ff # readme 브랜치의 내용을 가져와서 머지함, fast-forward 기능 끄기
```

## License
이 저장소는 MIT 라이선스의 보호를 받습니다.
