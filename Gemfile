source 'https://rubygems.org'

gem 'rake', '>= 10.0'
gem 'activerecord', ENV['AR'] ? ENV['AR'].split(",") : [">= 6.0.0", "< 8.0"]
gem 'railties', ENV['AR'] ? ENV['AR'].split(",") : [">= 6.0.0", "< 8.0"]
gem 'nokogiri', "~> 1.14"

group :dev do
  gem 'sqlite3', '< 1.7'
  gem 'rspec', '>= 2.99.0'
  gem 'jeweler'
end
