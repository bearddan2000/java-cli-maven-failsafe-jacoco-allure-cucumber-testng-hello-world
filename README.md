# java-cli-maven-failsafe-jacoco-allure-cucumber-testng-hello-world

## Description
A POC for maven app using testNg
and cucumber framework with jacoco,
allure, failsafe and surefire plugins.

Serves allure report from link given
after the build.

## Tech stack
- java
- maven
  - testNg
	- failsafe
  - surefire
  - jacoco
  - cucumber
	- allure

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- jacoco report under bin/target/site/jacoco

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Code concept](https://stackoverflow.com/questions/67847818/maven-junit-5-cucumber-not-running-tests)
- [Jacoco config](https://www.baeldung.com/jacoco)
