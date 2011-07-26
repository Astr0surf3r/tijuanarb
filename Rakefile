# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require File.expand_path('../config/application', __FILE__)

#la riga sottostante l'ho inserita per heroku
require 'rake/dsl_definition'

require 'rake'
# If you named your application something other than SampleApp, change that below

module ::Tijuanarb
   class Application
        include Rake::DSL
    end
end


Tijuanarb::Application.load_tasks
