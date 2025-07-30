# frozen_string_literal: true

source "https://rubygems.org"

# Ruby version (matches Gitpod and Render)
ruby "3.2.8"

# Rails
gem "rails", "~> 8.0.2"

# PostgreSQL
gem "pg", "~> 1.5"

# Puma web server
gem "puma", "~> 6.0"

# Sass (for Bootstrap)
gem "sass-rails", ">= 6"

# Turbo + Stimulus (Hotwire)
gem "turbo-rails"
gem "stimulus-rails"

# Devise for authentication
gem "devise"

# Import maps
gem "importmap-rails"

# JSON views
gem "jbuilder"

# Speed up boot time
gem "bootsnap", require: false

# Background jobs (optional)
gem "sidekiq"

# === Development & Test ===
group :development, :test do
  gem "rspec-rails"
  gem "debug", platforms: %i[mri mingw x64_mingw]
end

# === Development Only ===
group :development do
  gem "web-console"
  gem "listen"
  gem "spring"
  gem "spring-watcher-listen"
end

# === Test Only ===
group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end
