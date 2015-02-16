# say-as-a-service

## Description

Make a `say` server so your friends can make your computer talk to you


## Objectives

### Learning Objectives

After completing this assignment, you should…

* Be able to write controllers to expose functionality to the local network
* Make system calls based on user input
* Appreciate the difficulting in securing anything doing the above


### Performance Objectives

After completing this assignment, you be able to effectively use

* Sinatra or Camping to build a web server in Ruby
* Their respective DSLs for routing and handling an incoming request


## Details

### Deliverables

* A repo containing at least:
  * `app.rb`
  * `example.rb`, based on the `example.rb` file in this folder

### Requirements

* Running `ruby app.rb` should start a server
* Running `ruby example.rb` (with the server up) should play several phrases, and then log the most recent requests


## Normal Mode

Implement endpoints `POST /cellos` and `POST /badnews` that take a `phrase` param and say that phrase with the associated voice.

Any call to `say` should be logged for auditing later. Record the time and ip address of the requester. `GET /logs?limit=n` should show the `n` most recent such requests.

You are encouraged to add more voices and examples as you see fit.

## Hard Mode

Maintain a whitelist of ips allowed to use the service. Automatically block users if they make too many calls per minute.


## Notes

Be _very_ careful exposing system calls to the outside world. Think about how a malicious user could use them to attack your system.

## Additional Resources

* Read throught the [Sinatra](http://www.sinatrarb.com/intro.html) or [Camping](http://camping.io/The-Camping-Book) intros.
* Check out [a list of available `say` voices](http://www.maclife.com/article/columns/terminal_101_making_your_mac_talk_%E2%80%9Csay%E2%80%9D).
