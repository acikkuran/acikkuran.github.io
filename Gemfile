source "https://rubygems.org"
ruby RUBY_VERSION

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#

gem "nokogiri", ">= 1.10.8"
# If you have any plugins, put them here!
gem 'wdm', '>= 0.1.0' if Gem.win_platform?
group :jekyll_plugins do
    gem 'jekyll-feed'
    gem "i18n", "~> 1.2.0" if RUBY_ENGINE == "jruby"
    gem 'jekyll-sitemap'
    gem 'jekyll-paginate'
    gem 'jekyll-seo-tag'
end
 
