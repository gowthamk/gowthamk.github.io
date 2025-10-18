source "https://rubygems.org"

# Use the official GitHub Pages gem
gem 'github-pages', group: :jekyll_plugins

# Explicitly list non-default/external plugins
group :jekyll_plugins do
  # These are NOT included in the 'github-pages' meta-gem
  gem 'jekyll-email-protect'
  gem 'jekyll-paginate-v2'
  gem 'jekyll-scholar'
  gem 'jemoji'
  # The below gem is often a dependency of jekyll-scholar, good to keep it explicit
  gem 'unicode_utils'
end

# Required for local serving with Jekyll on Ruby 3.0+
gem "webrick"