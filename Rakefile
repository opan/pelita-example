# ./Rakefile

#!/usr/bin/env rake
task :app do
  require_relative "boot"
end
Dir[File.dirname(__FILE__) + "/lib/tasks/*.rb"].sort.each do |path|
  require path
end
