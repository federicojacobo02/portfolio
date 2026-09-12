# Test Documentation Standards

This document defines the naming rules and basic documentation standards used for the manual testing of **Nazi Zombies: Portable**.

The goal is to keep the test documentation clear, consistent and easy to follow.

## 1. Test Case IDs

Each test case uses the following format:

`NZP-[Module]-[Number]`

### Example

`NZP-GP-001`

Where:

* `NZP` = Nazi Zombies: Portable
* `GP` = Gameplay module
* `001` = Test case number

## 2. Bug IDs

Each bug uses the following format:

`BUG-[Module]-[Number]`

### Example

`BUG-GP-001`

This format identifies the project, the module and the bug number.

## 3. Module Codes

| Code | Module         |
| ---- | -------------- |
| MN   | Main Menu      |
| GP   | Gameplay       |
| UI   | User Interface |
| WEB  | Web System     |
| GM   | Game Modes     |
| MP   | Multiplayer    |
| COMP | Compatibility  |

## 4. Test Case Information

Each test case should contain:

* Test Case ID
* Module
* Title
* Test Steps
* Expected Result

The test steps describe what the tester must do.

The expected result describes what should happen if the system works correctly.

## 5. Bug Report Information

When a reproducible defect is found, the bug report should contain:

* Bug ID
* Module
* Title
* Description
* Steps to Reproduce
* Expected Result
* Actual Result
* Severity
* Priority
* Evidence
* Status

## 6. Severity Levels

Severity describes how much the problem affects the system.

### Blocker

The problem prevents the game from starting or continuing.

### Major

The problem affects an important game function.

### Minor

The problem affects a function but does not stop the main game flow.

### Cosmetic

The problem only affects visual elements, text or small UI details.

## 7. Priority Levels

Priority describes how important it is to fix the problem.

### High

The problem should be reviewed as soon as possible.

### Medium

The problem should be reviewed after higher-priority problems.

### Low

The problem can be reviewed later.

## 8. Test Result Values

The test execution uses the following results:

* **PASS** — The actual result matches the expected result.
* **FAIL** — The actual result does not match the expected result.
* **BLOCKED** — The test cannot be executed because another problem prevents it.
* **NOT RUN** — The test has not been executed yet.

## 9. Multiplayer Test Cases

The original academic documentation contained duplicate Multiplayer IDs.

For this portfolio, the Multiplayer test cases use unique IDs to keep traceability clear.

The final numbering is:

* `NZP-MP-001` — Access Multiplayer Menu
* `NZP-MP-002` — Enter Player Nickname
* `NZP-MP-003` — Create Multiplayer Host
* `NZP-MP-004` — Return to Main Menu
* `NZP-MP-005` — Connect a Second Player
* `NZP-MP-006` — Check Player Visibility
* `NZP-MP-007` — Check Simultaneous Movement
* `NZP-MP-008` — Check Player Exit During Match
* `NZP-MP-009` — Check Multiplayer Menu
* `NZP-MP-010` — Check Connection Attempt

This change only corrects the documentation IDs. It does not change the test results.

## 10. Documentation Goal

These rules were used to make the test documentation easier to read and to keep a clear relationship between:

**Test Plan → Test Cases → Test Execution → Bug Reports → Test Summary**

The same naming rules are used throughout this portfolio project.
