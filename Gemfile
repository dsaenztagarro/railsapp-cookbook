source 'https://rubygems.org'

# Uncomment these lines if you want to live on the Edge:
#
# group :development do
#   gem "berkshelf", github: "berkshelf/berkshelf"
#   gem "vagrant", github: "mitchellh/vagrant", tag: "v1.6.3"
# end
#
# group :plugins do
#   gem "vagrant-berkshelf", github: "berkshelf/vagrant-berkshelf"
#   gem "vagrant-omnibus", github: "schisamo/vagrant-omnibus"
# end

group :development do
  gem 'kitchen-vagrant'
end

# Executables provided by ChefDK
group :chef do
  gem 'librarian-chef'
  gem 'foodcritic', '~> 5.0.0'
  gem 'rspec', '~> 3.3.0'
  gem 'rubocop'
end

group :test do
  gem 'berkshelf', '~> 4.0.1'
  gem 'reek', '~> 3.5.0'
  gem 'cane', '~> 2.6.2'
  gem 'chefspec', '~> 4.4.0'
  gem 'coveralls', '~> 0.8.3'
  gem 'simplecov', '~> 0.10.0'
  gem 'simplecov-console', '~> 0.2.0'
  gem 'test-kitchen', '~> 1.4.2'
end

group :integration do
  gem 'serverspec', '~> 2.24.1'
end
