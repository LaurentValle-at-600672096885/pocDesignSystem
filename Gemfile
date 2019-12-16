source 'https://rubygems.org'

ruby '~> 2.6.3'

gem 'fastlane', '2.137.0'
gem 'cocoapods', '1.8.3'
gem 'aws-sdk-s3'

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval_gemfile(plugins_path) if File.exist?(plugins_path)
