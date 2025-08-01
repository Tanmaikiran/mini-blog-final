# frozen_string_literal: true

source "https://rubygems.org"

ruby "3.2.2"

# Rails
gem "rails", "~> 8.0.2"

# PostgreSQL
gem "pg", "~> 1.5"

# Puma for app server
gem "puma", "~> 6.6"

# Sass for styling
gem "sass-rails", ">= 6"

# Importmap
gem "importmap-rails"

# Stimulus & Turbo
gem "turbo-rails"
gem "stimulus-rails"

# Devise for authentication
gem "devise"

# Other useful gems
gem "jbuilder"
gem "bootsnap", require: false

# For background jobs (optional)
gem "sidekiq"

group :development, :test do
  gem "debug", platforms: %i[mri mingw x64_mingw]
  gem "rspec-rails"
  gem "dotenv-rails"  # ✅ Enables use of .env for DATABASE_URL and others
end

group :development do
  gem "web-console"
  gem "listen"
  gem "spring"
  gem "spring-watcher-listen"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end
