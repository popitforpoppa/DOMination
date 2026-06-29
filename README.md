# JavaScript Fundamentals Quiz

An interactive quiz game built with plain **HTML, CSS, and JavaScript**. It shows
questions one at a time, gives instant color-coded feedback, tracks your score,
and lets you restart when you're done.

## Features

- Start screen before the quiz begins
- One question shown at a time with dynamically generated answer buttons
- Immediate feedback: green for correct, red for incorrect
- Answer buttons lock after a choice so you can't change your mind
- Live score tracker and progress bar
- Final results screen with a score message
- Restart button to play again

## How to View / Run

No build tools or installation required.

1. Clone or download this repository.
   ```bash
   git clone <your-repo-url>
   ```
2. Open the project folder.
3. Double-click `index.html` (or right-click → "Open with" your browser).

That's it. The quiz runs entirely in the browser.

## File Structure

| File         | Purpose                                              |
| ------------ | ---------------------------------------------------- |
| `index.html` | The structure: start, quiz, and score sections      |
| `style.css`  | The look and feel, including the `.hidden` helper    |
| `script.js`  | The quiz data and all the game logic                 |

## Customizing

- **Add questions:** open `script.js` and add more objects to the `quizData`
  array. Each object needs a `question`, an `options` array, and an `answer`
  (the index of the correct option, starting at 0).
- **Change colors:** edit the CSS variables at the top of `style.css`
  (`--correct`, `--incorrect`, `--accent`, etc.).

## What This Project Practices

- DOM manipulation (updating HTML from JavaScript)
- Event listeners (responding to clicks)
- Conditional logic (checking the user's answer)
- Arrays and loops (storing and rendering questions)

