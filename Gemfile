source 'https://rubygems.org'

ruby '2.0.0'

gem 'rails', '4.0.0.rc1'  
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'    
gem 'jbuilder', '~> 1.0.1'
gem 'better_errors'
gem 'therubyracer'
gem 'less-rails-bootstrap'
gem 'twitter-bootstrap-rails', :git => 'git://github.com/seyhunak/twitter-bootstrap-rails.git'

# The asset_sync gem is WELL worth using
# but you should read more about it before deciding
# https://github.com/rumblelabs/asset_sync
# gem 'asset_sync'

# only want sqlite in dev and test envs
group :development, :test do
  gem 'sqlite3'
end

group :production do
  gem 'pg' # dont want sqlite in production
  gem 'unicorn'
  gem 'hooves'
  gem 'rails_12factor'
end

group :doc do
  gem 'sdoc', require: false
end