---
layout: post
title:  "What is Jekyll"
date:   2021-11-27 03:30:36 +0530
categories: Jekyll
comments: true
---

<h3>Jekyll 구조</h3>

'''
├── _data
│   ├── locale.yml
│   ├── navigation.yml
│   └── variables.yml
├── _includes
│   ├── analytics-providers
│   ├── aside
│   ├── comments-providers
│   ├── markdown-enhancements
│   ├── pageview-providers
│   ├── scripts
│   ├── sidebar
│   ├── snippets
│   ├── svg
│   │   ├── icon
│   │   │   ├── social
│   │   │   │   ├── facebook.svg
│   │   │   │   └── ...
│   │   └── logo.svg
│   └── ...
├── _layouts
│   ├── 404.html
│   ├── archive.html
│   ├── article.html
│   ├── base.html
│   ├── home.html
│   ├── none.html
│   └── page.html
├── _sass
├── assets
│   ├── css
│   │   └── blog.scss
│   └── images
├── tools
├── 404.html
├── Gemfile
├── _config.yml
├── about.md
├── archive.html
├── favicon.ico
├── gulpfile.js
├── index.html
├── jekyll-text-theme.gemspec
└── package.json
'''

<h3>_config.yml에 관해</h3>
Jekyll에서 _config.yml은 여러분이 여러분의 테마를 만들거나, 테마를 수정하지 않더라도, 커스터마이징을 원한다면 자주 들락날락할 파일입니다. JSON처럼 데이터의 형태를 나타내는 YAML 문법으로 작성되어 있으며, 각 테마별로 달려있는 옵션이 다를수도 있습니다. TeXt의 _config.yml은 기본적으로 어느 부분이 어떤 역할을 하는지 주석으로 표시해 놔서 대략적인 의미 정도는 이해하기에 충분합니다. 한번 쭉 읽어보세요.
이걸 다 이해할 필요는 없습니다. 내가 특정한 기능을 추가하거나 수정하고 싶을 때, 어떤 부분을 건드려야 할 지 검색할 수 있는 능력만 있으면 충분합니다.