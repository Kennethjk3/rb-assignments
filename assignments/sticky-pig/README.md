# sticky-pig

## Description

Use models to add persistence to an existing command line game

## Objectives

### Learning Objectives

After completing this assignment, you should understand:

* Using models to persist permanent state

### Performance Objectives

After completing this assignment, you be able to effectively use

* `ActiveRecord` to interact with data stores
* Using active record models along with other plain Ruby objects

## Details

### Deliverables

A repo (based on [our class skeleton](https://github.com/TIY-DC-ROR-2015-Jan/model-skeleton)) containing:
* `ruby play.rb` should play a game of [pig](http://en.wikipedia.org/wiki/Pig_%28dice_game%29)
* `ruby leaderboard.rb` should display the winningist players

## Normal Mode

* Add a model that tracks wins and losses for each player.
* Add an option to just print the leader board instead of playing.

## Hard Mode

* Make games resumable (players can quit in the middle by pressing Ctrl-C, and start from where they left off when running the script later).

# References

* [The in-class history example with Hangman](https://github.com/TIY-DC-ROR-2015-Jan/course-notes/tree/master/feb/10/persistent-hangman)
* Feel free to use [my Pig implementation](https://github.com/TIY-DC-ROR-2015-Jan/course-notes/blob/master/feb/09/classy-pig/pig.rb) as a starting point (you do not need to implement Hog here).
* Refer to the [ActiveRecord query interface docs](http://guides.rubyonrails.org/active_record_querying.html).
* For context, you may want to read more about the [active record pattern](http://en.wikipedia.org/wiki/Active_record_pattern) (the `ActiveRecord` gem being a Ruby implementation of that general idea).
