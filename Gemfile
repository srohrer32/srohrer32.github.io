source "https://rubygems.org"

# Run with: bundle exec jekyll serve
gem "jekyll"

gem "minima"

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", :install_if => Gem.win_platform?

