source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
#gem 'pry'
#gem 'pry-remote'
#gem 'pry-stack_explorer'
#gem 'pry-debugger'

group :development, :test , :production do
  gem 'rails', '4.2.5'
end

group :development do
  gem 'pry'
# Use sqlite3 as the database for Active Record
#gem 'sqlite3'
  gem 'mysql2', '>= 0.3.13', '< 0.5'

  gem 'hoe', '~> 3.14', '>= 3.14.2'
  gem 'rake-compiler', '~> 0.9.5'
  gem 'cucumber', '~> 2.1'
  gem 'rspec-rails', '2.9.0'
end

# Use SCSS for stylesheets
group :assets do
  gem 'sass-rails', '~> 4.0.3'
  # Use Uglifier as compressor for JavaScript assets
  gem 'uglifier', '>= 1.3.0'
  # Use CoffeeScript for .coffee assets and views
  gem 'coffee-rails', '~> 4.1.0'
end
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

gem 'nokogiri', '>= 1.6.7.rc'
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
end

group :test do
  gem 'capybara', '1.1.2'
end


group :development do
  gem 'spring'
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
end

group :production do
  #ruby '2.2.2', :engine => 'jruby', :engine_version => '9.0.0.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
# gem 'rails', '4.1.8'
# Use postgresql as the database for Active Record
  gem 'activerecord-jdbcpostgresql-adapter'
  gem 'rails_12factor'
  # gem 'pg', '0.12.2'
end

gem 'puma'
# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
