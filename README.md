# Cucumber Allure

A sample gradle base project which uses Cucumber4 JVM for writing tests in BDD Manner. Reporting is generated by Allure Framework
Selenide is used for UI Tests

# To Run

`./gradlew cucumber` will run all the features inside `test/resources` . The glue is present in `test/stepdefs`

Configure the glue and other details by modifying the cucumber task in `build.gradle` file

After the features are ran, you can see the allure results under `build/reports/allure-report/index.html`

## Libraries Used

Cucumber - 4.7.4
Selenide - 5.3.1
Allure - 2.8.1
Junit - 5.5.0

Cucumber syntax is based on cucumber java-8 model


## References

https://cucumber.io/docs/guides/10-minute-tutorial/

https://cucumber.io/docs/installation/java/#gradle

https://docs.qameta.io/allure/#_cucumber_jvm

https://docs.qameta.io/allure/#_selenide

https://docs.qameta.io/allure/#_gradle_5

https://github.com/allure-framework/allure-java/tree/master/allure-cucumber4-jvm




