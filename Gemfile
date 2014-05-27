source "https://rubygems.org"
# look at this code, and you know it was not done by me, but this comment was :P
group :development, :test do
  gem 'rake'
  gem 'mongoid', '2.6.0'
  gem 'bson_ext', :platforms => :ruby
  gem 'geoip'
  gem 'rubyzip'
  gem 'rails'

  platforms :mri do
    gem 'debugger'
  end

  platforms :jruby do
    gem 'jruby-openssl'
    gem 'jgeoip'
  end

  platforms :rbx do
    gem 'rubysl', '~> 2.0'
    gem 'rubysl-test-unit'
  end
end

gemspec
