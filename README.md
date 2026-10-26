# Almost There

A finite rage-bait browser game.

You will lose a lot.  
The more you lose, the more you will want to beat it.

---

## Play

1. Open `almost.html` in any modern browser (Chrome, Firefox, Edge, Safari).
2. Click **BEGIN**.
3. Survive.

No install. No account. No download required beyond the HTML file.

---

## What kind of game is this?

**Almost There** is a short-to-medium length game built around one feeling:

> “This game keeps messing with me… but I *will* finish it.”

It mixes different segment types so you never settle into one comfort zone:

| Segment Type          | What you do                                      |
|-----------------------|--------------------------------------------------|
| Control               | Move a character, jump, deal with changing rules |
| Instruction           | Follow a rule while the game tries to trick you  |
| Hybrid / Mutation     | Starts as one type, turns into another           |
| Fake UI / Victory     | Screens that look like the end but aren’t        |

The game is **finite**. There is a real ending. The Narrator eventually has to accept defeat.

---

## Features

- **Hybrid progress** — sometimes you get a clear “Segment Cleared”, sometimes only a fragile checkpoint that disappears if you quit
- **Pause system** — manual pause button + automatic pause when you switch tabs or apps
- **Changing rules** — inverted controls, reverse gravity, bigger floaty jumps, proximity spikes, fake platforms
- **Instruction traps** — “only press the green button”, “do not press anything with the word NO”, color/text contradictions, fake victory screens
- **Narrator** — already in full prank mode from the first second (sarcastic, mean, gaslighting, fake-helpful)
- **Replay variety** — segment order, lies, and mechanics change between runs
- **Real ending** — the Narrator is forced to admit you won

---

## Controls

Controls change depending on the current segment.

**Common:**
- Arrow keys / WASD — move
- Space / W / ↑ — jump
- Mouse — click buttons or drag when required

**Pause:**
- Pause button on screen
- Or switch tab / app (game pauses automatically)

Pause menu options:
- Resume
- Restart current segment
- Return to Main Menu

---

## Important mechanics

### Spikes (proximity only)
- Stay fully hidden until you get close, then suddenly emerge
- Detach and rise so you have to go underneath
- Rise, then slam back down as a fake-out

### Platforms
- Fake and real collapsing platforms look **identical**
- They only start shaking when you stand on them
- Real ones collapse. Fake ones just keep shaking.

### Special jumps
- Sometimes you get a much bigger jump with slower fall (more hang-time)

### Color instructions
- The required button color changes between appearances and runs (not always green)

---

## Technical

- Single self-contained HTML file
- Works even if `localStorage` is blocked (no crash)
- Modern browser recommended

---

## Design intent

The game is intentionally mean in a joyful, competitive way.  
Mild skill digs and sarcasm are part of the experience.  
Extreme insults, family references, and real-world controversy are not.

Rage-quitting is on the player.

---

## File
```
almost.html   ← the game
README.md     ← this file
```
