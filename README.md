# ECE444-F2023-Lab5

## Disclaimer

The code found in this repo is taken from the open source project: https://github.com/mjhea0/flaskr-tdd

## Test Cases

The test case written by Yousef were about Testing the sign up with an existing username. https://github.com/ECE444-2023Fall/project-1-web-application-design-group17-jigglies/blob/main/tests/app_test.py#L132-L150 

## Pros and Cons of TDD

Test-Driven Development (TDD) is a well-regarded software development practice with several advantages. Unit testing helps developers write better code, which results in a more reliable and less glitchy product. This practice is commonly used before developing actual code. Because developers are forced to consider the design and structure beforehand, this methodology encourages the creation of cleaner, more modular systems. Refactoring code without worrying about regressions is made confidently possible by a developed suite of tests. These unit tests can also function as documentation, showing how particular functionality ought to operate. TDD makes ensuring that modifications made by one developer don't unintentionally break another's code when numerous devs work together, which facilitates teamwork. Furthermore, it generates an instantaneous feedback loop that facilitates quick modifications and iterations.

However, TDD is not without its challenges. The upfront investment of writing tests can appear to slow down the development process, especially for newcomers. There's a learning curve associated with TDD, requiring a paradigm shift from traditional development approaches. While there's an emphasis on unit tests, teams might inadvertently sideline other essential tests like integration or system tests. This focus can sometimes lead to over-engineering, where tests are written for even low-value or improbable scenarios. As projects evolve, the responsibility of maintaining and updating these tests can become a significant overhead. And, it's worth noting that TDD might not be the optimal approach for every project, such as those in exploratory phases or prototypes.
