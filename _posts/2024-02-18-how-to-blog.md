---
title:  "github 블로그 로컬 서버 열기"
categories: 
  - Blog
tag: [Ruby]
author_profile: false
---

## 로컬 개발 서버 여는 법

#### 1) 커맨드 라인 창 열기
<aside>
📢 C:/Users/YOUR_NAME/WORKSPACE/YOUR_FOLDER/kimkyurin.github.io
</aside>{: .notice--gray}
Shift 키 + 마우스 우클릭 > 여기에서 PowerShell 창 열기

#### 2) 폴더 이동 및 서버 구동 (bundle exec jekyll serve)

```ruby
PS C:\Users\YOUR_NAME\WORKSPACE\YOUR_FOLDER> cd .\kimkyurin.github.io\
PS C:\Users\YOUR_NAME\WORKSPACE\YOUR_FOLDER\kimkyurin.github.io> bundle exec jekyll serve
```

```ruby
Configuration file: C:/Users/YOUR_NAME/WORKSPACE/YOUR_FOLDER/kimkyurin.github.io/_config.yml
            Source: C:/Users/YOUR_NAME/WORKSPACE/YOUR_FOLDER/kimkyurin.github.io
       Destination: C:/Users/YOUR_NAME/WORKSPACE/YOUR_FOLDER/kimkyurin.github.io/_site
 Incremental build: disabled. Enable with --incremental
      Generating...
                    done in 13.183 seconds.
 Auto-regeneration: enabled for 'C:/Users/YOUR_NAME/WORKSPACE/YOUR_FOLDER/kimkyurin.github.io'
    Server address: http://127.0.0.1:4000/
  Server running... press ctrl-c to stop.
```

**http://127.0.0.1:4000 서버 구동 완료**

#### 3) 설정 파일인 config.yml을 서버 리부트 필요
