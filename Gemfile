source "https://rubygems.org"

gem 'bundler'
gem 'jemoji'
gem 'kramdown'
gem 'rack-jekyll'
gem 'rake'
gem 'puma'
gem "github-pages", group: :jekyll_plugins

# Plugins
group :jekyll_plugins do
    gem 'devlopr', '~> 0.4.5'
    gem 'jgd', '~> 1.12'
    gem 'jekyll-feed', '~> 0.13.0'
    gem 'jekyll-paginate', '~> 1.1.0'
    gem 'jekyll-gist', '~> 1.5.0'
    gem 'jekyll-seo-tag', '~> 2.6.1'
    gem 'jekyll-redirect-from'
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?
gem "jekyll", "~> 3.9"
