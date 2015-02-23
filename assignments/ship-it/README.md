## Objectives

:shipit:

### Learning Objectives

After completing this assignment, you should…

* Have shipped some code
* Understand how to run and pass tests
* Have a basic appreciation for what a working developer's process might look like

### Performance Objectives

After completing this assignment, you be able to effectively use

* Minitest to verify that your code meets spec
* `git` to commit and push code to Github
* Travis CI for vigilance

## Details

### Deliverables

* A link to a repo under your personal Github account.

### Requirements

* The provided tests should be passing.
* The repo should contain a README.md file with a passing Travis CI badge and a picture of a squirrel.


## Normal Mode

Create a new repo and copy `triangle_test.rb` into it. Running `ruby test_triangle.rb` should show 4 errors.

First, implement the given `triangle` method to get the tests passing. Then commit and push your work to Github. Finally, turn on Travis CI, and add a .travis.yml config file and a README.

## Hard Mode

Add a separate `triangle.rb` file that defines a `Triangle` class and is `require`d by the test. Use `Triangle.new(a,b,c).classification` for the definition of the `triangle` method in `test_triangle.rb`.

## Notes

* See the [Travis CI getting started guide](http://docs.travis-ci.com/user/getting-started) and especially [this example](http://docs.travis-ci.com/user/getting-started/#Ruby)
