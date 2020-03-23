# Development Overview
### Shared Setup
Do this in the terminal of your local machine:

    1. Install bundle
    2. Install jekyll

### First-time build
Mostly copied from https://jekyllrb.com/tutorials/using-jekyll-with-bundler/

    1. < cd to github pages root project directory >
    2. create a Gemfile in the root project directory by copying this site's /Gemfile
    3. $ bundle config set path 'vendor/bundle'
    4. $ bundle install
    5. $ bundle exec jekyll new --force --skip-bundle .
    6. $ bundle install

### Rebuild Static site & view it
    1. < cd to github pages root project directory >
    2. bundle update
    3. terminal $ bundle exec jekyll serve
    4. in browser: localhost:4000
