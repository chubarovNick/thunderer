require 'bundler/gem_tasks'
require 'rake'
require 'rspec/core/rake_task'

desc 'Run RSpec'
RSpec::Core::RakeTask.new do |t|
  t.verbose = false
end

task default: [:spec, "jasmine:ci"]
require 'jasmine'
load 'jasmine/tasks/jasmine.rake'
