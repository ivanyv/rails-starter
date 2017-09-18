# frozen_string_literal: true

source 'https://rubygems.org'
ruby '2.4.1'

# Rails
gem 'rails', '~> 5.1.4'

# ActiveRecord
gem 'pg', '~> 0.18'

# Orchestration
gem 'puma', '~> 3.10'
gem 'foreman', '~> 0.84'
gem 'dotenv-rails', '~> 2.1'

# Asset processing
gem 'sassc-rails', '~> 1.2'
gem 'uglifier', '>= 1.3'
gem 'coffee-rails', '~> 4.2'
gem 'non-stupid-digest-assets'

# Views
gem 'slim-rails', '~> 3.1'
gem 'simple_form', '~> 3.5'

# Assets
gem 'jquery-rails'
gem 'turbolinks', '~> 5'

# API builder
gem 'jbuilder', '~> 2.5'

# Background jobs
gem 'sidekiq'

# Logging
gem 'lograge', '~> 0.6'

group :development, :test do
  # Debugging
  gem 'byebug', platform: :mri

  # Testing
  gem 'factory_girl_rails'
  gem 'faker'

  # Code Quality
  gem 'rubocop', require: false
end

group :development do
  # Debugging
  gem 'web-console', '~> 3.3'
  gem 'listen', '~> 3.0'

  # Preloading
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0'

  # Testing
  gem 'letter_opener'
  gem 'meta_request'
  gem 'overcommit', require: false
end

group :test do
  # Testing
  gem 'mocha'
  gem 'webmock'
  gem 'capybara'
  gem 'poltergeist'
end
