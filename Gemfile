source 'https://rubygems.org'
ruby '2.1.5'
gem 'rails', '4.2.0'
gem 'pg'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0', group: :doc
gem 'omniauth-facebook'
gem 'koala', '~> 2.0'


group :production do
  gem 'thin'
  gem 'rails_12factor'  
end


group :development, :test do
	gem 'thin'
	gem 'rb-fsevent', '>= 0.9.1'
	gem 'rails-dev-tweaks', '~> 1.1'
gem 'rails-dev-boost', :git => 'git://github.com/thedarkone/rails-dev-boost.git'

  # Call 'byebug' anywhere , '~1.6.3'in the code to stop execution and get a debugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end