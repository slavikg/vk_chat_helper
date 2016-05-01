source 'https://rubygems.org'

ruby '2.2.1'

gem 'rails', '4.0.2'

gem 'sqlite3'

# Haml for Layout
gem 'haml-rails'

# Env
gem 'figaro'

# Pretty debug
gem 'awesome_print'

group :development do
  gem 'spring'
  gem 'spring-commands-rspec'
end

group :test do
  gem 'timecop'
  gem 'webmock'
  gem 'simplecov', require: false
  # This gem installs the following gems: capybara, minitest, minitest-rails, minitest-capybara
  gem 'minitest-rails-capybara'
  gem 'poltergeist'
  gem 'database_cleaner'
end

group :production, :staging do
  gem 'rails_12factor'
end

# others

gem 'sass-rails', '~> 4.0.0'

gem 'uglifier', '>= 1.3.0'

gem 'coffee-rails', '~> 4.0.0'

gem 'jquery-rails'

gem 'turbolinks'

# gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end
