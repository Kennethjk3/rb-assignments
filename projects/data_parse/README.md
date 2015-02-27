# Parsing Data: Planet Express Logs

## Description
Parsing Data: Planet Express Logs


## Objectives

### Learning Objectives

After completing this assignment, you should…

* Understand some key concept


### Performance Objectives

After completing this assignment, you be able to effectively use

* Use some tool or technique



## Details

Record format:

```
Destination, What got shipped, Number of crates, Money we made
```

### Good news Rubyists!
* We have a week of records tracking what we shipped at Planet Express.
* I need you to answer a few questions for Hermes.


### Deliverables

* A gist with two files:
  * `planet_express_logs.csv`
  * `planet_express.rb`

### Requirements

* You should use the ruby "CSV" library
* Do not make changes to the `planet_express_logs.csv` file


## Normal Mode

1. How much money did we make this week?
2. Also, bonuses are paid to employees who pilot the Planet Express

* Different employees have favorite destinations they always pilot to
* Fry - pilots to Earth (because he isn't allowed into space)
* Amy - pilots to Mars (so she can visit her family)
* Bender - pilots to Uranus (teeheee...)
* Leela - pilots everywhere else because she is the only responsible one

3. How many trips did each employee pilot?

* They get a bonus of 10% of the money for the shipment as the bonus
* How much of a bonus did each employee get?


## Hard Mode

* How much money did we make broken down by planet? ie.. how much did we make shipping to Earth? Mars? Saturn? etc.

## Nightmare Mode

* uses classes for each shipment, such as a `class Shipment`

## Additional Resources

* Ruby [CSV](http://ruby-doc.org/stdlib-2.2.0/libdoc/csv/rdoc/CSV.html)
* Watch [Introduction to Importing from CSV](https://gorails.com/episodes/intro-to-importing-from-csv)
* Advanced: [importing CSV in Ruby](https://rubyoffrails.com/videos/4-importing-csv-in-ruby)
