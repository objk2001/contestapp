source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.5'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.2', '>= 6.0.2.1'

group :production do
  gem 'pg', '1.2.2'
  gem 'rails_12factor', '0.0.2'
end

# Use sqlite3 as the database for Active Record
group :development, :test do
gem 'sqlite3', '~> 1.4.2'
  # Helpful gems
  gem "better_errors" # improves error handling
  gem "binding_of_caller" # used by better errors

  # Testing frameworks
  gem 'rspec-rails' # testing framework
  #gem "factory_girl_rails" # use factories, not fixtures
  gem "factory_bot_rails"
  #gem "capybara" # simulate browser activity
  gem "fakeweb"

  # Automated testing
  gem 'guard' # automated execution of test suite upon change
  gem "guard-rspec" # guard integration with rspec

  # Only install the rb-fsevent gem if on Max OSX
  # gem 'rb-fsevent' # used for Growl notifications
end

# Use Puma as the app server
gem 'puma', '~> 4.1'
# Use SCSS for stylesheets
gem 'sass-rails', '>= 6'
gem "execjs"
gem "twitter-bootstrap-rails"
gem "bootstrap-sass"
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 4.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
