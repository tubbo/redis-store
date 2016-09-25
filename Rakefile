require 'bundler/setup'
require 'rake'
require 'bundler/gem_tasks'
require 'redis-store/testing/tasks'
require 'rubocop/rake_task'
require 'travis/release'

RuboCop::RakeTask.new :lint

Travis::Release::Task.new
