source 'https://rubygems.org'
ruby '2.0.0'

gem 'rails', '4.0.3'
gem 'bootstrap-sass', '2.3.2.0'
gem 'bcrypt-ruby'
gem 'faker', '1.1.2'
gem 'will_paginate', '3.0.4'
gem 'bootstrap-will_paginate', '0.0.9'

gem 'sass-rails', '~> 4.0.0'
gem 'uglifier', '2.1.1'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 1.2'
gem 'sprockets', '2.11.0'

group :production do
	gem 'pg'
#	gem 'rails_12factor' specifically for heroku
end

group :doc do
  gem 'sdoc', '0.3.20', require: false
end

group :development, :test do 
	gem 'debugger'
	gem 'sqlite3'
	gem 'rspec-rails', '2.13.1'
	gem 'guard-rspec', '2.5.0'
	gem 'spork-rails', github: 'sporkrb/spork-rails'
	gem 'guard-spork', '1.5.0'
	gem 'childprocess'
	gem 'launchy'
end

group :test do
	gem 'selenium-webdriver', '~> 2.35.1'
	gem 'capybara'
	# gem 'libnotify', '0.8.0' for LINUX
	gem 'growl', '1.0.3' # for MacOSX
	gem 'cucumber-rails', '1.4.0', :require => false
  gem 'database_cleaner', github: 'bmabey/database_cleaner'
  gem 'factory_girl_rails', '4.2.1'
end


# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
