troubleshooting: Use Ruby 2.7.4 instead.

1. Ruby+Devkit 2.7.4 [Download Archives](https://rubyinstaller.org/downloads/archives/)

troubleshooting: Use eventmachine for ruby.

1. `gem uninstall eventmachine`
2. `gem install eventmachine --platform ruby`

Server on.

1. Fork and or clone [modern-resume-theme](https://github.com/sproogen/modern-resume-theme)
2. `cd modern-resume-theme`
3. `bundle install`
4. `bundle exec jekyll serve`
5. Open your browser to `http://localhost:4000`

livereload.

1. `bundle exec jekyll serve --livereload`
2. Open your browser to `http://localhost:35729`

build site.

1. `jekyll build`
