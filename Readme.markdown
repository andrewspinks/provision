## Capistrano tasks to install a rails stack (nginx, unicorn, postgres) on ubuntu.

Also includes a few tasks for dumping data from Heroku into the provisioned db.

Usage:
- cap provision:install
- cap deploy:setup
- cap postgresql:capture_heroku_database # pg_restore is not yet working with capistrano
- cap deploy
