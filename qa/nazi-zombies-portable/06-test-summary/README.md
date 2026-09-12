# Test Summary Report — Nazi Zombies: Portable

This document summarizes the results of the manual testing performed on **Nazi Zombies: Portable**.

## 1. Project Overview

**Project:** Nazi Zombies: Portable — Manual QA Testing
**Role:** Manual QA Tester
**Institution:** Teclab Instituto Técnico Superior
**Course:** Professional Practice
**Date:** July 2026

The project focused on manually testing the web version of the game using different browsers and hardware configurations.

## 2. Test Scope

The testing covered:

* Web loading and restart
* Main menu navigation
* Player movement
* Shooting and reloading
* Damage and enemy behavior
* User interface
* Score and round changes
* Game mode selection
* Basic multiplayer functionality
* Browser compatibility
* Basic performance
* Low-resource hardware

The following areas were outside the project scope:

* Automated testing
* Source code testing
* Backend testing
* Advanced network testing
* Game modifications or mods

## 3. Test Environment

Testing was performed using:

### Gigabyte G5 MD

* Intel Core i5-11400H
* NVIDIA GeForce RTX 3050 Ti — 4 GB VRAM
* 40 GB RAM
* Windows 11

### Positivo BGH AT550

* Intel Celeron N3350
* Intel HD Graphics 500
* 4 GB RAM
* Windows 10

### Browsers

* Google Chrome
* Mozilla Firefox
* Microsoft Edge

## 4. Test Results

A total of **32 test cases** were executed.

| Result    |  Count | Percentage |
| --------- | -----: | ---------: |
| PASS      |     32 |       100% |
| FAIL      |      0 |         0% |
| BLOCKED   |      0 |         0% |
| NOT RUN   |      0 |         0% |
| **Total** | **32** |   **100%** |

## 5. Results by Module

| Module         | Test Cases |   PASS |  FAIL |
| -------------- | ---------: | -----: | ----: |
| Web System     |          6 |      6 |     0 |
| Main Menu      |          3 |      3 |     0 |
| Gameplay       |          4 |      4 |     0 |
| User Interface |          3 |      3 |     0 |
| Multiplayer    |         10 |     10 |     0 |
| Game Modes     |          1 |      1 |     0 |
| Compatibility  |          5 |      5 |     0 |
| **Total**      |     **32** | **32** | **0** |

## 6. Main Findings

The game worked correctly within the tested scope.

### Browser Compatibility

The game was tested on Chrome, Firefox and Edge.

The main functions worked correctly in the tested browsers.

### Low-Resource Hardware

The game was also tested on the Positivo BGH AT550.

The initial loading time was longer than on the Gigabyte G5 MD.

After loading, the game was playable in the tested configuration.

Approximately **45–50 FPS at 640 × 480 fullscreen** was observed during basic performance testing.

This result only describes the tested configuration and should not be considered a general performance benchmark.

### Multiplayer

Basic multiplayer functionality was tested between the two computers.

The tested scenarios included:

* Creating a game
* Connecting a second player
* Player visibility
* Simultaneous movement
* Player disconnection

All planned multiplayer test cases passed.

## 7. Observations

One browser reload behavior was observed during testing.

F5 and Ctrl+R did not reload the page while the game was active. The browser reload button worked correctly and restarted the game.

This behavior was documented as an observation and was not reported as a confirmed functional bug.

## 8. Defects

No reproducible functional defects were identified during the test execution.

This does not mean that the game has no defects.

It means that no reproducible functional defects were found within the tested scope, configurations and test execution.

## 9. Limitations

The results are limited to:

* The tested version of the game
* The two available computers
* The three tested browsers
* The test scenarios included in this project
* The manual testing approach

The project did not include automated tests, source code analysis, backend testing or advanced network testing.

No complete visual evidence set from the original academic execution was preserved.

## 10. Conclusion

The planned manual testing was completed successfully.

All **32 test cases** were executed and passed.

The game performed correctly within the tested scope on both the main computer and the low-resource computer.

The project provided practical experience in:

* Test planning
* Test case design
* Manual test execution
* Functional testing
* Exploratory testing
* Browser compatibility testing
* Basic performance testing
* Multiplayer testing
* QA documentation
* Test result analysis

The results represent the tested configurations and should not be interpreted as a guarantee that the game will behave identically on all systems.
