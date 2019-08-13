source "https://rubygems.org"

# If you want to want to use a different Jekyll version, change it below, save
# the file and run `bundle install`. Then 'bundle exec jekyll serve'.

# gem "jekyll", "~> 3.8.6"

# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
gem "github-pages", group: :jekyll_plugins

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.6"
  gem "jemoji"
  # SEO
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
  # GitHub-Pages Defaults
  gem "jekyll-coffeescript"
  gem "jekyll-gist"
  gem "jekyll-github-metadata"
  gem "jekyll-paginate"
  gem "jekyll-relative-links"
  gem "jekyll-optional-front-matter"
  gem "jekyll-readme-index"
  gem "jekyll-default-layout"
  gem "jekyll-titles-from-headings"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0", :install_if => Gem.win_platform?
