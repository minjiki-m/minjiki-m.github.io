---
layout: post
title:  "git 자주쓰는 명령어"
date:   2019-10-28 18:25:15 +0900
categories: dev update
---



#### git 

<pre>
<code>
$ git remote add/show origin [git 저장소]
$ git add . 
$ git commit -m "comment"
$ git push origin master
$ git log 
$ git status
$ git fetch
</code>
</pre>

git clone [git 저장소] -> 복제 모든 파일 가져오기만 함
git clone -b [브랜치] [git 저장소]

git pull -> local repository와 비교 병합 local repository 저장(add)


git brach [브랜치명feature/001] master

git checkout [브랜치명]
git checkout -b [브랜치명] -> 생성과 체크아웃