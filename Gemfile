# frozen_string_literal: true

source 'https://rubygems.org'

# we cannot use gemspec here because it would load pagy before simplecov
# and miss files from coverage gemspec

group :test do
  gem 'activesupport'
  gem 'i18n'
  gem 'minitest'
  gem 'minitest-reporters'
  gem 'oj', require: false     # false is for testing with or without it
  gem 'rack'
  gem 'rackup'
  gem 'rake-manifest'
  gem 'rematch'
  gem 'rubocop'
  gem 'rubocop-minitest'
  gem 'rubocop-packaging'
  gem 'rubocop-performance'
  gem 'rubocop-rake'
  gem 'simplecov', require: false
end

group :apps do
  gem 'puma'
  gem 'rerun'
  gem 'rouge'
  gem 'sinatra'
  gem 'sinatra-contrib'
end

group :performance do
  gem 'benchmark-ips'
  gem 'kalibera'
  gem 'memory_profiler'
end
