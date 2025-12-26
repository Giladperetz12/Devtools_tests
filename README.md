# Unit Testing Assignment — Dream Team (Gilad & Yuval)

Short description
-----------------
A small Java utility project (org.example.App) with several example functions and a comprehensive JUnit test suite (org.example.AppTest). The tests are run using the Gradle wrapper that ships with the repo.

Goals
-----
- Provide a small, well-documented set of example utilities (add, isPrime, reverse, factorial, etc.).
- Maintain clear, focused unit tests that exercise normal cases and edge cases.
- Make it easy to run tests and inspect results using the Gradle wrapper.

What's included
---------------
- app/src/main/java/org/example/App.java — implementation of utility functions.
- app/src/test/java/org/example/AppTest.java — JUnit tests covering the functions.
- Gradle wrapper files (gradlew, gradlew.bat, gradle/) to run tasks reproducibly.
- Test reports produced as HTML in app/build/reports/tests/test/ after running tests.

Project layout (overview)
-------------------------
- app/
  - src/
    - main/java/org/example/App.java
    - test/java/org/example/AppTest.java
  - build.gradle
- gradlew, gradlew.bat, gradle/ (wrapper)

How to run the tests
--------------------
From the repository root:

- Windows PowerShell / CMD:
  .\gradlew.bat :app:test

- macOS / Linux:
  ./gradlew :app:test

Run one test class:
- .\gradlew.bat :app:test --tests "org.example.AppTest"

Run one test method:
- .\gradlew.bat :app:test --tests "org.example.AppTest.add_positiveNumbers"

Where to find results
---------------------
- HTML test report: app/build/reports/tests/test/index.html
- Add --info or --stacktrace for more console detail:
  .\gradlew.bat :app:test --stacktrace --info

Contributing
------------
- Add unit tests for new functions or edge cases.
- Keep tests small, readable, and deterministic.
- Open a pull request with a short description of your change.

