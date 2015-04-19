source 'https://rubygems.org'
gemspec development_group: :gem_build_tools

group :development do
  gem 'guard-rspec'
  gem 'rb-fsevent', '~> 0.9.1' if RUBY_PLATFORM =~ /darwin/
end

group :test do
  gem 'rspec', '~> 3.2'
end

group :gem_build_tools do
  gem 'rake'
end

group :test do
  gem 'benchmark_suite'
  gem 'rspec', '~> 3.2'
  gem 'rspec-retry'
end

gem 'coveralls', require: false
gem 'celluloid', github: 'celluloid/celluloid', branch: '0.17.0-prerelease'
