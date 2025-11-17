source "https://rubygems.org"

# Lock to the GitHub Pages stack (pins Jekyll and allowed plugins)
gem "github-pages", group: :jekyll_plugins

# Local dev on Ruby 3.x
gem "webrick", "~> 1.8"

# (Optional) Extra plugins that GitHub Pages supports
group :jekyll_plugins do
  gem "jekyll-feed"     # RSS
  gem "jekyll-sitemap"  # sitemap.xml
  # gem "jekyll-remote-theme" # uncomment only if you use remote themes
end

# Windows/JRuby extras (keep if you’re on Windows/JRuby)
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

