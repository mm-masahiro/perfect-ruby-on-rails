desc 'Rake task test'

task :first_task do
  puts 'Hello Rakefile!'
end

task :task1 do
  puts 'task1'
end

task :task2 do
  puts 'task2'
end

task :task3 => [:task1, :task2] do
  puts 'task3'
end