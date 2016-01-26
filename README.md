== README

A project aimed to give an example of a basic rails server with low resource consumption.

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


Please feel free to use a different markup language if you do not plan to run
<tt>rake doc:app</tt>.

#### Steps to configure

included "config.action_mailer.default_url_options = { host: 'localhost', port: 3000 }" in environment/development.rb
rails g devise:install
rails g active_admin:install
