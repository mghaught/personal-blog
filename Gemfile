# frozen_string_literal: true

source 'https://rubygems.org'

ruby File.read('.ruby-version').strip

gem 'csv', '~> 3.3'
gem 'webrick', '~> 1.8'

gem 'jekyll', '~> 4.3.3'
group :jekyll_plugins do
  gem 'jekyll-avatar', '~> 0.8.0'
  gem 'jekyll-default-layout', '~> 0.1.5'
  gem 'jekyll-environment-variables', '~> 1.0'
  gem 'jekyll-feed', '~> 0.17'
  gem 'jekyll-include-cache', '~> 0.2.1'
  gem 'jekyll-optional-front-matter', '~> 0.3.2'
  # gem 'jekyll-paginate'
  gem 'jekyll-paginate-v2'
  gem 'jekyll-postcss-v2', '~> 1.0'
  gem 'jekyll-redirect-from', '~> 0.16.0'
  gem 'jekyll-relative-links', '~> 0.7.0'
  gem 'jekyll-seo-tag', '~> 2.8'
  gem 'jekyll-sitemap', '~> 1.4'
  gem 'jekyll-titles-from-headings', '~> 0.5.3'
  # gem 'jekyll-v4-github-pages'
end

group :github_pages do
  gem 'github-pages-health-check', '~> 1.18', '>= 1.18.2'
  gem 'nokogiri', '~> 1.16', '>= 1.16.6'
end

group :development do
  gem 'rubocop-github'
  gem 'rubocop-jekyll'
end
