source :rubygems

gem "rails", "~> 3.2.3"
gem "rake"

gem "authlogic"
gem "capistrano", "2.8.0"
gem "chronic"
gem "dynamic_form"
gem "formatize"
gem "haml-rails"
gem "heroku_san"
gem "hpricot"
gem "jquery-rails"
gem "newrelic_rpm"
gem "paperclip"
gem "progress_bar"
gem "rack-recaptcha", :require => "rack/recaptcha"
gem "rMeetup"
gem "rMeetup"
gem "sass"
gem "seed_dump"
gem "sunspot_rails"
gem "sunspot_solr"
gem "will_paginate"

group :assets do
  gem "coffee-rails", "~> 3.2.1"
  gem "sass-rails",   "~> 3.2.3"
  gem "uglifier",     ">= 1.0.3"
end

group :development do
  gem "mysql2", :git => "git://github.com/sdruby/mysql2.git", :branch => "master"
  gem "sqlite3"
  gem "ruby-debug",   platforms: :ruby_18
  gem "ruby-debug19", platforms: :ruby_19
end

group :test do
  gem "faker"
  gem "factory_girl_rails"
  gem "rspec-rails"
  gem "shoulda-matchers"
  gem "vcr"
  gem "webmock"
  gem "capybara"
  gem "capybara-firebug"
  gem "spork", "~> 1.0rc"
  gem "database_cleaner"
end

group :development, :test do
  gem "guard"
  gem "guard-spork"
  gem "guard-rspec"
  gem "launchy"
end

group :heroku do
  gem 'pg'
end
