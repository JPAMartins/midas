source 'https://rubygems.org'

git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.1.3'

gem 'rails', '~> 7.0.4'
gem 'mysql2', '>= 0.4.4', '< 0.6.0'
gem 'puma', '~> 3.11'
gem 'bootsnap', '>= 1.1.0', require: false

group :development, :test do
  gem "rspec-rails"
  gem "factory_bot_rails"
  gem "faker"
  gem 'pry-byebug'
end

group :development do
  gem 'rubocop'
  gem 'rubocop-rspec'
  gem 'rubocop-performance'
  gem 'rubocop-rails'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.1.0'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
