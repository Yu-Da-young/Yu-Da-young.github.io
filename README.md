# git blog 작성 과정 
## ruby, jekyll 설치
기존에 git은 이미 설치를 한 상태였기 때문에 ruby와 jekyll을 깔으면 됐다.
mac을 사용하기 때문에 ruby버전을 기존 설정에서 내가 설치한 버전으로 바꿔줘야 했는데 그 과정이 순탄하지 않았다.
**Gem::FilePermissionError** 가 계속 떠서 rbenv로 ruby가 관리되도록 설정해줬다.

## github page 생성
github에 Yu-Da-young.github.io 이름의 repository를 생성하였다.
그 후 git clone으로 local-remote repository끼리 연동을 시켜주었다.
토큰은 1학기에 이미 해놔서 그 과정은 넘겼다.

## 테마 바꾸기
http://jekyllthemes.org/
이 링크에서 plainwhite라는 테마를 다운받았다.
fork하는 법을 모르겠어서 git clone으로 로컬로 받아왔다.
그 후 테마에 맞게 사진을 추가했고 readme.md를 읽으면서 넣어줘야 하는 코드를 넣고 _posts에 포스트도 작성해 보았다.

## 댓글 기능 추가하기
먼저 disqus에 가입하고 _confiig.yml에

'''
comment:
  provider:         "disqus"
  disqus:
    shortname:      "yudayoung" 
'''

이 코드를 넣어주었다.

그 후에는 disqus 홈페이지에서 code를 복사하여 _layouts/post.html 에 넣어주었다.
_posts 에 있는 포스트 중 댓글 기능을 원하는 곳에
'''
comments: true
'''
라는 코드를 넣어주었다.
