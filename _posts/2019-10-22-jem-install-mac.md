---
layout: post
title:  "install jekyll budler on mac"
date:   2019-10-22 20:46:15 +0900
categories: mac update
---

gem install jekyll budler

ERROR:  While executing gem ... (Gem::FilePermissionError)
    You don't have write permissions for the /Library/Ruby/Gems/2.3.0 directory
    
문제 해결 : 
brew update
brew install rbenv ruby-build


버전 확인 : 
rbenv versions
