# frozen_string_literal: true

desc 'Run local server'
task(:serve) do
    puts '## Running: bundle exec jekyll serve --host 0.0.0.0'
    system 'bundle exec jekyll serve --host 0.0.0.0'
rescue Interrupt => e
    puts e
    puts "\n## Shutting down server"
end

task default: ['serve']
