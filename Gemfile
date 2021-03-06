source 'https://rubygems.org'
gem 'rails', '4.2.5'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'soundcloud'
gem 'sdoc', '~> 0.4.0', group: :doc

group :development, :test do
  gem 'byebug'
  gem 'sqlite3'
end

group :development do
  gem 'web-console', '~> 2.0'
  gem 'spring'
end

gem 'thin'
gem 'slim-rails'
gem 'haml-rails'
gem 'bootstrap-sass'
gem 'font-awesome-sass'
gem 'simple_form'
gem 'high_voltage'
gem 'devise'
gem 'pundit'

group :development do
  gem 'guard-bundler'
  gem 'guard-minitest'
  gem 'guard-livereload'
  gem 'rack-livereload'
  gem 'better_errors'
  gem 'binding_of_caller', platforms: :mri_21
  gem 'quiet_assets'
  gem 'pry-byebug'
  gem 'pry-rails'
  gem 'rails_layout'
  gem 'rails_best_practices'
  gem 'rails_apps_pages'
  group :linux do
    gem 'libnotify', require: false
  end
  group :darwin do
    gem 'growl', require: false
  end
end

gem 'minitest-rails'
group :test do
  gem 'minitest-reporters'
  gem 'minitest-rails-capybara'
  gem 'faker'
end

group :production do
  gem 'rails_12factor'
  gem 'pg'
end
