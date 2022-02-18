source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "2.7.0"

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 7.0.2", ">= 7.0.2.2"

# Until a new release is cut that includes:
# https://github.com/rails/sprockets/pull/714
# https://github.com/rails/sprockets/pull/717
gem "sprockets", github: "rails/sprockets", branch: "master"
gem "sprockets-rails", '>= 3.4.2'

# Use the Puma web server [https://github.com/puma/puma]
gem "puma", "~> 5.0"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

gem 'dartsass-rails'
# gem 'dartsass-rails', git: 'https://github.com/chipairon/dartsass-rails.git', branch: 'configurable-load-paths'
# gem 'dartsass-rails', path: '../dartsass-rails'

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  # gem "spring"
end
