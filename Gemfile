# Las gemas se descargan del repositorio de Ruby
source "https://rubygems.org"

# Usamos la versión 4.3.4 de Jekyll
gem "jekyll", "~> 4.3.4"

# Tema: Just the Docs
gem "just-the-docs"

# Plugin para el feed (genera automáticamente un archivo RSS)
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Gema CSV (para manejar archivos CSV)
gem 'csv'

# Dependencias adicionales para Windows y JRuby
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Para JRuby
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
gem 'base64', require: 'base64'

