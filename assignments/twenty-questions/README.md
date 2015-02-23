# twenty-questions

## Description

Write a script that learns to play twenty questions


## Objectives

### Learning Objectives

After completing this assignment, you should…

* Be able to persist infomation between runs of a script
* Appreciate using an appropriate data structure


### Performance Objectives

After completing this assignment, you be able to effectively use

* `gets` to ask a user for input
* ActiveRecord to store the user's answers


## Details

### Deliverables

* A repo containing at least:
  * `twenty.rb`

### Requirements

* Running `ruby twenty.rb` should play an interactive game of twenty questions to guess an animal.

## Normal Mode

We will actually be building a knowledge base from the user. After each time the script loses (which it will often to begin with), ask the user:

```
> What animal were you thinking of?
> What is a question that would distinguish #{that animal} from #{potential answer}?
```

and store their response. Next time around, you won't be fooled so easily.

## Nightmare Mode

Every question should be able to eliminate at least one candidate answer, but if there are more than 21 animals in the database, you would need to choose a question that divides the remaining candidate pool roughly in half at each step. Attempt to do so. This will likely require asking the user a lot more questions about animals.
