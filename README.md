Sample Appium TestNG project
---

This contains the source code for running sample [Appium](http://github.com/appium/appium) tests using [TestNG](http://www.testng.org).

In order to run the tests, you will need to install [Apache Maven](http://maven.apache.org), and Appium (according to the Appium [installation instructions](https://github.com/appium/appium).

You will then need to start appium, eg:

    grunt appium

To compile and run all tests, run:

    mvn test

To run a single test, run:

    mvn -Dtest=com.saucelabs.appium.SimpleTest test