source 'https://rubygems.org'
git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

ruby '2.5.3'

gem 'rails', '5.1.6'
gem 'puma', '3.12.0'
gem 'sass-rails', '5.0.7'
gem 'uglifier', '4.1.19'
gem 'coffee-rails', '4.2.2'
gem 'turbolinks', '5.2.0'
gem 'jbuilder', '2.7.0'

gem 'pg', '1.1.3'
gem 'jquery-rails', '4.3.3'

group :development, :test do
  gem 'byebug', '10.0.2', platforms: [:mri, :mingw, :x64_mingw]
  gem 'capybara', '2.18.0'
  gem 'selenium-webdriver', '3.14.1'
end

group :development do
  gem 'web-console', '3.7.0'
  gem 'listen', '3.1.5'
  gem 'spring', '2.0.2'
  gem 'spring-watcher-listen', '2.0.1'
end

gem 'tzinfo-data', '1.2018.7', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
