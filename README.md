# Albi Flutter Evaluation App

A evalutation project for Flutter Engineers.  It starts as the out of the box counting app and interviewee makes changes.

## Rules

- Your camera must be on and your screen must be shared.
- You may use the internet and any search engine to look up syntax or answer a technical question.  However, AI tools like ChatGPT will not be allowed.  These searches must also be done in front of the proctor via screen share.
- You may use any IDE or development tool.
- You may use any state management provider you wish, keep in mind this is a timed test.
- Speaking out loud is encouraged, we want to hear your thought process as you are working through the tasks and solving problems.  You can also express things like "I would do this if I had more time" if prioritizing speed over "clean code" or "best practices".

## Tasks

1. Put an outline around the number being counted.  This outline should be deep purple and have rounded corners of 8, and have a padding of 16 between it and the number.

2. Add text at the top of the page, below the navbar, that says "Let's Count".  Underneath "Let's Count", add a horizontal line the width of the screen.  The counter and outline should remain centered on the screen. 

3. Add text below the underline that says "Fast Count", then below that add 3 buttons that increase counts by 2, 3, or 5.  The buttons should be in a horizontal group and use all the available space. 

4. Below the three fast count buttons, add a text only button that says "More Options".  When clicked, it should open a bottom sheet with a list of numbers 10 to 200 counting by tens i.e (10, 20, 30, ect.). When one of the numbers is clicked the bottom sheet should close and the amount be added to the counter.

5. Below the counter, add a button that says "Custom".  When clicked it should open an entirely new page with a text box at the top and a button below it that says "Add".  When a number is typed into the box and the button is clicked, the page should close and the number be added to the counter.

6. In the navbar of the counter page add a button that says "Reset" that will set the counter back to 0.