# frozen_string_literal: true

source "https://rubygems.org"

# Plain Jekyll rather than the github-pages gem: the site is built by
# .github/workflows/deploy.yml, not by Pages' own builder, so nothing here
# needs to match GitHub's pinned versions. See CLAUDE.md.
gem "jekyll", "~> 4.3"
gem "jekyll-seo-tag"

# Ruby 3 dropped webrick from stdlib; `jekyll serve` still wants it.
gem "webrick", "~> 1.8"
