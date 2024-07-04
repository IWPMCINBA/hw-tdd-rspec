source 'https://rubygems.org'

ruby '2.6.6'
gem 'rails', '4.2.9'

# For Heroku deployment - as described in Ap. A of ELLS book
group :development, :test do
  gem 'sqlite3'
  gem 'byebug'
  gem 'database_cleaner', '1.4.1'
  gem 'capybara', '2.4.4'
  gem 'launchy'
  gem 'rspec-rails', '3.3.2'
  gem 'ZenTest', '~> 4.12.0' # Updated ZenTest version
end

group :test do
  gem 'cucumber-rails', require: false
  gem 'cucumber-rails-training-wheels'
  gem 'simplecov', require: false
end

group :production do
  gem 'pg'
end

# Gems used only for assets and not required
# in production environments by default.
gem 'sass-rails', '~> 5.0.3'
gem 'coffee-rails', '~> 4.1.0'
gem 'uglifier', '>= 2.7.1'

gem 'jquery-rails'
gem 'haml'

# Nokogiri with system libraries configuration
gem 'nokogiri', '~> 1.8', '>= 1.8.1', platforms: :ruby, require: false

# Specify a compatible version of ffi
gem 'ffi', '~> 1.15'
