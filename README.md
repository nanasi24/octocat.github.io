# True/False Quiz App

An interactive web-based quiz app built with vanilla HTML, CSS, and JavaScript — no frameworks or libraries required.

## Overview
This app presents a series of true/false (○/✕) questions, lets the user answer each one, and immediately shows whether the answer was correct along with a short explanation. Users can filter questions by round/session and track their score in real time.

- **Tech stack**: HTML, CSS, JavaScript (all in a single file, no external dependencies)
- **Data**: Questions are stored as a JavaScript array of objects (question text, correct answer, explanation)

## Features
- **True/False question format** with instant feedback and explanations
- **Filter by round** using a dropdown menu, so users can practice a specific session's questions
- **Live score tracking** showing correct answers out of total answered
- **Reset button** to clear all answers and start over
- **Responsive design** that adapts to mobile screen sizes

## How It Works
1. The user selects a round from the dropdown (or views all questions)
2. Questions are rendered dynamically from a JavaScript data array
3. Clicking ○ or ✕ locks in the answer and reveals whether it was correct, plus an explanation
4. The score board updates automatically as questions are answered
5. The reset button clears all answers and reloads the question list

## How to Run
Simply open `index.html` in any web browser — no server or build step needed.

## Possible Improvements
- Persist scores between sessions using local storage
- Add a timer or quiz mode with a final results summary
- Load questions from an external JSON file instead of hardcoding them in the script