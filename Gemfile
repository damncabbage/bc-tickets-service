source 'https://rubygems.org'

gem 'rails', '3.2.12'
gem 'thin'
gem 'sqlite3'

group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'
  gem 'uglifier'
  gem 'libv8'
  gem 'therubyracer', :platform => :ruby, :require => 'v8'
end

# Ticket Generation
gem 'haml-rails'
gem 'wicked_pdf'
gem 'wkhtmltopdf'
gem 'qrencoder' # requires 'brew install qrencode' or 'apt-get install libqrencode-dev'

group :development do
  gem 'quiet_assets'
  gem 'better_errors'
end

group :development, :test do
  gem 'rspec-rails'
  gem 'capybara'
  gem 'factory_girl_rails'
end
