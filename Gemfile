source "https://rubygems.org"

# Bundles the exact toolchain GitHub Pages builds this site with
# (as of writing: Jekyll 3.10.0, kramdown 2.4.0 - see https://pages.github.com/versions/).
# Deliberately unpinned so `bundle update` tracks whatever GitHub is actually running.
gem "github-pages", group: :jekyll_plugins

# webrick left Ruby's standard library in 3.0, and `jekyll serve` needs it.
gem "webrick"

# These left Ruby's *default* gems in 3.4. Listing them keeps Jekyll 3.x working
# on newer Rubies, and is harmless on older ones.
gem "base64"
gem "bigdecimal"
gem "csv"
gem "logger"
