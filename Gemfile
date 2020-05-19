source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.2.4', '>= 5.2.4.3'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0', '>= 5.0.6'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2', '>= 4.2.2'
# gem 'therubyracer', platforms: :ruby

gem 'jquery-rails', '>= 4.2.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.6', '>= 2.6.4'

group :development, :test do
  gem 'byebug', platform: :mri
end

group :development do
  gem 'web-console', '>= 3.4.0'
  gem 'listen', '~> 3.0.5'
  gem 'spring', '>= 2.0.1'
  gem 'spring-watcher-listen', '~> 2.0.1'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

### Added Gems
gem 'bootstrap-sass', '~> 3.3', '>= 3.3.6'
gem 'ransack', '~> 1.8', '>= 1.8.2'
gem 'devise', '~> 4.4', '>= 4.4.2'

gem 'data-confirm-modal', '~> 1.3', '>= 1.3.0'

gem 'cancancan', '~> 1.16'
gem 'paperclip', '~> 5.1', '>= 5.1.0'
gem 'friendly_id', '~> 5.2', '>= 5.2.0'

gem 'avatarly', '~> 1.5'
gem 'link_thumbnailer', '~> 3.3', '>= 3.3.0'
gem 'paperclip-cloudinary', '~> 1.3'

gem 'will_paginate', '~> 3.1', '>= 3.1.5'
gem 'font-awesome-rails', '~> 4.7', '>= 4.7.0.4'
gem 'social-share-button', '~> 0.8.8'

group :development, :test do
  gem 'rspec-rails', '~> 3.5', '>= 3.5.2'
  gem 'factory_girl_rails', '~> 4.8', '>= 4.8.0'
  gem 'awesome_print'
  gem 'sqlite3'
end

group :test do
  gem 'capybara', '~> 2.12'
  gem 'shoulda-matchers', '~> 3.1', '>= 3.1.1'
  gem 'rails-controller-testing', '~> 1.0', '>= 1.0.1'
  gem 'poltergeist', '~> 1.13'
  gem 'capybara-screenshot', '~> 1.0', '>= 1.0.14'
  gem 'database_cleaner', '~> 1.5', '>= 1.5.3'
  gem 'faker', '~> 1.6', '>= 1.6.3'
end

group :production do
  gem 'pg'
end
