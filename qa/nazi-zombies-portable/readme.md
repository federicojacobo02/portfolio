# Nazi Zombies: Portable — Manual QA Testing

**Manual QA Testing Project**

**Teclab Instituto Técnico Superior — Práctica Profesionalizante**
**July 2026**

## Project Overview

This project contains the manual testing work performed on **Nazi Zombies: Portable**, a WebGL FPS game that runs directly in a web browser.

The main goal was to check the game's functionality, browser compatibility, basic performance and multiplayer features on different computers and browsers.

## My Role

**Manual QA Tester**

I was responsible for:

* Planning the tests
* Designing test cases
* Executing manual tests
* Recording test results
* Collecting evidence
* Checking different browsers and hardware
* Testing multiplayer features
* Writing the test documentation
* Reporting and reviewing possible issues

## Test Scope

The testing covered:

* Web loading and restart
* Main menu and navigation
* Player movement
* Shooting and reloading
* Damage and enemy behavior
* User interface
* Score and round changes
* Game mode selection
* Multiplayer
* Browser compatibility
* Basic performance
* Low-resource hardware

Automated testing, source code testing, backend testing and advanced network testing were outside the project scope.

## Test Environment

### Main Computer

**Gigabyte G5 MD**

* Intel Core i5-11400H
* NVIDIA RTX 3050 Ti 4 GB
* 40 GB RAM
* Windows 11

### Low-Resource Computer

**Positivo BGH AT550**

* Intel Celeron N3350
* Intel HD Graphics 500
* 4 GB RAM
* Windows 10

### Browsers

* Google Chrome
* Mozilla Firefox
* Microsoft Edge

## Testing Methods

The project used manual testing techniques including:

* Functional Testing
* Exploratory Testing
* UI Testing
* Usability Testing
* Browser Compatibility Testing
* Basic Performance Testing
* Multiplayer Testing

## Results

**32 test cases were executed.**

**32 PASS — 0 FAIL**

No reproducible functional bugs were found during the test execution.

The game worked correctly within the tested scope on the main computer and on the low-resource computer.

On the low-resource computer, the initial loading time was longer. After loading, the game reached approximately **45–50 FPS at 640×480 fullscreen** in the tested configuration.

Multiplayer was also tested between the two computers.

## Test Documentation

The project documentation is divided into the following sections:

* [Test Plan](./01-test-plan/)
* [Test Documentation](./02-test-documentation/)
* [Test Cases](./03-test-cases/)
* [Bug Report](./04-bug-report/)
* [Test Execution](./05-test-execution/)
* [Test Summary](./06-test-summary/)
* [Test Evidence](./evidence/)

## Important Notes

The results in this project describe the tested configurations and test scope. They do not represent a guarantee that the game will work in the same way on every computer or browser.

One browser reload test also showed a difference between the expected keyboard behavior and the browser reload button. The browser reload button correctly restarted the game. This was documented as an observation and was not reported as a functional bug.

## What I Learned

This project helped me practice:

* Creating a test plan
* Designing clear test cases
* Executing tests in a structured way
* Working with different hardware configurations
* Testing browser compatibility
* Testing multiplayer features
* Recording evidence
* Writing technical QA documentation
* Reporting test results clearly
