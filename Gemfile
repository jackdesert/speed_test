source 'https://rubygems.org'

gem 'rails', '3.2.13'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'sqlite3'


# Gems used only for assets and not required
# in production environments by default.
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby


gem 'jquery-rails'
gem 'rr'
gem 'pry-byebug'
gem 'exception_notification'


# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'
gem "rack"  # Update rack to 1.3.0 or later to get rid of utf8 string regex warnings
gem "unicorn"   # Some of our capybara webkit tests fail with thin, so we use unicorn
gem 'delayed_job_active_record'
gem "high_voltage"
gem "airbrake"
gem "paperclip"
gem "paperclip-meta"
gem 'aws-sdk'
gem "will_paginate"
gem "formtastic"
gem "flutie"
gem "dynamic_form"
gem "twilio-rb"
gem "clearance"
gem "aws-s3"
gem "delayed_job"
gem "heroku_san"
gem "haml-rails"
gem "chronic"
gem "mixpanel"
gem "mixpanel_client"
gem "newrelic_rpm"
gem "mongoid"
gem "bson_ext"
gem 'fancybox-rails', :git => "https://github.com/hecticjeff/fancybox-rails.git"
gem 'nokogiri'

# Gems used only for assets and not required
# in production environments by default.
  gem 'asset_sync'
  gem 'uglifier'
  gem 'jquery-ui-rails'

# A Note About Debuggers:
# -----------------------
# Used to load the 'debugger' and 'pry-debugger' gems, but then a (wimped-out) employee decided to
# develop using an IDE instead of the command line and encountered a conflict with those gems and
# his 'ruby-debug-ide' gem, i.e. his debugger would not work if the other debugger gems were included
# in the mix.
# Conditional inclusion in this 'Gemfile' screwed up 'gemfile.lock' => not a solution.
# So all references to debugger-related gems have been removed => each developer is responsible
# for loading whatever debugger gems s/he needs.
# The code contains several references to the original gems, which will screw up those who do not have
# them loaded. The solution to this problem is for those people to define an environment variable called
# 'NO_DEBUGGER' so the problem statements can be suffixed with an " unless ENV['NO_DEBUGGER'] " qualifier.
# If you need to go this route, make sure you define 'NO_DEBUGGER' at the system level and not the user one.
# For example, in Ubuntu this means adding the line "NO_DEBUGGER=true" in '/etc/environment' instead of
# the line "export NO_DEBUGGER=true" in '~/.bashrc'

# RSpec needs to be in :development group to expose generators
# and rake tasks without having to type RAILS_ENV=test.
  gem "colored"
  gem "rspec-rails"
  gem "factory_girl_rails"
  gem "steak"
  gem "rails-dev-tweaks"  # The rails-dev-tweaks gem makes it so assets are not reloaded as often. 
                          # For instance, XHR requests by themselves do not reload assets when using this gem
                          # Note that all defaults can be overridden, see the github README for this gem

  gem "getopt"
  #gem "ruby-debug19", :require => 'ruby-debug'

#group :test do
#  gem "cucumber-rails", :require => false
#  gem "factory_girl_rails"
#  gem "bourne"
#  gem "capybara"
#  gem "database_cleaner"
#  gem "fakeweb"
#  gem "sham_rack"
#  gem "nokogiri"
#  gem "timecop"
#  gem "shoulda"
#  gem "shoulda-matchers"
#  gem "email_spec", "~> 1.1"
#  gem "sham_rack"
#  gem "show_me_the_cookies"
#  gem "capybara-webkit"
#  gem "poltergeist"
#  gem "sinatra"
#  gem 'spork', '~> 1.0rc' 
#end

  gem 'guard-rspec'
  #gem 'rb-fsevent', :require => false if RUBY_PLATFORM =~ /darwin/i # guard-rspec depends on this, but only OSX operating systems don't have it already
  gem 'guard-spork'
  gem 'guard-livereload'
  gem 'letter_opener'
