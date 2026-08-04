source "https://rubygems.org"

# Match what GitHub Pages runs in production so Netlify (and local) builds
# stay in lockstep with the live site at resume.patrick.taylors.family.
gem "github-pages", group: :jekyll_plugins

# Ruby 3.4 removed these from the standard library; pin them so builds keep
# working on newer Netlify build images regardless of the Ruby version chosen.
gem "csv"
gem "base64"
gem "bigdecimal"
gem "logger"

# Needed to run `bundle exec jekyll serve` locally on Ruby 3+.
gem "webrick"
