source 'https://rubygems.org'

gem 'rails', '7.1.0'
gem 'sqlite3'
gem 'thin'
gem 'faye'

# Heroku and New Relic
gem 'rails_12factor'
gem 'newrelic_rpm'

# Assets
gem 'jquery-rails', '>= 4.3.2'
gem 'turbolinks'
gem 'sass-rails', '~> 5.0', '>= 5.0.8'
gem 'coffee-rails', '~> 4.2.2'
gem 'uglifier', '>= 1.0.3'
gem 'bootstrap-sass'
gem 'therubyracer', require: 'v8'
gem 'yui-compressor'
gem 'font-awesome-rails', '>= 4.7.0.8'
gem 'responders', '~> 3.0', '>= 3.0.0'

# Custom gems
gem 'pivotal-tracker'
gem 'backtop'
gem 'mongoid', github: 'mongoid'
gem 'bson_ext'

gem 'rspec-rails', '>= 3.6.1', group: [:test, :development]

group :test do
  gem 'factory_girl_rails', '>= 4.9.0'
  gem 'forgery'
  gem 'capybara'
  gem 'selenium-webdriver'
  gem 'database_cleaner'
  gem 'rack_session_access'
  gem 'mocha', require: false
  gem 'zeus', require: false
end

group :development do
  gem 'spring'
  gem 'better_errors', '>= 2.3.0'
  gem 'binding_of_caller'
  gem 'capistrano', '~> 3.0', require: false
  gem 'capistrano-rails', '~> 1.1', require: false
  gem 'capistrano-bundler', '~> 1.1', require: false
  gem 'capistrano-rvm', '~> 0.1', require: false
  gem 'codeclimate-test-reporter', require: false
end

gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc
