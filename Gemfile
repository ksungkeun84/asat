source 'https://rubygems.org'

#ruby '2.1.5'
ruby '2.2.8'

gem 'rails', '4.2.1'

gem 'validates_email_format_of'

gem 'delayed_job_active_record'

group :development do
  gem 'annotate'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'web-console', '~> 2.0'
end

group :production do
  gem 'thin'
  gem 'pg'
  gem 'rails_12factor'
  gem 'responders', '~> 2.0'
  gem 'pluck_to_hash'
end

# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
gem 'bootstrap-sass', '~> 3.3.3'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

gem 'sorcery'

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  gem 'rspec-rails', '3.4.2'
  gem 'sqlite3'
  gem 'pluck_to_hash'

  # Access an IRB console on exception pages or by using <%= console %> in views
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]


group :test do
   gem 'cucumber-rails', :require => false
   gem 'cucumber-rails-training-wheels' # some prefabbed step definition
   gem 'database_cleaner' # to clean cucumbers test database between runs
   gem 'capybara' # lets cucumber pretend to be a web browser
   gem 'launchy' # a useful debuggin aid for user stories
   gem 'simplecov', :require => false
end 


gem 'pluck_to_hash'
