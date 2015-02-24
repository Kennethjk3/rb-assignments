# spotibetical

## Description

Build a community-generated playlist generator


## Objectives

### Learning Objectives

After completing this assignment, you should…

* understand basics of building a full MVC CRUD app
* be able to implement a user / voting system
* be able to push locally aggregated data to an external service (Spotify)


### Performance Objectives

After completing this assignment, you be able to effectively use

* a rudimentary authentication system
* ActiveRecord to interact with a DB
* HTTParty (or similar) to make requests to an external API
* Sinatra for responding to requests locally
* Processes (git branching, user stories, etc.) to effectively work on all of the above

## Details

### Deliverables

* A repo containing a Sinatra app

### Requirements

* Running the app starts a server with features detailed below:

## Normal Mode

* Users have accounts and can login
* Users can propose songs for the week's playlist
* Users can spend points to vote on proposed songs
* At the end of the week, the top rated song is chosen for each letter A-Z and added to a playlist; that playlist is pushed to Spotify
* Users get a fixed number of points to spend at the start of each week
* Users get a bonus based on how many people voted for their suggestions last week
* Points do _not_ transfer week-to-week (use it or lose it)
* Users can veto one song pick per week

## Hard Mode

* Disable general signup, but add (and secure) an admin-only section for managing user accounts
* Deploy your app to Heroku
* Automate playlist generation (e.g. roll a new one and reset vote counts every Friday at 9:00)
