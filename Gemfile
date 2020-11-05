source 'https://rubygems.org'
git_source(:github) {|repo|"https://github.com/#{repo}.git"}

ruby'2.6.3'

gem 'rails', '~> 6.0.2', '>= 6.0.2.2'
gem 'pg','>=0.18', '<2.0'
gem 'puma', '~>3.11'
gem 'sass-rails', '~>5'
gem 'bootstrap-sass'
gem 'webpacker', '~>4.0'
gem 'turbolinks', '~>5'
gem 'jbuilder', '~>2.5'

gem 'redis', '~>4.0'
gem 'local_time'

gem 'devise'
gem 'devise_invitable'
gem 'rolify'
gem 'cancancan'

gem 'immutable-struct'
gem 'sidekiq'
gem 'sinatra', require:nil

gem 'gravatar_image_tag'
gem 'money-rails'

gem 'slack-notifier'

# Use Active Storage variant
# gem'image_processing', '~>1.2'

#Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>=1.4.2', require:false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri]
  gem 'rspec-rails'
  gem 'rails-controller-testing'
  gem 'capybara'
  gem 'simplecov', :require => false, :group => :test
  gem "factory_bot_rails"
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background.Read more:https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem "letter_opener"
  gem 'foreman'
end

gem 'rack-cors', :require=> 'rack/cors'