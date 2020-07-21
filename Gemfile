# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) { |repo_name| "https://github.com/#{repo_name}" }

gem "typhoeus
gem "sentry-raven"

group :development, :test do
  gem "guard"
  gem "guard-rspec"
  gem "rspec-rails"
  gem "factory_bot_rails"
  gem "annotate"

  # pry
  gem "pry"
  gem "pry-byebug"
  gem "pry-rails"
  gem "pry-doc"

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem "spring"
  gem "spring-watcher-listen"
  gem "spring-commands-rspec"

  # Use sqlite3 as the database for Active Record
  gem "sqlite3"
  gem "faker"
end

group :development do
  gem "brakeman"
  gem "httplog"
  gem "standard"
end
