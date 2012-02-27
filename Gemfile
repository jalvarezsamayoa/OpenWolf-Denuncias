source 'https://rubygems.org'

gem 'rails', '3.2.1'

gem 'pg' # Postgresql
gem 'activeadmin', :git => 'git://github.com/gregbell/active_admin.git' #BackEnd Administrador
gem "meta_search",    '>= 1.1.0.pre' # DSL Busquedas
gem 'sass-rails',   '~> 3.2.3' # Integracion de Rails con SASS

gem 'jquery-rails' #Integracion de Rails con JQuery

gem "paperclip" #upload files
gem "aws-s3" # integrate with amazon s3
gem "aws-sdk" # integrate with amazon s3
gem 'devise' # rails generate devise:install

gem "cancan" # permisions

gem "ancestry" # allow model to act as tree
gem 'draper' # decoracion de modelos para desplegar en vistas
gem 'state_machine' # maneja estados de objetos
gem 'airbrake' # bug tracking

# gem "recaptcha", :require => "recaptcha/rails" # add recapcha challenge
# gem "redcarpet" # allow markup in textareas
# gem "prawn", "~> 0.12.0" # generate pdfs
# gem 'sanitize'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'coffee-rails', '~> 3.2.1' #Integracion de Raisl con CoffeeScript
  gem 'uglifier', '>= 1.0.3'
end

group :development do
  gem "haml-rails" #integracion de haml como lenguaje de vistas
  gem "heroku" #integracion con heroku
  gem "taps" # herramienta para db con heroku
  gem 'annotate', :git => 'git://github.com/ctran/annotate_models.git', :require => false # herramienta anotar modelos

  gem 'guard' # herramienta ve cambios a archivos y ejecuta accion
  gem 'guard-livereload' # recarga browser cuando vistas cambian
  gem 'yajl-ruby'
  gem 'rack-livereload'
end

group :development, :test do
  gem 'faker' #genera inforamcion para pruebas
  gem 'factory_girl_rails' 
  gem "database_cleaner" #limpia base de datos
  gem "steak" # framework para testing basado en rspec
  gem "rails3-generators" # plugin para utilizar generadores con haml

  gem 'libnotify' #integracion con notificaciones con sistema operativo
  gem 'rb-inotify'
end

group :production do
  gem 'thin' # server needed for heroku
end


#################
# how to install
################

# active admin
#   $> rails generate active_admin:install
#   $> rails generate active_admin:install User
# in production
# config.assets.precompile += %w[active_admin.css active_admin.js]
# orails generate active_admin:resource [MyModelName]

#aws-s3
# create config/s3.yml
# http://doganberktas.com/2010/09/14/amazon-s3-and-paperclip-rails-3/

# devise
# rails generate devise:install
# rails generate devise User


# acts-as-taggable-only
# rails generate acts_as_taggable_on:migration

# drapper
# Run rails g draper:install to create the directory and ApplicationDecorator
