# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.1.0'

gem 'rails', '~> 7.0.3', '>= 7.0.3.1'
gem 'sprockets-rails'
gem 'puma', '~> 5.0'
gem 'importmap-rails'
gem 'turbo-rails'
gem 'stimulus-rails'
gem 'jbuilder'
gem 'redis', '~> 4.0'
gem "kredis"
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
gem 'bootsnap', require: false
gem "sassc-rails"
gem 'sqlite3'
gem "image_processing", "~> 1.2"

group :development, :test do
  gem 'debug', platforms: %i[mri mingw x64_mingw]

  # Security tools
  gem 'brakeman'
  gem 'bundler-audit'
  gem 'ruby_audit'

  # Database
  gem 'pg', '~> 1.1'

  # Linting
  gem 'rubocop'
  gem 'rubocop-rails'
end

group :development do
  gem 'web-console'
  gem "rack-mini-profiler"
end

group :test do
  gem 'capybara'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end
