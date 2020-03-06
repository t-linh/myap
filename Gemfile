source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "2.6.3"

gem "bcrypt", "3.1.12"
gem "bootsnap", ">= 1.1.0", require: false
gem "bootstrap-sass", "3.3.7"
gem "bootstrap-will_paginate", "1.0.0"
gem "carrierwave", "1.2.2"
gem "coffee-rails", "~> 4.2"
gem "faker", "1.7.3"
gem "jbuilder", "~> 2.5"
gem "jquery-rails"
gem "mini_magick", "4.9.4"
gem "puma", "~> 3.11"
gem "rails", "~> 5.2.3"
gem "sass-rails", "~> 5.0"
gem "sqlite3"
gem "turbolinks", "~> 5"
gem "uglifier", ">= 1.3.0"

group :development, :test do
  gem "awesome_print"
  gem "pry-coolline"
  gem "pry-rails"
  gem "rubocop", require: false
  gem "rubocop-performance"
  gem "rubocop-rails"
end

group :development do
  gem "listen", ">= 3.0.5", "< 3.2"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "web-console", ">= 3.3.0"
end

group :test do
  gem "guard",                    "2.13.0"
  gem "guard-minitest",           "2.4.4"
  gem "minitest",                 "5.10.3"
  gem "minitest-reporters",       "1.1.14"
  gem "rails-controller-testing", "1.0.2"
end

group :production do
  gem "fog", "1.42"
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
