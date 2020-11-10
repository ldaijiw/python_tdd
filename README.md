# Test Driven Development

Normally with software development, code is written and then tested. With TDD, specific unit tests are constructed first (designed to fail), and then the code is written to pass these tests. Only when the code has passed every test is it approved and goes live.

Tests can give developeres the confidence when refactoring code, as they are more likely to catch bugs due to the instant feedback when tests are executed.


![](images/tdd.png)

## Types of Testing
- Unit testing
- TDD

## Testing in Python
- pytest
- unittest

## Why TDD
- TDD helps us minimise the risk of failure before sending the product to production


**Steps**
- Create a file to write tests
- Run the tests and they will all fail
- Create a file to write code
- Refactor and add the code to pass the tests