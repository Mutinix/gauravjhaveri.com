source 'https://rubygems.org'

ruby '2.1.0'
#ruby-gemset=ruby-2.1.0

gem 'rails', '3.2.13'

group :development do
  gem 'sqlite3'
end

group :production do
  gem 'pg'
  # Gem to skip plugin injection
  gem 'rails_12factor'
end


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
  gem 'zurb-foundation'
end

gem 'jquery-rails'
gem 'figaro'

# Jekyll blog
gem 'bloggy'

# High Voltage for static pages
gem 'high_voltage'