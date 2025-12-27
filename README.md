# Unit Testing Assignment — Dream Team

A small collection of Java utility functions with a focused JUnit test suite.
Used to demonstrate writing clear unit tests and handling edge cases.

Team
- Gilad Peretz — implemented/tested: add, isPrime, reverse  
- Yuval Ganot — implemented/tested: factorial, isPalindrome, fibonacciUpTo  
- Shared: charFrequency, isAnagram, average, filterEvens, mostCommonWord, etc.

Quick start (clone → run)
1. Clone:
   git clone <https://github.com/Giladperetz12/Devtools_tests.git>
   cd unit-testing-assignment-gilad-yuval-dream-team

2. Prerequisite:
   - JDK 11 or newer (ensure JAVA_HOME is set).

3. Run all tests:
   - Windows PowerShell/CMD:
     .\gradlew.bat :app:test
   - macOS / Linux:
     ./gradlew :app:test

Run a single test class or method
- Class:
  .\gradlew.bat :app:test --tests "org.example.AppTest"
- Method:
  .\gradlew.bat :app:test --tests "org.example.AppTest.add_positiveNumbers"

Results
- HTML report: app/build/reports/tests/test/index.html
- Raw results: app/build/test-results/test/*.xml
- For more console detail: add --info or --stacktrace


