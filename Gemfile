#source 'https://rubygems.org'
source 'https://ruby.taobao.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.7'
# Use sqlite3 as the database for Active Record
#gem 'sqlite3'
gem 'pg'



# Use Puma as the app server
# gem 'puma', '~> 3.0'


# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'


gem 'sdoc','~> 0.4.0',group: :doc
gem 'unicorn'
gem 'seed-fu'

gem 'dotenv-rails'
gem 'pry'
gem 'pry-rails'
gem 'pry-byebug'

gem 'grape'
gem 'grape-active_model_serializers'
gem 'grape-middleware-logger'




gem 'rake','>=10.2.2'
gem 'rack-cors',:require => 'rack/cors'

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'

gem 'redis-rails'
gem 'redis-namespace'
gem 'redis-objects'

# Use ActiveModel has_secure_password
gem 'bcrypt', '~> 3.1.7'




gem 'whenever',:require => false
gem 'rollbar'

#Excel parsing/importing
gem 'roo'
gem 'spreadsheet'
gem 'highline'

#Excel export
gem 'rubyzip','~> 1.1.0'
gem 'axlsx','~> 2.1.0.pre'
gem 'axlsx_rails'
gem 'axlsx_styler'

#异步消息
gem 'sidekiq'
gem 'sidekiq-unique-jobs'
gem 'sinatra',require:false



# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development
=begin

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end
=end



group :development, :test do
  gem 'byebug'
  gem 'faker'
  gem 'overcommit'
  gem 'fasterer'
end

group :test do
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'database_cleaner'
  gem 'timecop'
  gem 'simplecov',:require => false
end

group :development do
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'listen', '~> 3.0.5'

  gem 'capistrano','3.4.0'
  gem 'capistrano-bundler'
  gem 'capistrano-rbenv'
  gem 'capistrano-rails-console'
  gem 'capistrano-rails-tail-log'
  gem 'capistrano-sidekiq'
  gem 'capistrano-env-config'
  gem 'thin'
  gem 'web-console','~> 2.0'
  gem 'spring'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'rails_best_practices'
  gem 'did_you_mean','= 1.0.0'
  gem 'w3c_validators'
  gem 'brakeman',:require => false
  gem 'rubocop',:require => false
  gem 'reek',require: false
end



gem 'time_diff'


# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
