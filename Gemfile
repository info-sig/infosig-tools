# frozen_string_literal: true

source 'https://rubygems.org'

ruby RUBY_VERSION

gem 'rake'
gem 'timecop'

group :development, :test do
  gem 'pry'
  gem 'activesupport', '~> 6.0.3', '>= 6.0.3.7'
  # gem 'sidekiq-scheduler'
  gem 'sidekiq', '~> 5'
  gem 'sequel'
  gem 'ramda-ruby'
  gem 'concurrent-ruby'
  gem 'redlock', '~> 1' # version 1 is needed for tests to pass
end

group :test do
  gem 'minitest'
  gem 'minitest-parallel_fork', require: false
  gem 'rack-test'
  gem 'concurrent-ruby'

  # gem "webmock"
  # gem 'vcr'
  gem 'm', '~> 1.5.0'
  # gem 'timecop'
end

gemspec
