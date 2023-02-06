# README

learning some ruby and ruby on rails.

following along with the [getting started guide](https://guides.rubyonrails.org/getting_started.html)

here are the terminal commands run while following this getting started guide:

create a new directory called _blog_
_$_ rails new blog

check it out!
_$_ cd blog

start the web server
_$_ bin/rails server

run model generator for the article controller
_$_ bin/rails generate model Article title:string body:text

run the db migration
_$_ bin/rails db:migrate

activate the console, similar to the irb, and create an article
_$_ bin/rails console

_irb_ article = Article.new(title: "Hello Rails", body: "I am on Rails!")

_irb_ article.save

inspect what routes are mapped
_$_ bin/rails routes

run model generator for the comment controller
_$_ bin/rails generate model Comment commenter:string body:text article:references

run the db migration
_$_ bin/rails db:migrate

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
