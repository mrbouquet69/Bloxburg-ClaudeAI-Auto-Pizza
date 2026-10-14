---
name: bloxburg-pizza-job
description: Play the Bloxburg Pizza Planet pizza baker job in Roblox on the user's Windows PC with computer use, when asked to make pizzas or work a Bloxburg pizza shift.
---

# Bloxburg Pizza Planet: pizza baker job

Play the job yourself by looking at screenshots and using the mouse and keyboard. Do not write a bot or script. Keep going until the user says stop or the time they gave is reached. When they say stop, stop at once and reply in one line.

## Getting access
- Load the computer-use skill first.
- Request access to `Roblox` and `Roblox Player`. Then take a screenshot. If the game window is still masked, look at which process the screenshot says was hidden (on an Xbox/Store install it is `robloxplayerbeta.exe` under `c:\xboxgames\...`). Resolve that exact basename and request it too.
- If another window covers the game, ask the user to close or minimize it.
- Computer use does not work from cloud sessions that don't run on the PC. If the device says it is off, ask the user to turn on Computer use in the Claude desktop app (Settings, then This computer).

## Keeping focus
- The Claude desktop window often grabs keyboard focus, and key presses then fail. Click the Roblox title bar (around x=700, y=8) before each key press or held key. Do not click in the game world to regain focus, because that can open menus or use a held item.

## Making one pizza
1. Read the order card, the white card with a pizza picture and a green Done button. Zoom on it at full scale (scale 1), because low-resolution zooms hide toppings.
   - Green strips: Vegetables.
   - Pink or light squares: Ham.
   - Darker red round clumps under the cheese: Pepperoni. Plain-looking pizzas often have pepperoni, and missing it gives a red X.
   - Uniform red sauce with only yellow cheese strips: no topping.
2. Press E for Add Dough, then E for Add Tomato Sauce, then E for Add Cheese. Wait about 1.2 seconds between presses, or a press gets lost. Check the next prompt label if unsure.
3. If there is a topping, press E (Interact). A menu opens around the pizza with Add Vegetables, Add Ham, Add Pepperoni and Add Dough. Take a fresh screenshot to find the label, because the camera drifts.
4. Click the topping label, then click the green Done button on the card.
5. A green tick means correct. A red X means wrong. Watch Earnings and Efficiency at the top.

## Clicking that works in Roblox
- Plain instant clicks are often ignored. Make two or three small mouse moves onto the target with about 0.2 seconds between them, pause about 0.3 seconds, then click. If that fails, use mouse down, wait 0.15 seconds, then mouse up.
- Done only responds when the character stands close to the order card. If clicks on Done do nothing, walk a step toward the card (D held about 0.25 seconds) and try again.
- Clicking on your own character opens a Boost Mood/Emotes menu. Close it with its X.

## Restocking ingredients
- When the card says "You're out of ingredients! Take crate to restock", either walk sideways to a station whose bowls are still full, or restock:
  1. Walk to the ingredient crates behind the counter (from the station, S held about 1 second moves toward the camera side). Rotate the camera with the Left or Right arrow keys (about 1.5 seconds turns it around).
  2. Press E or click Take on a crate.
  3. Walk back to a station (S about 1 second when the camera faces the crates). Step until the prompt shows, then press E and choose Restock.

## Camera
- Left and Right arrow keys rotate the camera. About 0.4 seconds is roughly a quarter turn.
- Before each pizza, take a screenshot to find the card and Done positions again.

## Do not touch
- Do not click End Shift in the job panel unless the user asks.
- Do not reply to or type in game chat.

## Tracking
- Note earnings and efficiency every few pizzas, so you can report total earnings and average efficiency when the user asks.
