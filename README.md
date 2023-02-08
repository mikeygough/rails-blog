# README

learning some ruby and ruby on rails by following along with the [getting started guide](https://guides.rubyonrails.org/getting_started.html)

here are the terminal commands run while following this getting started guide:

create a new directory called _blog_
_$_ rails new blog

check it out!
_$_ cd blog

start the web server
_$_ bin/rails server

generate the articles controller
_$_ bin/rails generate controller Articles index --skip-routes

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

generate the comments controller
_$_ bin/rails generate controller Comments

run migration to add status to articles and comments
_$_ bin/rails generate migration AddStatusToArticles status:string

_$_ bin/rails generate migration AddStatusToComments status:string

run the db migration
_$_ bin/rails db:migrate


#### helpful rails resources:

* [ruby on rails guides guidelines](https://guides.rubyonrails.org/ruby_on_rails_guides_guidelines.html)

* [ruby on rails guides](https://guides.rubyonrails.org/index.html)
