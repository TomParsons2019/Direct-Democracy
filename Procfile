web: bundle exec bin/rails server -p $PORT -e $RAILS_ENV
worker: bundle exec sidekiq -q default -q mailers -c 10