# Test Cases — Nazi Zombies: Portable

This document contains the manual test cases designed and executed for **Nazi Zombies: Portable**.

## Test Case Summary

| Module         | Test Cases |
| -------------- | ---------: |
| Web System     |          6 |
| Main Menu      |          3 |
| Gameplay       |          4 |
| User Interface |          3 |
| Multiplayer    |         10 |
| Game Modes     |          1 |
| Compatibility  |          5 |
| **Total**      |     **32** |

All 32 test cases were executed during the project.

---

# 1. Web System

## NZP-WEB-001 — Load Game in Chrome

**Module:** WEB
**Title:** Game Loading in Google Chrome

### Steps

1. Open Google Chrome.
2. Enter the game URL.
3. Wait for the game to finish loading.

### Expected Result

The game shows the start screen without WebGL errors.

### Result

**PASS**

---

## NZP-WEB-002 — Load Game in Firefox

**Module:** WEB
**Title:** Game Loading in Mozilla Firefox

### Steps

1. Open Mozilla Firefox.
2. Enter the game URL.
3. Wait for the game to finish loading.

### Expected Result

The game loads the main menu correctly and background music plays.

### Result

**PASS**

---

## NZP-WEB-003 — Load Game in Edge

**Module:** WEB
**Title:** Game Loading in Microsoft Edge

### Steps

1. Open Microsoft Edge.
2. Enter the game URL.
3. Wait for the game to finish loading.

### Expected Result

The game loads the main menu correctly and background music plays.

### Result

**PASS**

---

## NZP-WEB-004 — Restart Game in Chrome

**Module:** WEB
**Title:** Game Restart Using F5

### Steps

1. Start an active game in Google Chrome.
2. Press the F5 key.

### Expected Result

The page reloads and the game returns to the title screen.

### Result

**PASS**

### Observation

During the test, F5 and Ctrl+R did not reload the page while the game was active.

The browser reload button worked correctly and restarted the game.

This observation was recorded during execution but was not registered as a functional bug.

---

## NZP-WEB-005 — Restart Game in Firefox

**Module:** WEB
**Title:** Game Restart Using F5 in Firefox

### Steps

1. Start an active game in Mozilla Firefox.
2. Press the F5 key.

### Expected Result

The page reloads and the game returns to the title screen.

### Result

**PASS**

---

## NZP-WEB-006 — Restart Game in Edge

**Module:** WEB
**Title:** Game Restart Using F5 in Edge

### Steps

1. Start an active game in Microsoft Edge.
2. Press the F5 key.

### Expected Result

The page reloads and the game returns to the title screen.

### Result

**PASS**

---

# 2. Main Menu

## NZP-MN-001 — Start Single Player

**Module:** MN
**Title:** Start a Single-Player Game

### Steps

1. Open the main menu.
2. Select **SOLO**.
3. Select a map.
4. Select **Start Game**.

### Expected Result

The game allows the player to select a map and starts loading the game without visible errors.

### Result

**PASS**

---

## NZP-MN-002 — Adjust Sound

**Module:** MN
**Title:** Change Sound Volume

### Steps

1. Open **CONFIGURATION**.
2. Open **AUDIO**.
3. Set the volume to 0%.

### Expected Result

The game sound is completely muted.

### Result

**PASS**

---

## NZP-MN-003 — Return to Main Menu

**Module:** MN
**Title:** Return to Main Menu

### Steps

1. Open the game options menu.
2. Press **Back** or **Esc**.

### Expected Result

The game returns to the main menu without closing.

### Result

**PASS**

---

# 3. Gameplay

## NZP-GP-001 — Basic Movement

**Module:** GP
**Title:** Player Movement

### Steps

1. Start a game.
2. Press W, A, S and D alternately.

### Expected Result

The player moves in the four directions without passing through walls.

### Result

**PASS**

---

## NZP-GP-002 — Shooting

**Module:** GP
**Title:** Basic Shooting

### Steps

1. Start a game.
2. Press the left mouse button.

### Expected Result

The weapon shows a firing effect and the shooting sound plays.

### Result

**PASS**

---

## NZP-GP-003 — Manual Reload

**Module:** GP
**Title:** Manual Weapon Reload

### Steps

1. Fire five shots.
2. Press the **R** key.

### Expected Result

The character completes the reload animation.

### Result

**PASS**

---

## NZP-GP-004 — Receive Damage

**Module:** GP
**Title:** Player Receives Damage

### Steps

1. Stand still near a zombie.
2. Wait for the zombie to attack.

### Expected Result

A red effect appears around the screen after the player receives damage.

### Result

**PASS**

---

# 4. User Interface

## NZP-UI-001 — Ammo Counter

**Module:** UI
**Title:** Ammo Counter Update

### Steps

1. Fire one shot with the starting weapon.

### Expected Result

The ammunition counter decreases by one.

### Result

**PASS**

---

## NZP-UI-002 — Score Counter

**Module:** UI
**Title:** Score Update

### Steps

1. Eliminate a zombie with one shot.
2. Check the score counter.

### Expected Result

The score counter increases correctly after the enemy is eliminated.

### Result

**PASS**

### Observation

The score system was also observed during execution:

* 20 points for a hit
* 100 points for a firearm kill
* 130 points for a melee kill

---

## NZP-UI-003 — Round Change

**Module:** UI
**Title:** Round Indicator

### Steps

1. Eliminate the last zombie of the current round.

### Expected Result

The next round indicator appears on the screen.

### Result

**PASS**

---

# 5. Multiplayer

## NZP-MP-001 — Access Multiplayer Menu

**Module:** MP
**Title:** Access Multiplayer

### Steps

1. Open the main menu.
2. Select **Multiplayer**.

### Expected Result

The multiplayer menu opens and shows the available multiplayer options.

### Result

**PASS**

---

## NZP-MP-002 — Set Player Nickname

**Module:** MP
**Title:** Player Nickname

### Steps

1. Find the player name field.
2. Enter **Tester1**.

### Expected Result

The field accepts the characters and displays the entered name correctly.

### Result

**PASS**

---

## NZP-MP-003 — Create Multiplayer Game

**Module:** MP
**Title:** Create a Multiplayer Host

### Steps

1. Select **Host Game** or **Create**.
2. Select a map.
3. Select **Start**.

### Expected Result

The selected map loads and the player appears at the spawn point.

### Result

**PASS**

---

## NZP-MP-004 — Return to Main Menu

**Module:** MP
**Title:** Leave Multiplayer Menu

### Steps

1. Open the multiplayer menu.
2. Press **Back** or **Esc**.

### Expected Result

The multiplayer menu closes and the game returns to the main menu.

### Result

**PASS**

---

## NZP-MP-005 — Connect Client to Local Server

**Module:** MP
**Title:** Client Connection

### Steps

1. Create a multiplayer game on the Gigabyte G5 MD.
2. Open Multiplayer on the Positivo BGH AT550.
3. Connect to the local server.

### Expected Result

The client connects to the server and loads the game.

### Result

**PASS**

---

## NZP-MP-006 — Player Visibility

**Module:** MP
**Title:** Check Player Visibility

### Steps

1. Connect both computers to the same game.
2. Move one player.
3. Observe the second computer.

### Expected Result

Both players can see each other inside the game.

### Result

**PASS**

---

## NZP-MP-007 — Simultaneous Player Movement

**Module:** MP
**Title:** Check Simultaneous Movement

### Steps

1. Connect both computers to the same game.
2. Move both players at the same time.

### Expected Result

The movement of both players is shown correctly during the game.

### Result

**PASS**

---

## NZP-MP-008 — Player Leaves During Game

**Module:** MP
**Title:** Player Disconnection

### Steps

1. Start a multiplayer game.
2. Close one of the game clients.

### Expected Result

The session continues and the game handles the player disconnection correctly.

### Result

**PASS**

### Observation

When the host was closed, the other player was returned to the main menu.

---

## NZP-MP-009 — Multiplayer Menu

**Module:** MP
**Title:** Multiplayer Menu Access

### Steps

1. Open the main menu.
2. Select **Multiplayer**.

### Expected Result

The game opens the multiplayer connection or server screen.

### Result

**PASS**

---

## NZP-MP-010 — Connection Attempt

**Module:** MP
**Title:** Multiplayer Connection Attempt

### Steps

1. Open Multiplayer.
2. Select **Connect** for a server.

### Expected Result

The game shows a loading or connection message.

### Result

**PASS**

---

# 6. Game Modes

## NZP-GM-001 — Game Mode Selection

**Module:** GM
**Title:** Select a Different Game Mode

### Steps

1. Select **SOLO**.
2. Select a map.
3. Open **Game Settings**.
4. Change **Classic** to another available mode, such as **Gun Mode**.
5. Start the game.

### Expected Result

The game starts using the rules or settings of the selected mode.

### Result

**PASS**

---

# 7. Compatibility

## NZP-COMP-001 — Initial Load on Low-Resource Hardware

**Module:** COMP
**Title:** Game Loading on Positivo BGH AT550

### Steps

1. Open Mozilla Firefox on the Positivo BGH AT550.
2. Enter the game URL.
3. Wait for the main menu to load.

### Expected Result

The game loads correctly and allows access to the main menu without critical errors.

### Result

**PASS**

---

## NZP-COMP-002 — Start Game on Low-Resource Hardware

**Module:** COMP
**Title:** Start Game on Positivo BGH AT550

### Steps

1. Start the game in Firefox.
2. Select **SOLO**.
3. Select a map.
4. Start the game.

### Expected Result

The game starts correctly and the player can control the character.

### Result

**PASS**

---

## NZP-COMP-003 — Basic Gameplay on Low-Resource Hardware

**Module:** COMP
**Title:** Basic Gameplay on Positivo BGH AT550

### Steps

1. Start a game.
2. Move the character.
3. Fire the weapon.
4. Reload the weapon.

### Expected Result

The player can perform the basic gameplay actions without freezes or unexpected crashes.

### Result

**PASS**

---

## NZP-COMP-004 — Game Stability

**Module:** COMP
**Title:** Stability During Gameplay

### Steps

1. Start a game.
2. Play for at least 10 minutes.
3. Observe the general system behavior.

### Expected Result

The game remains stable without crashes or critical freezes.

### Result

**PASS**

---

## NZP-COMP-005 — Basic Performance on Low-Resource Hardware

**Module:** COMP
**Title:** Performance on Positivo BGH AT550

### Steps

1. Start a game.
2. Enable the FPS counter if available.
3. Play for several minutes.
4. Observe the performance.

### Expected Result

The game maintains enough performance for basic gameplay.

### Result

**PASS**

### Observation

The tested configuration reached approximately **45–50 FPS at 640 × 480 fullscreen**.

This result applies only to the tested hardware and configuration. It is not a general performance benchmark.

---

# Test Execution Summary

| Result    |  Count |
| --------- | -----: |
| PASS      |     32 |
| FAIL      |      0 |
| BLOCKED   |      0 |
| NOT RUN   |      0 |
| **Total** | **32** |

All 32 test cases were executed during the project.
