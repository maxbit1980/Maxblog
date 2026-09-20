source "https://rubygems.org"

# Jekyll
gem "jekyll", "~> 4.4.1"

# Tema padrão
gem "minima", "~> 2.5"

# Plugins do Jekyll
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.17"
  gem "jekyll-seo-tag", "~> 2.8"
  gem "jekyll-sitemap", "~> 1.4"
end

# Gems padrão do Ruby 3.3+ que precisam ser declaradas
# para evitar que o Bundler tente baixá-las de servidores remotos.
gem "base64"
gem "json"
gem "csv"
gem "bigdecimal"

# Para ambientes Windows/JRuby (opcional, mas não atrapalha)
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
