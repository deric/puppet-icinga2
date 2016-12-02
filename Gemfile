source 'https://rubygems.org'
puppetversion = ENV.key?('PUPPET_VERSION') ? "#{ENV['PUPPET_VERSION'].to_s}" : ">= 3.8"
jsonversion = ENV['TRAVIS_RUBY_VERSION'].to_i <= 2 ? "1.8.3" : "~> 2.0"
gem 'puppet', puppetversion
gem 'puppetlabs_spec_helper', '>= 0.1.0'
gem 'puppet-lint', '>= 0.3.2'
gem 'facter', '>= 1.7.0'
gem 'rspec-puppet-facts', '>= 1.6.0'
gem 'json', jsonversion
gem 'json_pure', jsonversion
