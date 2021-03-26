# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.0'

gem 'bootsnap', '>= 1.4.4', require: false
gem 'pg', '~> 1.1'
gem 'puma', '~> 5.0'
gem 'rails', '~> 6.0.3'

gem 'bson_ext', '~> 1.5'
gem 'devise', '~> 4.7'
gem 'mongoid', '~> 7.2'
gem 'mongoid_search', '~> 0.4.0'
gem 'pundit', '~> 2.1'

group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'database_cleaner', '~> 2.0'
  gem 'factory_bot_rails', '~> 6.1'
  gem 'faker', '~> 2.17'
  gem 'mongoid-rspec', '~> 4.1'
  gem 'pry', '~> 0.14.0'
  gem 'rspec-rails', '~> 5.0'
  gem 'rubocop', '~> 0.90.0', require: false
end

group :development do
  gem 'listen', '~> 3.3'
  gem 'spring'
end

gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
