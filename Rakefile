ENV['SINATRA_ENV'] ||= "development"

reqiure_relative './config/environment'
require 'sinatra/activerecord/rake'

task :console do
  Pry.start
end