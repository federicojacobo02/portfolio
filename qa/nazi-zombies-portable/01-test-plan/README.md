# Test Plan — Nazi Zombies: Portable

**Project:** Nazi Zombies: Portable — Web Version
**Student:** Federico Jacobo
**Institution:** Teclab Instituto Técnico Superior
**Course:** Professional Practice
**Tutor:** Santiago Di Colantonio
**Date:** April 29, 2026

## 1. Introduction

This document defines the test plan for **Nazi Zombies: Portable**, a version of the game that runs in a web browser.

The system under test is a first-person shooter (FPS) game based on round-based survival. The player must survive enemy waves, earn points and improve their equipment.

The web version uses **WebGL**, so the game can run directly in a browser without installing the game.

The goal of this test plan is to define the **scope, test strategy, test environment and test criteria** for the manual testing process.

## 2. Testing Objectives

### General Objective

Validate the main functions of the game in a web browser through manual testing.

### Specific Objectives

* Check player controls.
* Test shooting and reloading.
* Check enemy behavior.
* Test the main menu.
* Check navigation between options.
* Test game mode selection.
* Check basic multiplayer functionality.
* Check browser stability.
* Identify functional problems.
* Evaluate basic usability.

## 3. Test Scope

### Included

#### Gameplay

* Player movement
* Shooting
* Reloading
* Weapon changes
* Receiving damage
* Enemy spawning
* Round progression
* Testing on low-resource hardware

#### User Interface (UI)

* HUD
* Ammunition counter
* Visual indicators
* Main menu
* Navigation between options

#### Game Modes

* Mode selection
* Starting a game
* Basic behavior of each mode

#### Basic Multiplayer

* Access to multiplayer
* Creating or connecting to a game
* Starting a multiplayer session
* Basic interaction between players

Advanced network synchronization and network performance are outside the scope of this project.

#### Web System

* Game loading in the browser
* Game restart
* General stability
* Input response
* Possible freezes

### Not Included

* Automated testing
* Source code analysis
* Backend testing
* Advanced network testing
* Game modifications or mods

## 4. System Under Test

**Name:** Nazi Zombies: Portable
**Type:** First-Person Shooter (FPS)
**Platform:** Web Browser (WebGL)
**Main Mode:** Single Player
**Additional Mode:** Multiplayer — limited testing

The system is a recreation of the Zombies game mode from **Call of Duty**, built using technology based on Quake-derived engines and available on several platforms, including web browsers.

## 5. Test Strategy

The project uses a **manual testing approach** based on direct interaction with the game.

### Test Types

* Manual Functional Testing
* Exploratory Testing
* UI Testing
* Usability Testing
* Browser Compatibility Testing
* Basic Performance Testing
* Basic Multiplayer Testing

Manual testing was selected because the game is highly interactive and no test automation was used in this project. Direct interaction made it possible to check the behavior of the game from a user's point of view.

## 6. Test Environment

The tests were performed using different hardware and software configurations to check the behavior of the game under different conditions.

### Computer 1 — Main Test Device

**Model:** Gigabyte G5 MD
**Type:** Gaming notebook

**Specifications:**

* Intel Core i5-11400H
* NVIDIA GeForce RTX 3050 Ti Laptop GPU — 4 GB VRAM
* 40 GB RAM
* 512 GB NVMe + 1 TB HDD
* Windows 11

This computer was used as the main test device.

### Computer 2 — Low-Resource Device

**Model:** Positivo BGH AT550
**Type:** Notebook

**Specifications:**

* Intel Celeron N3350
* Intel HD Graphics 500
* 4 GB RAM
* 64 GB storage
* Windows 10

This computer was used to check the game on a system with limited hardware resources.

### Browsers

The game was tested on:

* Google Chrome
* Mozilla Firefox
* Microsoft Edge

**Test resolution:** 1920 × 1080

### Internet Connection

**Provider:** Starlink
**Hardware:** Starlink Mini
**Plan:** Lite

The internet connection was part of the test environment, especially for basic multiplayer testing.

### Technical Considerations

The game uses WebGL. Its performance depends on the computer hardware and the browser used for rendering.

For this reason, the project included tests on both a gaming computer and a low-resource computer.

## 7. Test Modules

### Main Menu

* Navigation between options
* Game mode selection
* Starting a game
* Menu behavior

### Gameplay

* Movement
* Shooting
* Reloading
* Receiving damage

### Game Modes

* Mode selection
* Starting a game
* Basic differences between modes

### Basic Multiplayer

* Access
* Initial connection
* Starting a game

### User Interface

* HUD
* Visual indicators
* Player feedback

### Web System

* Initial loading
* Restart
* Stability
* Performance

## 8. Tools Used

* Google Chrome
* Mozilla Firefox
* Microsoft Edge
* Screenshot tool
* Excel / Google Sheets
* Screen recorder — optional

## 9. Testing Risks

The main risks identified for this project were:

* Unstable game builds
* WebGL performance problems
* Browser compatibility problems
* Hardware limitations
* Limited testing time

## 10. Test Schedule

The testing process was planned over **four weeks**.

Because the project included exploratory testing, some activities could overlap or change according to the test results.

### Week 1 — Analysis and Planning

* Analyze the system under test
* Define the test scope
* Identify test modules
* Create the test plan

### Week 2 — Test Design

* Design test cases
* Define test scenarios
* Prepare the test environment

### Week 3 — Test Execution

* Execute test cases
* Perform exploratory testing
* Test different browsers
* Test different computers

### Week 4 — Documentation and Closure

* Document possible defects
* Re-test important cases when necessary
* Analyze test results
* Prepare the final report

## 11. Entry and Exit Criteria

### Entry Criteria

Testing could start when:

* The game loaded correctly in the browser.
* The main menu was accessible.
* A game could be started.

### Exit Criteria

Testing could finish when:

* All planned test cases were executed.
* Relevant defects were documented with evidence.
* The test documentation was completed.
* The test results were reviewed.

## 12. Success Criteria

The testing process was considered complete when the planned tests were executed and the results were properly documented.

The final evaluation considered:

* Test case results
* Functional behavior
* Browser compatibility
* Basic performance
* Multiplayer behavior
* Problems found during testing
* Evidence collected during execution

Finding a defect was **not required for the testing process to be considered successful**. A test result without reproducible defects is also a valid result.
