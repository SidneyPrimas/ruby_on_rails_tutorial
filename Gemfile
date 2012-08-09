source 'https://rubygems.org'

gem 'rails', '3.2.7'

#Since sqlite3 is used for local testing, we make sure to only include it in the development environment. 
#A different database will be used int he actual environemnt. In this case heroku
group :development do
  gem 'sqlite3', '1.3.5'
end


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '3.2.4'
  gem 'coffee-rails', '3.2.2'

  gem 'uglifier', '1.2.3'
end

gem 'jquery-rails', '2.0.2'
