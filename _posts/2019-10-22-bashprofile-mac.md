---
layout: post
title:  "bash_profile, bashrc, zshrc"
date:   2019-10-22 21:30:15 +0900
categories: mac update
---

  .bash_profile
    - 시스템에 로그인할 때마다 실행
    - login shell 에서 실행
    - .bash_profile, .bash_login, .profile 

  .bashrc
    - 이미 로그인 한 상태에서 새 터미널 창을 열 때마다 실행 
    - non-login shell 실행

  .bash_logout
    - login shell을 종료할 때마다 실행한다.


새 터미널 창을 열 때마다 .bash_profile 실행 방법,
.bashrc 에 .bash_profile 을 호출



#.bash_profile
if [ -f ~/.bashrc ]; then
. ~/.bashrc
fi


추가 zshrc
source ~/.bash_profile