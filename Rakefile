task :default => [:deploy]

task :deploy do
  puts `rsync -avzd . root@vm-ubuntu-2:/opt/splunk/etc/apps/central_log_server`
end

task :deploy_remote do
  puts `rsync -avzd . root@htgslice:/opt/splunk/etc/apps/central_log_server`
end