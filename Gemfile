# frozen_string_literal: true

source "https://rubygems.org"
gemspec

# Adds Jekyll + dependencies
gem "jekyll", ENV["JEKYLL_VERSION"] if ENV["JEKYLL_VERSION"]
gem "kramdown-parser-gfm" if ENV["JEKYLL_VERSION"] == "~> 3.9"
gem 'logger', '~> 1.6', '>= 1.6.1'
gem 'csv', '~> 3.3'
gem 'ostruct', '~> 0.6.0'
gem 'base64', '~> 0.2.0'

# Adds theme dependencies
gem "webrick", "~> 1.7"
gem 'jekyll-paginate', '~> 1.1'
gem 'jekyll-seo-tag', '~> 2.8'


# Add gems that will no longer be included in Ruby >= 3.4.0
gem "bigdecimal", "~> 3.1.4"
gem "safe_yaml", "~> 1.0.5"

# Makes site ready for GH Pages deployment
gem 'github-pages', '~> 232'

# Additional Plugins
gem 'jekyll-watch', '~> 2.2', '>= 2.2.1'
