# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

gem 'typhoeus', '~> 1.3', '>= 1.3.1'
gem "sentry-raven", "2.9.0"

group :development, :test do
  gem "guard", "~> 2.15", ">= 2.15.0"
  gem "guard-rspec", "~> 4.7", ">= 4.7.3"
  gem "rspec-rails", "~> 3.8", ">= 3.8.2"
  gem "factory_bot_rails", "~> 5.0", ">= 5.0.2"
  gem "annotate", "~> 2.7", ">= 2.7.4"

  # pry
  gem "pry", "~> 0.12", ">= 0.12.2"
  gem "pry-byebug", "~> 3.4"
  gem "pry-rails", "~> 0.3", ">= 0.3.9"
  gem "pry-doc", "~> 1.0"

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem "spring", "~> 2.0", ">= 2.0.2"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "spring-commands-rspec", "~> 1.0", ">= 1.0.4"

  # Use sqlite3 as the database for Active Record
  gem "sqlite3", "~> 1.4", ">= 1.4.1"
  gem "faker", "~> 1.9", ">= 1.9.6"
end

group :development do
  gem "httplog", "~> 1.3", ">= 1.3.1"
  gem "standard", "~> 0.2.3"
end

