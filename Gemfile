source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 7.1.0'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 6.0', '>= 6.0.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2', '>= 4.2.2'
# gem 'therubyracer', platforms: :ruby

gem 'jquery-rails', '>= 4.3.0'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.6', '>= 2.6.4'

group :development, :test do
  gem 'byebug', platform: :mri
end

group :development do
  gem 'web-console', '>= 3.5.0'
  gem 'listen', '~> 3.1.0'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.1.0'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

### Added Gems
gem 'bootstrap-sass', '~> 3.3', '>= 3.3.6'
gem 'ransack', '~> 2.3', '>= 2.3.1'
gem 'devise', '~> 4.7', '>= 4.7.0'

gem 'data-confirm-modal', '~> 1.4', '>= 1.4.0'

gem 'cancancan', '~> 1.16'
gem 'paperclip', '~> 5.2', '>= 5.2.0'
gem 'friendly_id', '~> 5.2', '>= 5.2.1'

gem 'avatarly', '~> 1.5', '>= 1.5.1'
gem 'link_thumbnailer', '~> 3.3', '>= 3.3.1'
gem 'paperclip-cloudinary', '~> 1.3', '>= 1.3.1'

gem 'will_paginate', '~> 3.1', '>= 3.1.5'
gem 'font-awesome-rails', '~> 4.7', '>= 4.7.0.8'
gem 'social-share-button', '~> 0.9.0'

group :development, :test do
  gem 'rspec-rails', '~> 3.6', '>= 3.6.0'
  gem 'factory_girl_rails', '~> 4.9', '>= 4.9.0'
  gem 'awesome_print'
  gem 'sqlite3'
end

group :test do
  gem 'capybara', '~> 2.12', '>= 2.12.1'
  gem 'shoulda-matchers', '~> 3.1', '>= 3.1.2'
  gem 'rails-controller-testing', '~> 1.0', '>= 1.0.3'
  gem 'poltergeist', '~> 1.14', '>= 1.14.0'
  gem 'capybara-screenshot', '~> 1.0', '>= 1.0.15'
  gem 'database_cleaner', '~> 1.5', '>= 1.5.3'
  gem 'faker', '~> 1.6', '>= 1.6.3'
end

group :production do
  gem 'pg'
end
