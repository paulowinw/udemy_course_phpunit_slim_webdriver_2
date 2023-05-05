# PHPUNIT AND FACEBOOK WEBDRIVER BASED ON PHPUNIT SELENIUM COURSE ON UDE#MY 

- Selenium dependency on composer was substituted for phpwebdriver, this is the library that is up-to-date, other libraries don't work.
- PHP Selenium server must be installed to work with phpwebdriver
- I used chatgpt to rewrite the code for phpwedriver instead of PHPUnit_Extensions_Selenium2TestCase

## MAIN GOALS OF UNIT TESTS

- Create tests for front end to:
    - check menu itens.
    - click on buttons and check if an element is loaded.
    - check title of pages
    - check validation of forms
- Create scenarios for tests using long names to explain the situation according to the business requiriments
- Use tests to connect business with development results
- Use the TDD cycle to refator the main code using the tests as reference to satisfy business requiriments
- A method can satisfy more than one cenario that's why TDD is important, business is very clean so that you can identify problems easy and code better to solve theses problems
- You expect results first of coding your solutions
- Refactoring based on tests makes your code better because you think on the code based on scenarios(results)
- Depeding of your test coding strategies your software is going to have high scalability and manutanability