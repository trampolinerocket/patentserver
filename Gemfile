source 'http://rubygems.org'

gem 'rails'
gem "twitter-bootstrap-rails"
gem 'jquery-rails'

group :production do
  gem 'pg'
end


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platform => :ruby
  gem 'uglifier', '>= 1.0.3'
end


group :development do
  gem 'rails_best_practices'
end

group :test, :development do
  gem 'sqlite3'
  gem 'pry-rails'
  gem 'spork'
  gem 'rspec-rails'
#  gem 'ruby-debug19', :require => 'ruby-debug'
end

group :test do
  gem 'cucumber-rails'
end