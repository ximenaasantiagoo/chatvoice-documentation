source "https://rubygems.org"

# Usar la versión correcta de Jekyll
gem "jekyll", "~> 4.3.4"

# Tema Just the Docs
gem "just-the-docs"

# Plugin para el feed
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Agregar la gema CSV si es necesario
gem 'csv'

# Dependencias adicionales para Windows y JRuby
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Si usas Windows, puedes agregar la gema para mejorar el rendimiento
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Para JRuby
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

