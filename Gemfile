source 'https://rubygems.org'

# Specify your gem's dependencies in active_admin_datetimepicker.gemspec
gemspec

group :test do
  default_rails_version = '5.2.1'
  default_activeadmin_version = '2.0.0'

  gem 'rails', "~> #{ENV['RAILS'] || default_rails_version}"
  gem 'activeadmin', "~> #{ENV['AA'] || default_activeadmin_version}"

  gem 'sprockets-rails', '3.0.4'
  gem 'rspec-rails'
  gem 'coveralls', require: false # Test coverage website. Go to https://coveralls.io
  gem 'sass-rails'
  gem 'sqlite3', '~> 1.3.6'
  gem 'launchy'
  gem 'database_cleaner'
  gem 'capybara'
  gem 'selenium-webdriver'
  gem 'chromedriver-helper'
  gem 'byebug'
end
