source 'http://rubygems.org'

gem 'rails', '~> 3.2.0'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'
  gem 'uglifier'
end

gem 'jquery-rails'

gem 'mongoid'
gem 'bson_ext'

gem 'haml'
gem 'haml-rails'
gem 'aws-s3'
gem 'mongoid-paperclip'
gem 'dynamic_form'

gem 'omniauth' 
gem 'omniauth-facebook'
gem 'omniauth-twitter'
gem 'omniauth-google-oauth2'
gem 'omniauth-identity'
gem 'bcrypt-ruby'

gem 'stripe'

group :production do
  gem 'thin'
end

group :development do
  gem 'taps'
  gem 'unicorn'
  gem 'hpricot'
end

group :test, :development do
  gem 'capistrano'
  gem 'capistrano_colors'
  gem 'capybara'
  gem 'database_cleaner'
  gem 'email_spec' 
  gem 'factory_girl_rails'
  gem 'fakeweb'
  gem 'launchy'
  gem 'mongoid-rspec'
  gem 'pry-rails'
  gem 'pry-debugger'
  gem 'rspec-rails'
  gem 'timecop'
  gem 'vcr'

  # Pretty printed test output
  gem 'turn'

  gem 'simplecov'
  gem 'simplecov-rcov'
end

