Hexo-theme-yilia
================
Yilia : A simple and elegant theme for [Hexo](https://github.com/tommy351/hexo).

[Current Project Demo](http://dinosaurfiles.github.io/)

[Original Demo](http://litten.github.io/)




####Problems/Issues?
* Submit an issue [here](https://github.com/dinosaurfiles/hexo-theme-yilia/issues)

—————————————————————

#### Installation

``` bash
$ git clone https://github.com/dinosaurfiles/hexo-theme-yilia.git themes/yilia
```

#### Installing the theme

Modify the theme in `hexoblog/_config.yml` by changing theme variable to `yilia`

##Configuration

Modifying the yilia theme `hexoblog/themes/yilia/_config.yml`

```
# Header
menu:
  Home: /
  Archives: /archives
  # Tags: /tags/tags

# SubNav
subnav:
  github: "#"
  rss: "#"
  facebook: "#"
  google: "#"
  twitter: "#"
  linkedin: "#"

rss: /atom.xml


# Content
excerpt_link: more
fancybox: true
mathjax: true

# Miscellaneous
google_analytics: ''
favicon: /favicon.png

#Services:

#Avatar url
avatar: ""
#Share Links
share: true
#Disqus
disqus_shortname: ''
#Tag Cloud
tagcloud: true

#Links
friends:
  Link 1: http://localhost:4000/
  Link 2: http://localhost:4000/
  Link 3: http://localhost:4000/
  Link 4: http://localhost:4000/
  Link 5: http://localhost:4000/
  Link 6: http://localhost:4000/

#About Me
aboutme: Hail Hydra..
```

##Other
#####Enabling RSS feed
Execute `npm install hexo-generator-feed --save` in your Hexo blog folder
