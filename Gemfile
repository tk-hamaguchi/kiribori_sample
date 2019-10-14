# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.5'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.0'
# Use mysql as the database for Active Record
gem 'mysql2', '>= 0.4.4'
# Use Puma as the app server
gem 'puma', '~> 3.11'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 4.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'
# Use Active Model has_secure_password
gem 'bcrypt', '~> 3.1.7'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'rails-i18n'
group :development, :test do
  gem 'rubocop', '0.74.0'
  gem 'rubocop-checkstyle_formatter', require: false
  gem 'rubocop-junit-formatter'
  gem 'rubocop-rspec'
  gem 'rubocop-performance'
end

gem 'config'

gem 'dotenv-rails'

gem 'redis'
gem 'hiredis'
gem 'haml-rails'

gem 'simple_form'

group :development, :test do
  gem 'rspec-rails', '~> 3.8'
  gem 'rails-controller-testing', require: false
  gem 'rspec-its'
  gem 'rspec_junit_formatter'
  gem 'shoulda-matchers', require: false
end

group :development, :test do
  gem 'cucumber-rails', require: false
  gem 'webdrivers'
  gem 'capybara'
  gem 'database_cleaner'
  gem 'aruba'
end

group :development, :test do
  gem 'factory_bot_rails'
  gem 'faker', require: false
  gem 'faker-japanese', require: false
end

group :development, :test do
  gem 'annotate'
end

group :development, :test do
  gem 'reek'
end

gem 'devise'
gem 'devise-i18n'

gem 'acts_as_paranoid'

gem 'kaminari'

gem 'pundit'

gem 'ajax-datatables-rails'
gem 'draper'

group :development, :test do
  gem 'rails_best_practices'
end

group :development do
  gem 'rails-erd'
end
