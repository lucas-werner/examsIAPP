# Privacy Certifications Practice Quiz

This repository contains a single-page web application that provides interactive practice quizzes for several IAPP certifications. The AIGP exam includes 100 questions, while the CIPP/E, CIPM, CIPP/A and CIPT samples contain smaller question sets for demonstration purposes.

## Opening the Quiz

1. Clone or download this repository.
2. Open the `index.html` file directly in any modern web browser (Chrome, Firefox, Edge, etc.). No additional server setup is required.

The page will load the quiz automatically and start a three‑hour timer when you press **Start**. You can restart the quiz at any time using the **Restart Quiz** button that appears once results are shown.

At the halfway point, the quiz pauses and shows a review screen. Use the flag icon on any question to mark it for review. Flagged questions from the first half appear on this mid-quiz review page so you can revisit them before continuing.

## Prerequisites

The HTML file references Tailwind CSS and Google Fonts via public CDNs and fetches `questions.json` for quiz data. Make sure your computer has internet access when you open `index.html` so these resources can be loaded.

Progress and timer information are saved in your browser's local storage with an identifier for each exam type, so switching between simulators will not overwrite previous progress.

