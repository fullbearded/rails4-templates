source 'http://ruby.taobao.org'

# rails
gem 'rails', '4.1.4'
gem 'rails_config'

# database
gem 'mongoid'
gem 'mongoid_rails_migrations', '1.0.1'

# asset pipeline
gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'therubyracer', platforms: :ruby
gem 'compass-rails', '~> 1.1.7'

# plugin for js
gem 'jquery-rails'
gem 'underscore-rails'

# Pagination
gem 'kaminari'

# file manage
gem 'carrierwave'
# gem 'mini_magick'
gem 'carrierwave-mongoid', :require => 'carrierwave/mongoid'

# json build
gem 'rabl-rails'
gem 'oj'

# cache
gem "dalli"

# others
gem 'chinese_pinyin', require: false

gem 'capistrano3_templates', git: 'https://github.com/huhongda/capistrano3_templates.git'
# rails g capistrano3_templates:install

group :development do
  # deploy
  gem 'capistrano-rails'
  gem 'capistrano-bundler'
  gem 'capistrano-rbenv'
  # server
  gem 'thin'
  gem 'quiet_assets'
end

group :development, :test do
  gem 'pry'
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'database_cleaner'
  gem 'teaspoon'
  gem 'simplecov', :require => false
end

group :test do
  gem 'selenium-webdriver'
  gem 'capybara'
end

group :production do
  # crontab
  gem 'whenever'
  gem 'newrelic_rpm'
  gem 'unicorn'
  gem 'unicorn-worker-killer'
end