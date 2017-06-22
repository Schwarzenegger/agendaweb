source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.0.2'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'pg'
gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem "bower-rails", "~> 0.11.0"
gem 'kaminari'
gem "therubyracer"
gem "less-rails" #Sprockets (what Rails 3.1 uses for its asset pipeline) supports LESS
gem 'twitter-bootstrap-rails'
gem 'devise'
gem 'devise-i18n'
gem 'sprockets', '3.6.3'
gem 'enum_help'
gem "pundit"
gem "pry-rails"
gem "rails-erd"
gem 'font-awesome-rails'
gem 'carrierwave'
gem 'paper_trail'
gem 'rails_admin', '~> 1.2'
gem 'ransack'
gem 'prawn'
gem 'prawn-rails'
gem 'prawn-table'

gem 'rubyzip', '~> 1.1.0'
gem 'axlsx', '2.1.0.pre'
gem 'axlsx_rails'
gem 'ransack'

group :development, :test do
  gem 'rspec-rails', '~> 3.5'
  gem 'shoulda-matchers', :require => false
  gem 'byebug', platform: :mri
  gem 'factory_girl_rails'
  gem 'faker'
  gem 'sqlite3'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
