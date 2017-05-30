source "https://rubygems.org" 
ruby RUBY_VERSION 

# Hello! This is where you manage which Jekyll version is used to run. 
# When you want to use a different version, change it below, save the 
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so: 
# 
#     bundle exec jekyll serve 
# 
# This will help ensure the proper Jekyll version is running. 
# Happy Jekylling! 
 
#gem "github-pages", group: :jekyll_plugins 

group :jekyll_plugins do 
   gem "jekyll-feed"
end 

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby] 

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']

gem 'reveal-ck'
