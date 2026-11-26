# FLK Revision Games

Two browser games for SQE1 revision, covering FLK1 and FLK2. Each game is a plain HTML page with no build step and nothing to install. Both games share the question bank in `questions.js`.

## The games

### FLK Court (`flk-court.html`)
A single-best-answer quiz in the SQE1 style: five options, one best answer.
- 74 questions across all 14 FLK subjects, many set as client scenarios, each with an explanation citing the relevant case or statute
- Choose a paper, a mix of subjects and a round length
- Three modes: practice, exam pace at 1 min 42 s per question, or a mock exam with one clock for the whole round, flagging, and no answers shown until you submit
- A record of accuracy for each subject, with weak subjects shown in red
- An editor for adding your own questions

### Order in the Kitchen (`order-in-the-kitchen.html`)
A kitchen-rush game with two modes.
- **Best answer:** each order is an SQE1-style question with five options. Pick the best one before the table walks out. Wrong answers are sent back with the explanation, and the clock pauses while you read.
- **Letter grid:** each order is a clue for a legal term. Trace it through a 6×6 grid of letters, diagonals included, before the ticket burns.
- Earn tips for speed and combos, aiming for three stars
- The results screen lists everything you need to go over

## Playing
Open `index.html` in a browser, or use the GitHub Pages site if it's enabled for this repo. On an iPhone or iPad, open the page in Safari, tap Share, then Add to Home Screen.

Scores and any questions you add are saved in the browser on that device only.

## Note
The questions were written for revision practice. Rates, thresholds and time limits can change, so check anything you're unsure of against your course materials.
