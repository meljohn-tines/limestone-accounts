# frozen_string_literal: true

source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "2.3.0"

# Bundle edge Rails instead: gem "rails", github: "rails/rails"
gem "rails", "~> 5.2", ">= 5.2.4.3"

# Use postgresql as the database for Active Record
#gem "pg", "~> 0.21"

# Use Puma as the app server
gem "puma", "~> 3.12"

# Use Rack Timeout. Read more: https://github.com/heroku/rack-timeout
gem "rack-timeout", "~> 0.4"

# Use SCSS for stylesheets
gem "sass-rails", "~> 5", ">= 5.0.7"

# Use Uglifier as compressor for JavaScript assets
gem "uglifier", ">= 1.3.0"

# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
#gem "webpacker", ">= 4.0.x"

# Use CoffeeScript for .coffee assets and views
gem "coffee-rails", "~> 4.2", ">= 4.2.2"

# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem "turbolinks", "~> 5"

# TODO: Consider replacing with active_model_serializers
gem "jbuilder", "~> 2.7", ">= 2.7.0"

# Use Redis Rails to set up a Redis backed Cache and / or Session
gem "redis-rails", "~> 5.0", ">= 5.0.2"

# Use Font Awesome Rails for Font Awesome icons
# gem "font-awesome-rails", "~> 4.7"

# Pretty html abstractions
gem "haml", "~> 5"
gem "simple_form", "~> 5", ">= 5.0.0"

# Multi-tennancy
gem "apartment", "~> 2.2", ">= 2.2.0"
gem "apartment-sidekiq", "~> 1.2", ">= 1.2.0"

# Authentication
gem "devise", "4.6.0"
gem "devise_invitable", "~> 1.6.1"
gem "responders", "2.4.0"
# Authorization
gem "pundit", "~> 1", ">= 1.1.0"

# Soft deletes for ActiveRecord done right
gem "discard", "~> 1", ">= 1.0.0"

# Pretty admin dashboards
gem "administrate", "~> 0.13", ">= 0.13.0"

gem "receipts"
# Stripe stuff
gem "stripe"
gem "stripe_event", "~> 2.1.1"

# Upload to S3 directly
gem "aws-sdk-s3"

# Process images
gem "image_processing"
gem "mini_magick", ">= 4.3.5"

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", ">= 1.1.0", require: false

# Impersonate other users
gem "pretender", ">= 0.3.2"

# Search
# gem "searchkick", "~> 3.0"

# Jerbs
gem "sidekiq", "~> 5.0"

# Use Clockwork or Whenever for recurring background tasks
# gem "clockwork"
# gem "whenever"

# Feature flagging
gem "flipper"
gem "flipper-redis"
gem "flipper-ui"

gem "counter_culture", "~> 1.12", ">= 1.12.0"

group :development do
  gem "haml-lint", require: false
  gem "listen", ">= 3.0.5", "< 3.2"
  gem "rubocop"
  gem "spring", ">= 2.0.2"
  gem "spring-watcher-listen", "~> 2.0.1"
  gem "web-console", ">= 3.6.2"
end

group :test do
  gem "database_cleaner", "~> 1.6"
  gem "faker", "~> 1.8"
  gem "shoulda-matchers", "~> 3.1", ">= 3.1.2"
  gem "simplecov", ">= 0.16.1", require: false
end

group :development, :test do
  gem "action-cable-testing", "~> 0.3", ">= 0.3.1"
  gem "capybara", "~> 2.15"
  gem "chromedriver-helper"
  gem "factory_bot_rails", "~> 4.10", ">= 4.10.0"
  gem "pry"
  gem "rails-controller-testing", "~> 1", ">= 1.0.2"
  gem "rspec-rails", "~> 3.8", ">= 3.8.0"
  gem "selenium-webdriver"
  gem "stripe-ruby-mock", github: "archonic/stripe-ruby-mock", require: "stripe_mock"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data"
