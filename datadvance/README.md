# datadvance

## Description
Use ActiveRecord to query an existing SQLite3 database

## Objectives

### Learning Objectives

After completing this assignment, you should understand:

* How to interact with a SQL database through ActiveRecord

### Performance Objectives

After completing this assignment, you be able to effectively use

* Our project scaffolding
* `ActiveRecord#where` to find data
* `ActiveRecord#save` to modify data
* `ActiveRecord#sum` and aggregation methods

## Details

Start a new project from our [class skeleton project](https://github.com/TIY-DC-ROR-2015-Jan/model-skeleton). Use the database from the last `databasics` assignment (by moving it / modifying the settings in `config/database.yml`).

Create models as needed to use `ActiveRecord` to answer the following questions.

### Deliverables

A gist containing the answers and either the command(s) you used to find them, or a script that prints them all.


## Normal Mode

* How many users are there?
* What are the 5 most expensive items?
* What's the cheapest book?
* Who lives at "6439 Zetta Hills, Willmouth, WY"? Do they have another address?
* Correct Virginie Mitchell's address to "New York, NY, 10108".
* How much would it cost to buy one of each tool?
* How many total items did we sell?
* How much was spent on books?
* Simulate buying an item by inserting a User for yourself and an Order for that User.

## Hard Mode

* What item was ordered most often? Grossed the most money?
* What user spent the most?
* What were the top 3 highest grossing categories?
