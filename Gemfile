source 'https://rubygems.org'


gem 'rails', '4.1.4'

gem 'rails-api'

gem 'spring', :group => :development


#gem 'sqlite3'
gem 'tzinfo-data'

group :test do
  gem 'selenium-webdriver', '2.35.1'  # capybara dependency
  gem 'capybara', '2.1.0' #Simulate users BEHAVIOR.
  gem 'spork-rails', '4.0.0'  # To Speed up RSpec
  gem 'factory_girl_rails', '4.2.0'  #Factory to generate data
  gem 'sqlite3'
  #gem 'activerecord-sqlserver-adapter'
end

group  :development, :test do
  #gem 'sqlite3'
  gem 'rspec-rails', '2.13.1'  #access to RSpec generators
  gem 'byebug', '3.4.2'  # Successor to 'debugger'
  gem 'faker'
end

# Use Oracle in development i.e., primary or legacy db's

group :development do
  gem "activerecord-oracle_enhanced-adapter", "~> 1.5.0"
  gem 'ruby-oci8', '~> 2.1.0'
 
 # connection to sql server
 #gem 'tiny_tds'
 #gem 'activerecord-sqlserver-adapter' #, '4.0.0' #, git: 'https://github.com/rails-sqlserver/activerecord-sqlserver-adapter'
 
end
# To use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano', :group => :development

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'
