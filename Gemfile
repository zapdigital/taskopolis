source "https://rubygems.org"

ruby "2.3.1"

gem "autoprefixer-rails"
gem "flutie"
gem "jquery-rails"
gem "normalize-rails", "~> 3.0.0"
gem "pg"
gem "puma"
gem "rack-canonical-host"
gem "rails", "~> 5.0.0"
gem "recipient_interceptor"
gem "sass-rails", "~> 5.0"
gem "simple_form"
gem "sprockets", ">= 3.0.0"
gem "suspenders"
gem "title"
gem "uglifier"
gem "devise"
gem "sidekiq"
gem "slim"
gem "slim-rails"
gem "raygun4ruby"
gem "high_voltage"
gem "merit"

group :development do
  gem "listen"
  gem "spring"
  gem "spring-commands-rspec"
  gem "web-console"
  gem "guard"
  gem "guard-livereload"
  gem "rack-livereload"
  gem "rb-fsevent"
end

group :development, :test do
  gem "awesome_print"
  gem "bullet"
  gem "bundler-audit", ">= 0.5.0", require: false
  gem "dotenv-rails"
  gem "factory_girl_rails"
  gem "pry-byebug"
  gem "pry-rails"
  gem "rspec-rails", "~> 3.5.0.beta4"
  gem "rspec-sidekiq"
end

group :development, :staging do
  gem "rack-mini-profiler", require: false
end

group :development, :staging, :test do
  gem "ffaker"
end

group :test do
  gem "capybara"
  gem "database_cleaner"
  gem "formulaic"
  gem "launchy"
  gem "shoulda-matchers"
  gem "simplecov", require: false
  gem "timecop"
  gem "webmock"
end

group :staging, :production do
  gem "rack-timeout"
  gem "rails_stdout_logging"
end
