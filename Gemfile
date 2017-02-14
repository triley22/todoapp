source 'https://rubygems.org'
Ruby '2.3.1'

gem 'rails', '~> 5.0.1'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'coffee-rails', '~> 4.2'
gem 'jbuilder', '~> 2.5'
gem 'bootstrap', '~> 4.0.0.alpha6'

group :production do
  gem 'thin'
  gem 'pg'
end

group :development, :test do
  gem 'byebug', platform: :mri
  gem 'sqlite3'
end

group :test do
  gem 'capybara'
  gem 'database_cleaner'
  gem 'email_spec'
  gem 'factory_girl_rails'
  gem 'launchy'
  gem 'rails-controller-testing'
  gem 'rspec-rails'
  gem 'selenium-webdriver'
  gem 'shoulda-matchers', require: false
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end