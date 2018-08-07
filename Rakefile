ENV["SINATRA_ENV"] ||= "development"

require_relative './config/environment'
require 'sinatra/activerecord/rake'

# Type `rake -T` on your command line to see the available rake tasks.

task :console do
  Pry.start
end

namespace :db do
  desc 'sets NAME = create_movies'
    task :create_migration
      NAME = create_movies
    end
  end
end

