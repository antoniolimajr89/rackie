require 'bundler'
Bundler::GemHelper.install_tasks

require 'rspec'
require 'rspec/core'
require 'rspec/core/rake_task'

RSpec::Core::RakeTask.new(:spec) do |t|
  t.rspec_opts = ['--colour', '--format progress']
end
