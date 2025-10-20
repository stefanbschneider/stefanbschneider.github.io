# Gemfile for local development of the GitHub Pages / Jekyll site
# - Uses the `github-pages` gem so your local environment matches GitHub Pages.
# - Include `webrick` for `bundle exec jekyll serve` on recent Ruby versions.
# - Adjust the Ruby version if you target a specific one (optional).

source "https://rubygems.org"

# Optional: pin a Ruby version you use locally (uncomment / change if desired)
# ruby "3.2.2"

# Use the github-pages gem to match GitHub Pages environment and plugins
gem "github-pages", group: :jekyll_plugins

# Needed for `bundle exec jekyll serve` on Ruby >= 3.0
group :development do
  gem "webrick", "~> 1.7"
end