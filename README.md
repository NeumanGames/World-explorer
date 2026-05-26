# 🌍 World Explorer — Countries & Capitals Quiz

*A free learning game by NeumanGames™*

An interactive geography quiz that helps students and learners of all ages learn every country in the world and their capitals through maps, shapes, and smart practice.

-----

## What It Is

World Explorer is a single HTML file that runs in any web browser — no app store, no installation, no internet required after the first load. Students study the **geographic shape and location** of every country, and learn all **capital cities**, through four different quiz modes and a built-in learning algorithm that focuses practice where it’s needed most.

-----

## How to Use It

### Opening the App

Open the file in any web browser or visit the hosted URL. Works on any device with a web browser. On a tablet or mobile device, use your browser’s **“Add to Home Screen”** option to save it as a full-screen app icon for easy access.

> **Note:** The file must be opened in a browser (Safari, Chrome, etc.) — not from a file manager or Files app — for the interactive features to work.

-----

### Choosing a Quiz Mode

Four modes are available in the sidebar:

|Mode                   |How It Works                                                                                                        |
|-----------------------|--------------------------------------------------------------------------------------------------------------------|
|🗺️ **Click the Country**|A country name appears — tap the correct shape on the map. The capital city is shown as an early association hint   |
|📝 **Name the Country** |A country highlights on the map — pick its name from 4 choices                                                      |
|🏛️ **Find the Capital** |A capital city name appears — tap the correct country on the map                                                    |
|📖 **Study Mode**       |Browse all countries one at a time with name and capital shown. Use the search box to jump to any country or capital|

Switch modes any time. Your learning progress carries over across all modes.

-----

### Study Mode

Study Mode is the default starting mode and is designed for first-time learners. Each country is highlighted on the map one at a time with its name and capital displayed in the sidebar.

- **Click the highlighted country** to advance to the next one
- Use the **Search box** to find any country by name or capital city — it will highlight on the map and pan into view automatically
- **Tooltip toggles** control what appears when hovering over a country:

|Country name|Capital city|Tooltip shows                   |
|------------|------------|--------------------------------|
|✅           |✅           |`Washington D.C., United States`|
|✅           |☐           |`United States`                 |
|☐           |✅           |`Washington D.C.`               |
|☐           |☐           |No tooltip                      |

- **Tooltip in quiz** — enable this to allow hover tooltips during quiz modes as a learning aid

-----

### Navigating the Map

The world map supports full zoom and pan:

- **Scroll / pinch** — zoom in and out
- **Click and drag** — pan around the map
- **＋ / － buttons** — zoom in or out in steps
- **⌂ button** — reset to the default full-world view

Zoom in to see smaller countries like Luxembourg, Singapore, or island nations more easily.

-----

### Score Bar

The pills at the top of the screen track the current session:

- ✅ **Correct** — total right answers this session
- ❌ **Wrong** — total wrong answers this session
- 🔥 **Streak** — consecutive correct answers (hitting 3 in a row triggers a confetti celebration)
- 🌍 **Learned** — countries marked as mastered by the learning algorithm

-----

### Progress Panel

Click **📊 Progress — Show** in the sidebar to expand the progress tracker. It displays all 177 countries as small colored tiles:

|Color  |Meaning                                                              |
|-------|---------------------------------------------------------------------|
|⬜ Gray |Not yet seen                                                         |
|🟡 Amber|Seen but still learning — answered incorrectly or no streak yet      |
|🔵 Blue |Familiar — at least one correct answer in a row and over 50% accuracy|
|🟢 Green|Mastered — three or more correct in a row and over 75% accuracy      |

Hover over any tile to see exact stats for that country (how many times seen, accuracy percentage). The goal is to turn all 177 tiles green.

-----

### How the Learning Algorithm Works

World Explorer uses a **spaced repetition** system — the same technique used in professional flashcard apps — adapted for geography learning. It also uses **passive association** to introduce capitals before they are formally tested:

- **Countries never seen** are introduced with high priority so all 177 are encountered over time
- **Wrong answers** bring that country back quickly and more often until the student gets it right
- **Correct answers** gradually reduce how often that country appears — one right answer lowers the frequency, two in a row lowers it further, and three or more in a row moves the country to rare review
- **Distractors** (the wrong choices in multiple choice) are drawn from the countries the student is currently struggling with most, making the wrong options meaningfully challenging rather than random
- A **cooldown** of 4 questions prevents the same country from appearing back-to-back, so repetition feels natural rather than mechanical

The result is that a student who keeps getting France right will see it less and less, while a country like Kyrgyzstan that keeps getting confused will reappear frequently until it sticks.

**Capital association** is introduced in the Click the Country mode, where the capital city name appears alongside every country name question. Students absorb the country-capital pairing through repeated exposure before being formally tested on it in the capital quiz modes — a technique known as priming that reduces the cognitive load when the formal test arrives.

-----

### After Answering

In all quiz modes, after each answer:

- The correct country is highlighted **green** on the map
- Any wrong selection is highlighted **red**
- A **Next ▶** button appears — the question stays visible until you are ready to move on

-----

## Tips for Teachers and Parents

- Start in **Study Mode** to build familiarity with country shapes and locations before quizzing
- Turn on **Tooltip: Country name** and **Tooltip: Capital city** while still learning, so hovering reveals both
- In **Click the Country** mode, the capital is shown alongside every question — this passively builds capital associations before they are formally tested
- Turn the **Country hover** tooltip off when quizzing on country names — otherwise the tooltip gives the answer away. Leave **Capital hover** on to continue reinforcing capital associations during practice
- Use **Tooltip in quiz** (Study Assist) as a stepping stone — students can hover to check their answer before clicking, building confidence without penalty
- After a student masters a region, use the **Search box** in Study Mode to revisit specific countries they found difficult
- Progress is saved within a single browser session. Refreshing the page resets progress, so encourage students to complete a full practice session before closing

-----

## Files

|File        |Description                                                                       |
|------------|----------------------------------------------------------------------------------|
|`index.html`|The entire NeumanGames™ World Explorer app — fully self-contained, no dependencies|
|`README.md` |This document                                                                     |

To use on GitHub Pages, push both files to a public repository and enable GitHub Pages in the repository Settings under Pages → Source → main branch. The live version of this README is published at **[github.com/NeumanGames/World-explorer](https://github.com/NeumanGames/World-explorer)**.

-----

## Play Now

🌍 **[worldexplorer.neumangames.com](https://worldexplorer.neumangames.com)**

Also available directly at: [neumangames.github.io/World-explorer](https://neumangames.github.io/World-explorer)

-----

## Support NeumanGames™

Every game on this platform is free, forever. If World Explorer has been helpful for a student in your life, your support helps us build the next one.

- 🎁 **One-time donation:** [ko-fi.com/neumangames](https://ko-fi.com/neumangames)
- ⭐ **Monthly support & community:** [patreon.com/NeumanGames](https://www.patreon.com/NeumanGames)

Works on any device with a web browser — no login, no download, no cost.

-----

## Legal

© 2026 NeumanGames™. All rights reserved.

NeumanGames™ is a trademark of NeumanGames. World Explorer is a free educational game provided for personal and classroom use. Unauthorized reproduction or commercial use is prohibited.

This game is provided free of charge. No fees, no subscriptions, no paywalls — ever.

For permissions beyond personal and classroom use, please contact us through [Patreon](https://www.patreon.com/NeumanGames) or [Ko-fi](https://ko-fi.com/neumangames).

© 2026 NeumanGames™ — [neumangames.github.io](https://neumangames.github.io) · [worldexplorer.neumangames.com](https://worldexplorer.neumangames.com)