# robinkwong.github.io
This is the personal webstie of Robin Kwong: https://robinkwong.com

Heavily inspired by alexcarpenter.me and uses his Butane Jekyll Theme

## Building locally

github-pages 232 does not install on Ruby 4, so the site builds on Homebrew's `ruby@3.3` (pinned in `.ruby-version`). It is keg-only, so put it first on the PATH:

    export PATH=/opt/homebrew/opt/ruby@3.3/bin:$PATH
    bundle install
    bundle exec jekyll serve
