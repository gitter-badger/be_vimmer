source 'https://rubygems.org'

ruby "1.9.3"

gem 'rails', '3.2.16'

gem "twitter-bootstrap-rails"
gem 'twitter', '~> 4.5'
gem "thin"
gem "haml", ">= 3.0.0"
gem "haml-rails"
gem "jquery-rails"

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
  gem 'less-rails'
  gem 'therubyracer'
end

group :production do
  gem 'pg'
end

group :development, :test do
  gem 'sqlite3'
  gem 'heroku_san'
  gem 'heroku'
end

group :test do
  gem "rspec-rails", ">= 2.0.1"
  gem 'capybara'
end
