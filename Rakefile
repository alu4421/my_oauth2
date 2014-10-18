desc "Run server"
task :default do
  sh "rackup"
end

desc "Save config.yml out of the CVS"
task :keep_secrets do
  sh "cp config/config_template.yml config/config.yml "
end

