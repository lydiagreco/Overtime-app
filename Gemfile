git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.1.4'
gem 'pg', '~> 0.18'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'


group :development, :test do
  gem 'byebug'
  gem 'rspec-rails', '~> 3.0'
  gem 'capybara'
  gem 'database_cleaner'
  gem 'factory_bot_rails'
end


group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem 'devise', '~> 4.7'
gem 'bootstrap-sass', '~> 3.3', '>= 3.3.7'
gem 'gritter', '~> 1.2'
gem 'administrate', '~> 0.8.1'
gem 'bourbon', '~> 5.0'
gem 'pundit', '~> 1.1'
gem 'puma', '~> 3.11'
gem 'twilio-ruby', '~> 5.6', '>= 5.6.1'
gem 'dotenv-rails', groups: [:development, :test]
gem 'kaminari', '~> 1.1', '>= 1.1.1'
gem 'rails_12factor'
