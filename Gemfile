source 'https://rubygems.org'

group :development, :production, :test do
  gem 'sinatra'     , '2.0.5' , require: 'sinatra/base'
  gem 'mongoid'     , '7.0.1'
  gem 'arkaan'      , '1.9.0'
  gem 'virtuatable' , '0.6.1'
  gem 'require_all' , '3.0.0'
  gem 'platform-api'
  
  gem 'capistrano'        , '3.11.0'
  gem 'capistrano-bundler', '1.5.0'
  gem 'capistrano-rvm'    , '0.1.1'
  gem 'dotenv', '2.7.2'
end

group :developement, :production do
  gem 'rake'
end

group :development, :test do
  gem 'pry'                    , '0.11.1'
  gem 'rack-test'              , '0.7.0' , require: 'rack/test'
  gem 'rspec'                  , '3.6.0'
  gem 'rspec-mocks'            , '3.6.0'
  gem 'factory_girl'           , '4.8.1'
  gem 'simplecov'              , '0.15.1'
  gem 'database_cleaner'       , '1.6.1'
  gem 'bcrypt'                 , '3.1.11'
  gem 'rubocop'                , '0.74'
  gem 'rspec-json_expectations', '2.1.0', require: 'rspec/json_expectations'
  gem 'yard'                   , '0.9.20'
  gem 'rspec_junit_formatter'  , '0.4.1'
end