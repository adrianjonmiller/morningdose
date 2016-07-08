source 'https://rubygems.org'
gem 'github-pages'
gem 'scss_lint', require: false
gem 'octopress-autoprefixer'
gem 'autoprefixer-rails'
gem 'jekyll-assets'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']
