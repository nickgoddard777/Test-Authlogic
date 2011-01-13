source 'http://rubygems.org'

gem 'rails', '3.0.3'
gem "authlogic"
gem "rails3-generators"

# Deploy with Capistrano
gem 'capistrano'

# Bundle the extra gems:
# gem 'bj'
# gem 'nokogiri'
# gem 'sqlite3-ruby', :require => 'sqlite3'
# gem 'aws-s3', :require => 'aws/s3'

# Bundle gems for the local environment. Make sure to
# put test-only gems in this group so their generators
# and rake tasks are available in development mode:
group :development, :test do
	gem 'sqlite3-ruby', '1.3.2', :require => 'sqlite3'
	gem 'rspec-rails', '2.3.0'
	gem 'annotate-models', '1.0.4'
	gem 'faker', '0.3.1'
end

group :test do
	gem 'sqlite3-ruby', '1.3.2', :require => 'sqlite3'
	gem 'rspec', '2.3.0'
	gem 'webrat', '0.7.1'
	gem 'factory_girl_rails', '1.0'
end