source 'https://rubygems.org'

# Specify your gem's dependencies in google-apis.gemspec
gemspec


group :development do
  gem 'bundler', '~> 1.7'
  gem 'rake', '~> 10.0'
  gem 'rspec', '~> 3.1'
  gem 'json_spec', '~> 1.1'
  gem 'webmock', '~> 1.21'
  gem 'simplecov', '~> 0.9'
  gem 'coveralls', '~> 0.7.11'
  gem 'rubocop', '~> 0.29'
  gem 'launchy', '~> 2.4'
  gem 'dotenv', '~> 2.0'
  gem 'fakefs', '~> 0.6', require: "fakefs/safe"
  gem 'googleauth', '~> 0.4.2'
end

platforms :jruby do
  group :development do
  	gem 'jruby-openssl'
  end
end

platforms :ruby do
  group :development do
    gem 'yard', '~> 0.8'
    gem 'redcarpet', '~> 3.2'
    gem 'github-markup', '~> 1.3'
    gem 'pry-doc', '~> 0.8'
    gem 'pry-byebug', '~> 3.2'
  end
end

if ENV['RAILS_VERSION']
  gem 'rails', ENV['RAILS_VERSION']
end
