source 'http://rubygems.org'

gem 'rails', '3.1.0'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', "  ~> 3.1.0"
  gem 'coffee-rails', "~> 3.1.0"
  gem 'uglifier'
  gem 'therubyracer'
  gem 'therubyracer'
end

gem 'jquery-rails'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'

# Added by Tina per instructions in Section 3.9 of ELLS
# use Haml for templates
gem 'haml'

# use Ruby debugger
group :development, :test do
  gem 'ruby-debug19'
  gem 'sqlite3' # moved to the group :development :test block by Tina per ELLS A.8
end

# The following was added by Tina per instructions in ELLS A.8
group :production do
  gem 'pg'
end
