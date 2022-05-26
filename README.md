# Agenda
1. `Why are we here?` - TDD is painful, but is there another way?
2. `The Deeper Way` - Don't ship code, solve business needs
3. `Executable specifications` - Do tests codify requirements specs or impl. specs
4. `What's a Unit Test?` - Are we testing module behaviour or class structure
5. `Testing Behaviour` - Tests should be coupled to behaviour, not to structure
6. `TDD vs TLD` - How do we drive development through executable requirements?
7. `TDD & Clean Architecture` - Driving architecture through system behaviour

## **Why are we here?**

TDD is painful, but is there another way?

## Misconception #1 - The class is a unit of isolation

Write a test class for each production class.

Write a test method for reach production method

Isolate the class under test by mocking out all its collaborators.

Wikipedia says unit testing means testing `"Individual units of source code"`, and in the case of OOP that we're testing a `"class`, or an individual `method"` ... ***We trust Wikipedia...right?***

## Misconception #2 - Unit Tests must be expensive.

It's normal for `test code` to be `2-4X larger` than production code

It's normal that writing unit tests `takes up so much time.`

It's normal that `unit tests break` when we `refactor` class design.

***Anything that's worthwhile must be painful. No pain, no gain, right?***


## Misconception #3 - BDD is about behaviour, TDD is not.


`ATDD and BDD are about behaviours.` They are about testing our system from the user's perspective.

`TDD` is not about system behaviour, it's about `testing classes` and their interactions with other classes.

When we are under pressure and when the budget is tight, `let's just keep ATDD/BDD`. It actually tells us if we satisfied user requirements.


## But what if we could solve the pains of TDD?

Image if TDD could really `speed up development?`

Image if TDD could be done with `significantly less test code?`

Image `if tests wouldn't break all the time` whilst you refactor your class design?

Image if you could `test requirements at the unit level` and get really fast feedback?

Image if anyone - and ` not just companies with huge budgets` - could get the benefits of TDD?


