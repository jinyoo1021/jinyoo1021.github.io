source "https://rubygems.org"

# GitHub Pages compatible build. This gem pins Jekyll and plugins to the
# versions GitHub Pages runs, so local builds match production.
gem "github-pages", group: :jekyll_plugins

# Lock down the platform-specific gems Jekyll needs on newer Ruby.
gem "webrick", "~> 1.8"

# Standard libraries that were removed from Ruby's default gems in 3.4+.
# Harmless on GitHub Pages (older Ruby); needed for local builds on Ruby 4.x.
gem "csv"
gem "base64"
gem "bigdecimal"
gem "logger"
