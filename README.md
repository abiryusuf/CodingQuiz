# Web-APIs-HW_4-
# 04 Web APIs: Code Quiz

As you proceed in your career as a web developer, you will probably be asked to complete a coding assessment, which is typically a combination of multiple-choice questions and interactive challenges. Build a timed code quiz with multiple-choice questions. This app will run in the browser and feature dynamically updated HTML and CSS powered by your JavaScript code. It will also feature a clean and polished user interface and be responsive, ensuring that it adapts to multiple screen sizes.

## User Story

```
AS A coding bootcamp student
I WANT to take a timed quiz on JavaScript fundamentals that stores high scores
SO THAT I can gauge my progress compared to my peers
```

## Acceptance Criteria

```
GIVEN I am taking a code quiz
WHEN I click the start button
THEN a timer starts and I am presented with a question
WHEN I answer a question
THEN I am presented with another question
WHEN I answer a question incorrectly
THEN time is subtracted from the clock
WHEN all questions are answered or the timer reaches 0
THEN the game is over
WHEN the game is over
THEN I can save my initials and score
```

The following animation demonstrates the application functionality:

![code quiz](./Assets/04-web-apis-homework-demo.gif)

### Review

You are required to submit the following for review:

* The URL of the functional, deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

- - -
© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.

<!-- Outline/Pseudo code for HW-week 4
// Create Q&A Object.  Maybe an array? 
// ex. Q&A = [
//   { q: " what is this?" 
//      1: " "
//      2: " "
//      3: " "
//      4: " "
//      a: 2 }
//       ]
// Create Start Button (HTML)
// Attach a click event 
		// Start timer countdown (recommend using the setInterval method) 
		// Generate first question + answers + data attributes 
		// add "click" event for answer buttons 
			// increment a counter
			// Generate question 
			// if incorrect 
				//deduct time counter -->