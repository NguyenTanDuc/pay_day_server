source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "2.5.3"

gem "rails", "~> 5.2.2"
gem "mysql2", ">= 0.4.4", "< 0.6.0"
gem "puma", "~> 3.11"
gem "webpacker"
gem "bootsnap", ">= 1.1.0", require: false

group :development, :test do
  gem "pry-byebug"
  gem "pry"
  gem "rspec-rails"
  gem "factory_girl_rails"
  gem "rubocop", require: false
  gem "rubocop-checkstyle_formatter", require: false
end

group :development do
  gem "listen", ">= 3.0.5", "< 3.2"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
