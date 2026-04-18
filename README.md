Laboratory Work No. 3: JavaScript – Functions, Date & Time, Regular Expressions
Course: Web Programming and Web Design
University: Kherson National Technical University
Faculty: Information Technologies and Design
Department: Software and Technologies
Group: 2PR1
Author: O.O. Korniienko
Instructor: O.S. Komisarov
Year: 2026

Project Description
This project implements 10 tasks on the topic JavaScript: Functions, Date & Time, Regular Expressions as part of Laboratory Work No. 3.
Each task is implemented as a separate web page using HTML, CSS, and JavaScript.
The interface features a dark theme, responsive design, and easy navigation between all tasks.

Technologies Used
HTML5

CSS3 (Flexbox, responsive design)

JavaScript (ES6+)

Regular Expressions

DOM manipulation

Event handling

Tasks
Task 1: Functions (4 subtasks)
1.1 Change Font Size
A function that accepts a text string and a font size value, then displays the text with the given font-size CSS property.

1.2 Strings to HTML Table
A function that takes an array of strings and generates an HTML table where each string is placed in a separate cell (<td>).

1.3 Create Headers (createHeaders(N))
A function that creates N second-level headings (<h2>) on the page with the text Header1, Header2, ..., HeaderN.

1.4 Universal Function (Max / Sum / Sentence)
A function that accepts any number of parameters (numbers and words) and:

Finds the maximum number OR the sum of all numbers (user chooses)

Creates a sentence from the passed words

Example:
someFunction('Jane', 1, 3, 'like', 5, 9, 'read', 4, 'book');

Sum = 22

Sentence = "Jane like read book"

Task 2: Date & Time (2 subtasks)
2.1 Current Date and Time
A function that displays the current date in the format:
Date: 12 March 2017
Day of week: Sunday
Time: 15:08
The function runs when a button is clicked.

2.2 Relative Date
The user inputs a date in one of the formats: dd.mm.yyyy, dd/mm/yyyy, or dd-mm-yyyy.
The program outputs:

Today – if the date is today

Yesterday – if the date was yesterday

2 days ago … 6 days ago – if 2–6 days have passed

A week ago – if exactly 7 days have passed

A year ago – if exactly one year has passed

Otherwise – outputs the date in YYYY.MM.DD format

Task 3: Regular Expressions (4 subtasks)
3.1 Find Dates (findDates(text))
Finds all valid dates in the format YYYY-MM-DD inside a given text using regular expressions.
Example: "2024-12-25" → valid date.

3.2 snake_case → lowerCamelCase
Converts a variable name from snake_case to lowerCamelCase using regular expressions.
Examples:

my_variable → myVariable

new_brand_product → newBrandProduct

3.3 camelCase → snake_case
The inverse conversion: from camelCase to snake_case using regular expressions.
Examples:

myVariable → my_variable

newBrandProduct → new_brand_product

3.4 Find HEX Colors (findHexColor(text))
Finds all color codes in the format #RGB (3 hex digits) or #RRGGBB (6 hex digits) inside a given text. Returns null if none are found.
Examples: #FFF, #abc, #A1B2C3

lab3-js-functions-date-regex/
├── index.html          # Main menu with links to all tasks
├── 11.html             # Task 1.1 – Change font size
├── 12.html             # Task 1.2 – Strings to HTML table
├── 13.html             # Task 1.3 – Create N headers (h2)
├── 14.html             # Task 1.4 – Universal function (sum/max + sentence)
├── 21.html             # Task 2.1 – Current date and time
├── 22.html             # Task 2.2 – Relative date (Today, Yesterday, etc.)
├── 31.html             # Task 3.1 – Find dates YYYY-MM-DD
├── 32.html             # Task 3.2 – snake_case → camelCase
├── 33.html             # Task 3.3 – camelCase → snake_case
├── 34.html             # Task 3.4 – Find HEX colors (#RGB / #RRGGBB)
└── README.md           # This file

How to Run
Clone the repository or download all files.

Open index.html in any modern web browser.

Use the main menu to navigate to any task.

Each task page contains input fields, action buttons, a result display, and a Clear button where applicable.

Note: All processing is done client‑side with JavaScript. No web server is required.

Usage Examples
Task 1.4
Input: Jane 1 3 like 5 9 read 4 book (action: sum)
Output:

Sum = 22

Sentence = Jane like read book

Task 2.2
Input: 15.03.2026 (if today is 15.03.2026) → Output: Today

Task 3.1
Input text: Events: 2024-12-25, 2023-01-15, invalid 2025-13-01
Output: 2024-12-25, 2023-01-15

Task 3.4
Input text: Colors: #FFF, #abc, #A1B2C3
Output: #FFF, #abc, #A1B2C3 (with color preview)

Implementation Features
Input validation for dates, numbers, and text.

Error handling (invalid date formats, empty fields, etc.).

User‑friendly UI – dark theme, hover effects, Enter key support on many inputs.

Cross‑browser compatibility – works correctly in Chrome, Firefox, Edge, Safari.

Regular expressions used for pattern matching and text transformation.

Author
O.O. Korniienko
Student of group 2PR1
Kherson National Technical University

License
This project was created for educational purposes. Free use and modification are allowed.
