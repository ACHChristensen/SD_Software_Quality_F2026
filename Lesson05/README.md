[Software Quality - Spring 2026](https://github.com/arturomorarioja-ek/SD_Software_Quality_F2026/blob/main/README.md)

# Lesson 5 - 24 February

[Slides Continuous Testing]: #
[GitHub Actions demos:]: #
[- Runs Jest tests: https://github.com/arturomorarioja/js_vat]: #
[- Runs PHPUnit tests: https://github.com/arturomorarioja/php_words]: #
[- Runs SonarCloud: https://github.com/arturomorarioja/accessibility_web_design]: #
[- Deploys: https://github.com/arturomorarioja/circe]: #
[Talk about different flows (e.g., FE, BE, testing)]: #

[PENDING: State Transition Testing]: #

[Homework: try GitHub Actions]: #

### Homework:
Check out the following slide decks on Itslearning:
- **Integration Testing**, with especial attention to
  - Advantages: protection against regressions, resistance to refactoring
  - Disadvantages: slow, difficult to maintain
- **API Testing**. Focus on:
  - How do API calls usually fail?
  - What to test for?
  - Postman (although you can use Insomnia, ThunderClient or any other similar platform)
- **Database Testing**
  - How to test against the database?

Exercises:
- Integration testing
  - Solve the [measure converter exercise](https://github.com/arturomorarioja-ek/SD_Software_Quality_F2026/blob/main/Lesson05/01%20Measure%20Converter.md), where you will:
    - Apply your black-box and white-box test design knowledge
    - Once you implement the mocking and non-mocking tests, decide what would you and what would you not mock in a real life situation (and, most importantly, why)
- API testing
  - Check out the [library API v3](https://github.com/arturomorarioja/py_library_api_v3) Postman tests
    - [Collection](https://github.com/arturomorarioja/py_library_api_v3/blob/main/postman/Library%20API%20v3.postman_collection.json)
    - [Environment](https://github.com/arturomorarioja/py_library_api_v3/blob/main/postman/Library%20API%20v3.postman_environment.json)
  - Practice API testing in existing APIs of yours:
    - Create collections to group requests to the same API and environments to define variables
    - Write tests under "Scripts". You can use snippets and the built-in AI tool
    - Remember to write positive and negative tests
    - Sort your tests so that you can run them in a row
  - Solve the [customers API exercise](https://github.com/arturomorarioja-ek/SD_Software_Quality_F2026/blob/main/Lesson05/02%20Customers%20API.md) 
