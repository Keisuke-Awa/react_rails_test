# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

gem 'rails', '~> 5.1.6'

gem 'mysql2'

gem 'sass-rails', '~> 5.0'

gem 'uglifier', '>= 1.3.0'

gem 'coffee-rails', '~> 4.2', '>= 4.2.2'

gem 'jquery-rails'

gem 'jbuilder', '~> 2.0'

gem 'sdoc', '~> 0.4.0', group: :doc

gem 'dotenv-rails'

gem 'webpacker'

group :development, :test do
  gem 'byebug'
  gem 'rspec-rails'
  #Adds step-by-step debugging and stack navigation capabilities to pry using byebug.
  gem 'pry-byebug'
  gem 'factory_bot_rails'
  # Helps to kill N+1 queries and unused eager loading
  gem 'bullet'
  gem 'active_decorator-rspec'
  gem 'timecop'

  gem 'faker'

  gem 'seed-fu', '~> 2.3', '>= 2.3.7'
end


group :test do
  gem 'database_rewinder'
  gem 'launchy'
  gem 'selenium-webdriver'
  gem 'capybara'
  gem 'capybara-email'
  gem 'email_spec'
  gem "rails-controller-testing"
  gem "chromedriver-helper"
end

group :development do

  gem 'web-console', '~> 3.0'

  gem 'spring'

  gem 'spring-commands-rspec'

end
