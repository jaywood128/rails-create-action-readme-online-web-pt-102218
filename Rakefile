# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require File.expand_path('../config/application', __FILE__)

desc 'drop into pry console'
task :console => :environment do
  Pry.start
end

Rails.application.load_tasks
