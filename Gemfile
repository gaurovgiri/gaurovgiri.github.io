# frozen_string_literal: true

source "https://rubygems.org"

# gem "jekyll-theme-chirpy", "~> 7.3", ">= 7.3.1"  # Removed - using local theme files instead

# We still need Jekyll itself
gem "jekyll", "~> 4.3"

# Required Jekyll plugins for Chirpy theme
gem "jekyll-paginate"
gem "jekyll-include-cache"
gem "jekyll-sitemap"
gem "jekyll-seo-tag"
gem "jekyll-archives"

# Pin sass-embedded to a working version
gem "sass-embedded", "~> 1.70.0"

gem "html-proofer", "~> 5.0", group: :test

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]
