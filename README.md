# README

learning some ruby and ruby on rails.

following along with the [getting started guide](https://guides.rubyonrails.org/getting_started.html)

create a new directory called _blog_
_$_ rails new blog

check it out!
_$_ cd blog

start the web server
_$_ bin/rails server

run model generator
_$_ bin/rails generate model Article title:string body:text

run the migration
_$_ bin/rails db:migrate

activate the console, similar to the irb, and create an article
_$_ bin/rails console

_irb_ article = Article.new(title: "Hello Rails", body: "I am on Rails!")

_irb_ article.save


#### paused at section 6.2 Database Migrations

#### default ruby stuff...

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
