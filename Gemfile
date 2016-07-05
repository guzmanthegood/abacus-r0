source 'https://rubygems.org'

# Core
gem 'rails', '~> 5.0.0'
gem 'puma', '~> 3.0'

gem 'uglifier', '>= 1.3.0'
gem 'jbuilder', '~> 2.5'
gem 'sprockets-rails', '~> 2.0'

gem 'turbolinks', '~> 5'
gem 'coffee-rails', '~> 4.2'
gem 'sass-rails', '~> 5.0'

# Assets
gem 'jquery-rails'
gem 'bootstrap-sass', '~> 3.3.6'
gem 'bootstrap_form'

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

group :development, :test do
  gem 'sqlite3'
  gem 'byebug', platform: :mri
end

group :test do
  gem 'rspec-rails'
  gem 'database_cleaner'
  gem 'poltergeist'
  gem 'factory_girl_rails'
  gem 'capybara'
  gem 'capybara-screenshot'
  gem 'headless'
  gem 'timecop'
  gem 'fuubar'
end

group :development do
  gem 'web-console'
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'letter_opener_web'
  gem 'better_errors'
  gem 'binding_of_caller'
end

group :production do
  gem 'pg'
  gem 'rails_12factor'
end

# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'
# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development