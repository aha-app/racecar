# frozen_string_literal: true

source 'https://rubygems.org'

# Specify your gem's dependencies in racecar.gemspec
gemspec

# We actually support version 6.0 (see gemspec); this extra restriction is added just for running the test suite also
# on Ruby 2.4, which activesupport 6.0 no longer supports
gem 'activesupport', '< 6.0'

gem 'rdkafka', github: 'aha-app/rdkafka-ruby', branch: 'include-topic-on-delivery-report'
