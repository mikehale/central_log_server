task :default => [:deploy]

desc "deploy to staging"
task :deploy do
  puts `rsync -avzd . root@vm-ubuntu-2:/opt/splunk/etc/apps/central_log_server`
end

desc "deploy to production"
task :deploy_production do
  puts `rsync -avzd . root@htgslice:/opt/splunk/etc/apps/central_log_server`
end