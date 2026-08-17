# Local preview only. The `github-pages` gem pins Jekyll, jekyll-remote-theme,
# and every plugin to the exact versions GitHub Pages runs — so a local
# `bundle exec jekyll serve` reproduces the real build.
# This file is excluded from the built site via _config.yml `exclude:`.
#
# Requires Ruby < 3.4. Jekyll 3.9.0 (pinned above) still does bare `require
# "csv"` / `require "bigdecimal"`; Ruby 3.4 moved those out of the default
# gem set, and no Gemfile addition here fixes it for good — every stdlib
# extraction Ruby makes next needs its own patch. Use whatever your machine's
# package manager calls Ruby 3.3.x (there's no shared .ruby-version file —
# see .gitignore).
source "https://rubygems.org"

gem "github-pages", group: :jekyll_plugins
gem "webrick" # Ruby >= 3.0 dropped webrick from stdlib; `jekyll serve` needs it.
