source 'https://rubygems.org'

# You may use http://rbenv.org/ or https://rvm.io/ to install and use this version
ruby '2.7.2'

gem 'cocoapods', '~> 1.11', '>= 1.11.2'
gem "fastlane", "2.211.0"
gem 'fastlane-plugin-versioning_android'
gem 'fastlane-plugin-firebase_app_distribution'

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval_gemfile(plugins_path) if File.exist?(plugins_path)
