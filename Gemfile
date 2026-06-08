# frozen_string_literal: true

source 'https://rubygems.org'

gemspec

# Transitive dependency of oauth2; pinned to the 2.x line to remediate
# GHSA-c32j-vqhx-rx3x (patched in 2.10.3) without taking the unnecessary
# 3.x major bump. jwt is only exercised by oauth2's private_key_jwt
# assertion flow, which this strategy does not use.
gem 'jwt', '~> 2.10', '>= 2.10.3'

group :development, :test do
  gem 'bundler', '~> 2.4'
  gem 'pry'
  gem 'rake', '~> 13.0'
  gem 'rspec', '~> 3.9.0'
  gem 'rubocop'
  gem 'rubocop-performance'
  gem 'rubocop-rspec'
  gem 'simplecov', '~> 0.22'
  gem 'simplecov-console', '~> 0.9'
end
