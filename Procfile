# This is used by the Foreman gem, which we use to start our web server and the background jobs.
# In production, this file is used as a basis for generating Upstart daemon scripts.
web: bin/run_app.bash
cron: bundle exec script/run_clockwork.rb
resque: script/run_resque.rb
