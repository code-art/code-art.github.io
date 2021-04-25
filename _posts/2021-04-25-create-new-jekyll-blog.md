---
layout: post
title:  "Create new Jekyll Project!"
date:   2021-04-25 22:59:19 +0300
categories: jekyll create
---

### Create new Jekyll project
<pre>$ jekyll new . --force</pre>

### Run Jekyll on locally
``` console
$ bundle exec jekyll serve --livereload
```

### Update Gemfile before push to GitHub Repository
``` console
# Happy Jekylling!
# gem "jekyll", "~> 4.2.0"   # Comment this line
# This is the default theme for new Jekyll sites. You may change this to anything you like.
gem "minima", "~> 2.5"
# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
gem "github-pages", group: :jekyll_plugins      # uncomment this line
```

### Update _config.yml
``` console
title: code-art
email: code-art@code.dev
description: >- # this means to ignore newlines until "baseurl:"
  Write an awesome description for your new site here. You can edit this
  line in _config.yml. It will appear in your document head meta (for
  Google search results) and in your feed.xml site description.
baseurl: "" # the subpath of your site, e.g. /blog
url: "code-art.github.io" # the base hostname & protocol for your site, e.g. http://example.com
twitter_username: jekyllrb
github_username:  jekyll
```