source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.1.2'
gem 'rails', '~> 7.0.3'
gem 'sprockets-rails'
gem 'puma', '~> 5.0'
gem "jsbundling-rails", "~> 1.0"
gem 'jbuilder'
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
gem 'bootsnap', require: false

gem 'slim-rails'
gem 'html2slim'

group :development, :test do
  gem 'debug', platforms: %i[mri mingw x64_mingw]
  gem "sqlite3", "~> 1.4"
  gem 'rspec-rails', '~> 6.0.0.rc1'
  gem 'factory_bot_rails', '~> 6.2'
  gem 'faker', '~> 2.21'
end

group :development do
  gem 'rubocop', require: false
  gem 'rubocop-performance', require: false
  gem 'rubocop-rails', require: false
  gem 'rubocop-rspec'
  gem 'web-console'
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end

group :production do
  gem 'pg'
end
