source 'https://rubygems.org'
ruby '1.9.3'
gem 'rails', '3.2.14'
 
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end
gem 'jquery-rails'
gem 'bootstrap-sass'
gem 'cancan'
gem "devise", "2.2.5"
gem 'figaro'
gem 'rolify'
gem 'simple_form'
gem 'thin'
group :development do
  gem 'better_errors'
  gem 'binding_of_caller', :platforms=>[:mri_19, :mri_20, :rbx]
  gem 'guard-bundler'
  gem 'guard-cucumber'
  gem 'guard-rails'
  gem 'guard-rspec'
  gem 'hub', :require=>nil
  gem 'quiet_assets'
  gem 'rb-fchange', :require=>false
  gem 'rb-fsevent', :require=>false
  gem 'rb-inotify', :require=>false
end
group :development, :test do
  gem 'factory_girl_rails'
  gem 'rspec-rails'
end
group :test do
  gem 'capybara'
  gem 'cucumber-rails', :require=>false
  gem 'database_cleaner', '1.0.1'
  gem 'email_spec'
  gem 'launchy'
end
gem "nifty-generators", :group => :development
gem 'validates_formatting_of'
gem 'exception_notification'

gem 'client_side_validations'
gem 'client_side_validations-simple_form'
gem "heroku"
gem 'jquery-ui-rails'
gem "font-awesome-rails"
gem 'will_paginate', '3.0.3'
gem 'bootstrap-will_paginate', '0.0.6'
gem 'roo'
gem "letter_opener", :group => :development

gem "gibbon", "0.4.6"

group :development, :test do

  gem 'sqlite3'

end


group :production do
  gem 'pg'

end
