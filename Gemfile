source "https://rubygems.org"

ruby File.read(".ruby-version").strip if File.exist?(".ruby-version")

group :jekyll_plugins do
  gem "jekyll", "~> 3.9.0"
  gem "jekyll-feed", "~> 0.15.0"
  gem "jekyll-paginate", "~> 1.0"
  gem "kramdown-parser-gfm", "~> 1.0"
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
end

gem "webrick", "~> 1.0", group: :development

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
