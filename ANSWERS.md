<!-- Answers to the Short Answer Essay Questions go here -->

## 1. In Jest, what are the differences between `beforeAll`, `afterAll`, `beforeEach`, and `afterEach` and what are good uses for them?

`beforeAll` and `afterAll` are good if you only need to do setup once, before or after the file.
`beforeEach` and `afterEach` are for repeating tests many times.

## 2. What is the point of `Test Driven Development`? What do you think about this approach?

Test driven development ensures code success and good architecture by writing tests before code. I think it's a good concept if willing to sacrifice development speed since you have to write, sometimes quite complex, tests.

## 3. What are `Jest mock`? What are a good use case for them?

The goal for mocking is to replace something we don't control with something we do. Mocks can be used to test a callback passed to a function.

## 4. Mention three types of tests.

Unit testing, integration testing, behavioral testing

## 5. What type of test performs database operations against a real server.

Unit testing
