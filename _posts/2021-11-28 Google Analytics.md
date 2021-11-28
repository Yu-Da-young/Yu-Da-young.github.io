---
layout: post
title:  "Yuda"
date:   2021-11-28 18:25:13 +0530
comments: true
---

Google Analytics 적용법


- Google Analytics 등록하기
속성 이름에 블로그 주소를 넣어 계정을 생성한다.  

- tracking ID 찾기
관리 -> 데이터 스트림 에서 tracking ID를 찾아 복사한다.  

- _config.yml 수정하기
```
# Analytics
analytics:
  provider               : "google-gtag" 
                          # false (default), "google", "google-universal", "google-gtag", "custom"
  google:
    tracking_id          : "G-5HQPK7RHNC"
    anonymize_ip         : # true, false (default)
```
이 코드를 github.io 폴더 > _config.yml에 넣고 git push 하면 된다.  

이 방법이 적용되지 않을 경우 _includes > head.html에 웹 스트림 세부정보에 있는 코드를 넣어주면 된다.  

나의 경우 첫번째 방법이 적용되지 않아 두번째 방법을 사용하였다.