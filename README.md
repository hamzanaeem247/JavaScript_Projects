# JavaScript Projects

## 1. Pyramid Generator

- Utilized the `#` character to generate a pyramid structure.
- Created a `padRow` function to build rows, applying the correct spacing and character alignment based on the row number.
- Introduced an `inverted` boolean flag to allow toggling between normal and inverted pyramid generation.
- Made the pyramid height configurable using the `count` variable.
- Added logic to construct and store rows in the `rows` array, either in a regular or inverted order.
- The final output is a formatted string, which is printed to the `console`.

## 2. Gradebook App

- Implemented `getAverage` function to calculate the class average based on an array of scores.
- Created `getGrade` function to determine the student's grade based on their score, supporting grades from A++ to F.
- Added `studentMsg` function to generate a personalized message for students, including their grade and whether they passed or failed the course.
- Integrated logic to compare the student's score against the class average and return appropriate messages:
  - "You passed the course" if the grade is not an "F".
  - "You failed the course" if the grade is an "F".
- Used template literals for dynamic message creation with proper formatting.
