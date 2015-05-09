source 'https://rubygems.org'


gem 'rails', '4.2.1'
gem 'mysql2'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0', group: :doc
gem 'rails-i18n'
gem 'factory_girl_rails'
gem 'react-rails', '~> 1.0'

# asset/UI related:
# updating these may change the behavior and look of the UI
# block some time, when you plan to update!
gem 'selectize-rails', '~> 0.11.2'
gem 'font-awesome-rails', '~> 4.3'
gem 'bootstrap-sass', '~> 3.3.4.1'
gem 'bootstrap-sass-extras', '~> 0.0.6'

group :development, :test do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'i18n_viz'
  gem 'quiet_assets'
  gem 'bullet'
  gem 'web-console', '~> 2.0'
end

group :development, :test, 'test-ci' do
  gem 'capybara'
  gem 'capybara-screenshot'
  gem 'rspec-rails'
  gem 'jasminerice', git: 'https://github.com/bradphelan/jasminerice.git'
  gem 'guard-jasmine'
  gem 'guard-rspec'
  gem 'rspec-instafail'
  gem 'pry'
  gem 'pry-rails'
  gem 'pry-nav'
  gem 'pry-stack_explorer'
  gem 'pry-remote'
  gem 'json_spec', '~>1.1.4'
end

group :test, 'test-ci' do
  gem 'poltergeist'
  gem 'launchy'
  gem 'shoulda-matchers', require: false
  gem 'timecop'
  gem 'simplecov', require: false
  gem 'exifr'
end
