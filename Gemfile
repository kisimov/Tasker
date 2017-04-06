source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.0.2'
gem 'jquery-rails'
gem 'twitter-bootstrap-rails', '~> 4.0'
gem 'simple_form'

group :assets do
  gem 'sass-rails', '~> 5.0'
  gem 'uglifier', '>= 1.3.0'
  gem 'coffee-rails', '~> 4.2'
  gem 'therubyracer', '~> 0.12.3', platforms: :ruby
end

group :production do
  gem 'pg'
end

group :development, :test do
  gem 'byebug'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'sqlite3'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
