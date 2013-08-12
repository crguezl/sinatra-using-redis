desc "run  redis-server on port 6379"
task :server do
  sh "redis-server"
end

desc "run app. Run redis-server first"
task :default do
  sh "ruby sinatra-suing-redis"
end
