---
layout: content
title: Use Jekyll
---
已经有仓库的时候，安装jekyll
使用`bundle exec jelkyll serve`时报错

>Could not locate Gemfile or .bundle/ directory

处理方法:
```shell
bundle init
bundle add jekyll
bundle install
bundle exec jekyll new --force --skip-bundle .
```

