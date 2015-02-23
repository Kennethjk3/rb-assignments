# todo-web

## Description

Build a Todo manager that you can interact with via HTTP

## Objectives

### Learning Objectives

After completing this assignment, you should…

* Be comfortable with all the basics of models and controllers and using them together


### Performance Objectives

After completing this assignment, you be able to effectively use

* Sinatra and ActiveRecord together to build a usable web-based application



## Details

### Deliverables

* A repo based on our standard class structure containing at least:
  * `todo.rb`

### Requirements

* Running `ruby todo.rb` should start a server with endpoints detailed below

## Normal Mode

All endpoints require authentication, but this may be done with a token that you generate manually.

* `GET /list/:name` shows all incomplete items in the list with the given name
* `POST /list/:list_name?description=...` creates a new todo item, returning the id
* `PATCH /item/:id?due_at=...` adds or updates a due date
* `DELETE /item/:id` marks an item as complete
* `GET /next` returns a random incomplete
* `GET /search?q=...` finds items containing the given string

Note that lists belong to users, and different users should be able to use the app concurrently (without seeing each other's items).

## Hard Mode

[Deploy the app to Heroku](https://devcenter.heroku.com/articles/rack) and interact with it there.

## Nightmare Mode

Write a gem for interacting with the app deployed on Heroku.
