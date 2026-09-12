# Test Execution — Nazi Zombies: Portable

This document records the execution of the manual test cases for **Nazi Zombies: Portable**.

## 1. Execution Summary

**Total test cases:** 32

| Result    |  Count |
| --------- | -----: |
| PASS      |     32 |
| FAIL      |      0 |
| BLOCKED   |      0 |
| NOT RUN   |      0 |
| **Total** | **32** |

**Overall result:** 100% PASS

## 2. Test Environment

The test cases were executed using two different computers and three web browsers.

### Main Test Device

**Gigabyte G5 MD**

* Intel Core i5-11400H
* NVIDIA GeForce RTX 3050 Ti — 4 GB VRAM
* 40 GB RAM
* Windows 11

### Low-Resource Test Device

**Positivo BGH AT550**

* Intel Celeron N3350
* Intel HD Graphics 500
* 4 GB RAM
* Windows 10

### Browsers

* Google Chrome
* Mozilla Firefox
* Microsoft Edge

## 3. Execution by Module

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

## 4. Execution Notes

### Browser Testing

The game was tested on Google Chrome, Mozilla Firefox and Microsoft Edge.

The main game functions worked correctly within the tested scope.

### Low-Resource Hardware

The game was also tested on the Positivo BGH AT550 with limited hardware resources.

The initial loading time was longer than on the main computer.

After loading, the game was playable in the tested configuration.

A performance result of approximately **45–50 FPS at 640 × 480 fullscreen** was observed.

This result applies only to the tested computer and configuration. It is not a general performance benchmark.

### Multiplayer

Basic multiplayer functionality was tested between the two computers.

The tests included:

* Creating a multiplayer game
* Connecting a second player
* Player visibility
* Simultaneous movement
* Player disconnection

The tested multiplayer scenarios passed.

## 5. Observations

During execution, one browser reload behavior was documented:

* F5 and Ctrl+R did not reload the page while the game was active.
* The browser reload button worked correctly.
* The game restarted correctly after using the browser reload button.

This was documented as an observation and was not registered as a confirmed functional bug.


## 6. Final Execution Result

All **32 planned test cases were executed**.

The final execution result was:

**32 PASS — 0 FAIL — 0 BLOCKED — 0 NOT RUN**

No reproducible functional defects were identified during the execution.

The results apply only to the tested software version, hardware configurations, browsers and test scope described in this portfolio.
