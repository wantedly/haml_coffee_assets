# frozen_string_literal: true

require 'bundler'
Bundler::GemHelper.install_tasks

require 'rspec/core/rake_task'

# javascript tests
require 'rails/all'

task default: ['spec:rspec']

namespace(:spec) do
  # add rspec task
  RSpec::Core::RakeTask.new(:rspec)
end
