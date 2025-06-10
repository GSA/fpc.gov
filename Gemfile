ruby '>= 3.1.3'

source "https://rubygems.org"

gem "jekyll", "~> 4.3.4"
gem "execjs", "2.10.0" # https://github.com/rails/execjs/issues/99
gem "autoprefixer-rails", "10.4.19.0"
gem 'webrick', '1.9.1'# not included in jekyll directly until 4.3.0 https://github.com/jekyll/jekyll/pull/8524
gem 'jekyll-liquify', "0.0.3"
# See https://github.com/envygeeks/jekyll-assets/issues/622
gem "sprockets", "4.2.1"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.15"
  gem 'jekyll-redirect-from'
  gem 'jekyll-paginate-v2', "3.0.0"  
  gem 'jekyll-sitemap'
  gem 'jekyll-seo-tag'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.2.0" if Gem.win_platform?

gem "html-proofer", "~> 3.15"
gem "kramdown-parser-gfm"
gem 'sass-embedded', '~> 1.80'

