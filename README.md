# Unit test adding to the **Group** project
https://github.com/ECE444-2023Fall/project-1-web-application-design-group7-jemagas/blob/13314cee046001439ea138a486fd1dbc76092ece/backend/tests/calendar_test.py#L12-L48
Including 3 units test in `backend/tests/calendar_test.py`   
 - `test_calendar_upload`
 - `test_invalid_calendar_upload`
 - `test_get_request`

# The pro and con for TDD
Test-driven development (TDD) means writing tests before writing the actual code. And it is most likely that it will help us to improve the code quality, at the same time, it also comes with some drawbacks.
Advantages:
By focusing on testing requirements upfront, developers can ensure that the resulting system is more aligned with the intended specifications, potentially leading to fewer bugs in the final product. At the same time, when we are trying to refactor the code, we have more confidence about if we break things or not because we have a comprehensive test suite in place because we know that the tests will catch regressions. Even more importantly, this helps us to document the features better. They demonstrate how the system should behave. New team members who need to ramp up can refer to the tests to understand the expected behaviour of the system.

Disadvantages:
Even TDD is great for code quality, writing tests can be time-consuming, which may lead to a slowed development process. For startup projects, especially in projects with tight deadlines, TDD might drag the progress of the development. At the same time, TDD can sometimes lead to an overemphasis on unit testing at the expense of integration, system, or acceptance testing. This can result in well-tested units that don't work well together, to overcome this, we should better introduce integration testing to overcome this. 
