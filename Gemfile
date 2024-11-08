source "https://rubygems.org"

gem 'rb-readline'
gem "fastlane", ">= 2.191.0"

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval_gemfile(plugins_path) if File.exist?(plugins_path)
