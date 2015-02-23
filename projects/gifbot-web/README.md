# gifbot-web

## Description

Make a web accessible gif manager


## Objectives

### Learning Objectives

After completing this assignment, you should…

* Understand how to structure an HTTP server that interacts with a database


### Performance Objectives

After completing this assignment, you be able to effectively use

* Sinatra's `get` and `post` DSL for defining endpoints
* ActiveRecord for making DB queries within a Sinatra app



## Details

### Deliverables

* A repo based on our standard project structure, containing at least
  * `gifbot.rb`

### Requirements

* Running `ruby gifbot.rb` should start a server for managing gifs


## Normal Mode

Reimplement the functionality from the command-line gifbot as an API. Namely:

`POST /add?url=...` should add a gif with the given url and return its id
`POST /:id/tag?name=...` should tag the gif with the given id as the named tag
`GET /list` should return a list of all available gifs
`GET /surprise` should return a random gif
`GET /surprise?tags=...` should return a random gif filtered by tag

## Hard Mode

* Add a user authentication system. Gifs should note which user added them, and which users have seen them.
* Allow users to upvote, downvote, and block gifs

## Nightmare Mode

* Make the app publically available by deploying to Heroku
* Configure a Slack integration
