source 'http://rubygems.org'

gem 'jekyll'
gem 'coderay'
gem 'sass', '3.4.5'
gem 'octopress', '~> 3.0.0.rc.12'
gem 'jekyll-sitemap'
gem 'rouge'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']
